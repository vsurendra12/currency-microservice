pipeline {
    agent {
        label "java-node"
    }
    environment {
        BENCH_NAME = "pwd"
    }
    stages {
        stage ("build") {
            when {
                allOf {
                    branch 'main'
                environment name: "BENCH_NAME", value : "pwd"
                }
            }
            steps {
                echo "just print"
            }
        }
    }
}
