pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    File myfile = new File("/tmp/devops.txt")
                    myfile.append("hi John")
                    }
                }
            }
        }
    }
}
