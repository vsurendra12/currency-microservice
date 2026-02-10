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
            environment {
                cloud = "gcp"
            }
            steps{
            echo "hello ${name}"
            echo "thanks and ${course}"
            echo "you are certified in ${cloud}"
            }
        }
        stage ("second-satge") {
            environment {
                cloud = "k8s"
                name = "surendra"
            }
            steps{
            echo "hello ${name}"
            echo "thanks and ${course}"
            echo "you are certified in ${cloud}"
            }
        }
        stage ("third-satge") {
            environment {
                name = "sam"
                cloud = "docker"
            }
            steps{
            echo "hello ${name}"
            echo "thanks and ${course}"
            echo "you are certified in ${cloud}"
            }
        }
    }
}
