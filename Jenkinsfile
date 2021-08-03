pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    a = input message: 'please enter a value' , parameters:
                    [string(defualtValue: '10', description: '', name: 'myval', trim: false)]
                    println "my a value is ${a}"
                }
            }
        }
    }
}
