pipeline {
    agent {
        label "java-node"
    }
    environment {
        name =  "Surendra"
        course = "Welcome to devops course"
    }
    stages {
        stage ("first-satge") {
            steps{
            echo "hello ${name}"
            echo "thanks and ${course}"
            }
        }
    }
}
