pipeline {
    agent any 
    
    stages{
        stage("Cloning the  Code"){
            steps {
                git url:"https://github.com/Srijanatmg12/aws-elastic-beanstalk-express-js-sample.git", branch: "main"
            }
        }
        stage("Building the image"){
            steps {
                sh "docker build -t my-node-app ."
            }
        }
   }
}
