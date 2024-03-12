## CI/CD Pipeline with GitHub Actions

The objective of this project is to create a CI/CD pipeline using GitHub Actions. The pipeline will build the React app code and deploy it to an S3 bucket in AWS. The S3 bucket has been created using Terraform.

### Prerequisites

Before setting up the pipeline, make sure you have the following:

- An AWS account
- Terraform installed on your local machine
- Access and secret keys for your AWS account

### Steps

1. Fork this repository to your GitHub account.
2. Clone the forked repository to your local machine.
3. Update the AWS access and secret keys in the GitHub repository secrets.
4. Open the terminal and navigate to the project directory.
5. Run `npm install` to install all the dependencies.
6. Run `npm start` to start the app in development mode.
7. Open [http://localhost:3000](http://localhost:3000) to view the app in the browser.
8. Make any necessary changes to the app code.
9. Commit and push the changes to the repository.
10. GitHub Actions will automatically trigger the pipeline.
11. The pipeline will build the app code and deploy it to the S3 bucket in AWS.
12. Once the deployment is complete, you can access the app at the S3 bucket URL.

For more information, refer to the following resources:

- Reactjs: [https://reactjs.org/docs/create-a-new-react-app.html](https://reactjs.org/docs/create-a-new-react-app.html)
- react-textfit: [https://www.npmjs.com/package/react-textfit](https://www.npmjs.com/package/react-textfit)
- box-shadow: [https://box-shadow.dev/](https://box-shadow.dev/)

### Video Tutorial

You can watch a video tutorial for this project on YouTube [here](https://youtu.be/o89bhL-S6g8).