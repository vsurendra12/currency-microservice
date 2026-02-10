pipeline {
    agent {
        label "java-node"
    }
    environment {
        BRANCH_NAME = "prod"
    }
    stages {
        stage ("build") {
            when {
                allOf {
                    branch 'prod'
                environment name: "BRANCH_NAME", value : "prod"
                }
            }
            steps {
                echo "just print"
            }
        }
    }
}
