pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    File myfile = new File("/tmp/batc2.txt")
                    println "context of myfile is ${myfile.readLines()}"
                    for (line in myfile.readLines()) {
                        println "my line is ${line}"
                    }
                }
            }
        }
    }
}
