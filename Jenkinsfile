pipeline {
    agent {
        label "java-node"
    }
    environment {
        DAY = "mon"
    }
    stages {
        stage ("buils") {
            when {
                environment name: "DAY", value:"sun"
            }
            steps{
                echo "print this is sun if no sunday then don't"
            }
        }
    }
}
