@Library('jenkinslib') _
pipeline {
    agent any
    stages {
        stage("call lib") {
            steps {
                welcome("akash","31")
                script {
                    calculate.add(4,5)
                    calculate.mul(5,6)
                }
            }
        }
    }
}
