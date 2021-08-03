pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    val1 = 10
                    val2 = 20
                    val3 = 30
                    if (val1 > val2 && val1 > val3) {
                        println "val1 is big, ${val1}"
                    }
                    else if (val2 > val1 && val2 > val3 ){
                        println "val2 is big, ${val2}"
                    }
                    else {
                        println "val3 is big, ${val3}"
                    }
                }
            }
        }
    }
}
