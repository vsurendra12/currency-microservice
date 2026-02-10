pipeline {
    agent {
        label "java-node"
    }
    environment {
        BENNCH_NAME = "pwd"
    }
    stages {
        stage ("build") {
            when {
                allOf {
                    branch 'pro'
                environment name: "BENCH_NAME", value : "pwd"
                }
            }
            steps {
                echo "just print"
            }
        }
    }
}
