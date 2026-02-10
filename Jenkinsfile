

pipeline {
    agent {
        label "java-node"
    }
    stages {
        stage ("Build") {
             echo "build stage from feature branch"
        }
        stage ("scans") {
             echo "scan stage from feature branch"
        }
         stage ("docker-Build") {
             echo "docker stage from feature branch"
        }
         stage ("deployment") {
             echo "deploy stage from feature branch"
        }
    }

}
