def sum(a=20, b=30) {
    println "sum of ${a}, ${b} is"+ (a+b)
}

pipeline {
    agent any
    stages {
        stage('working with functions') {
            steps {
                script {
                    sum(10,30)
                    sum()
                }
            }
        }
    }
}
