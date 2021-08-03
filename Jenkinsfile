def myfun() {
    println "hi i am inside myfun function"
}

pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    myfun()
                }
            }
        }
    }
}
