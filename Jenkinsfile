pipeline {
    agent {
        label "java-node"
    }
    environment {pipeline {
    agent {
        label "java-node"
    }
    environment {
        name =  "Surendra"
        course = "Welcome to devops course"
        my_cred = credentials("surendra_text")
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
            echo "print ${my_cred}"
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
        name =  "Surendra"
        course = "Welcome to devops course"
        my_cred = credintials ("surendra_text")
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
            echo "print my cred ${my_cred}"
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
