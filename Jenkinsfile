pipeline {
    agent {
        label "java-node"
    }
    environment {
        MONTH_NAME = "AUG"
    }
    stages {
        stage ("build") {
            when {
                expression { BRANCH_NAME ==~ /(prod|hotfix)/ }
            }
            steps {
                echo "print"
            }
        }
    }
}
