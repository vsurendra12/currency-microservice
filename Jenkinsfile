pipeline {
    agent {
        label "java-node"
    }
    environment {
        DAY = "sun"
        CLASS = "first"
    }
    stages {
        stage ("build") {
            when {
                environment name: "DAY", value:"sun"
            }
            steps{
                echo "print if this is sun "
            }
        }
        stage ("scan") {
            steps {
                echo "testing"
                echo "i am in ${CLASS}"
                echo "this is ${DAY}"
            }
        }
    }
}
