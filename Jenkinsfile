pipeline {
    agent {
        label "java-node"
    }
    environment {
        DAY = "sun"
    }
    stages {
        stage ("buils") {
            when {
                environment name: "DAY", value:"sun"
            }
            steps{
                echo "print"
            }
        }
    }
}
