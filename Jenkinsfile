pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    a = 1
                    while (a <=10) {
                        println "value of a is ${a}"
                        a = a + 1
                    }
                }
            }
        }
    }
}
