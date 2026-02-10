pipeline {
    agent {
        label "java-node"
    }

    environment  {
        TODAY_DAY = "monday"
    }
    stages {
        stage ("build") {

            when {
                environment name: 'TODAY_DAY' , value : 'monday'
            }
            steps {
             echo "excute for nothing"   
            }
        }
    }
}
