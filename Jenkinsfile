pipeline {
    agent any
    stages {
        stage('my first stage') {
            steps {
                script {
                    for (i=1; i<10; i++) {
                        println "value of is ${i}"
                    }
                    lis1 = ["obj1", "obj2", "obj3"]
                    for (ele in lis1) {
                        println "my list of object is ${ele}"
                    }
                }
            }
        }
    }
}
