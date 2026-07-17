# cicd-pipeline-train-schedule-pipelines App Deployes to AWS EC2 To Staging -- To - Prod Stage with Approval 


This is a simple train schedule app written using nodejs. It is intended to be used as a sample application for a series of hands-on learning activities.
Your CI/CD pipeline is Follows Above Process:

You now have:

✅ Source control with GitHub

✅ GitHub Actions CI/CD

✅ Automated testing

✅ Docker image build

✅ Docker Hub integration

✅ Automated staging deployment

✅ Manual approval gate before production

✅ Automated production deployment
2 stage application

## Running the app

You need a Java JDK 7 or later to run the build. You can run the build like this:

    ./gradlew build

You can run the app with:

    ./gradlew npm_start

Once it is running, you can access it in a browser at [http://localhost:3000](http://localhost:3000)
To Run this app on AWs EC2 You should already have AWS EC2 VM Created and have above softwares installed and configured on AWs EC2 --
- Docker
- Port Open 80 3000
- Create ssh key .pem file
- Access App - http://AWS-EC2-Public-IP:80
- 

