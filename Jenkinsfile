pipeline {
    agent {
        label "java-node"
    }
    environment {
        name =  "Suresh"
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
