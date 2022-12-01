# pipeline

### The pipeline using CircleCI going through the following steps till it deploy the app onto AWS:

<img src="https://project3-images.s3.amazonaws.com/pipeline+diagram.png" width="600" height="600">

- The developer codes the project and push it.
- Create circleCI account and link you github repo with it.
- circleCI will trigger the workflow every time you push the code.
- circleCI will install requirements.
- circleCI will build the app.
- after successful build stage, the deploy stage will start.
