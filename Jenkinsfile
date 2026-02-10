pipeline {
    agent {
        label "java-node"
    }
    stages {
        stage ("build") {
            steps {
                echo "build stage from feature branch"
            }
        }
         stage ("scan") {
            steps {
                echo "scan stage from feature branch"
            }
        }
         stage ("dockerbuild") {
            steps {
                echo "dockerbuild stage from feature branch"
            }
        }
         stage ("deployment") {
            steps {
                echo "deploy stage from feature branch"
            }
        }
    }
}
