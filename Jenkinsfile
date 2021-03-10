pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                when {
                expression {
                    BRANCH_NAME == 'PET-CLINIC'
                }
            }
                echo 'Building..'
            }
        }
        stage('Test') {
             when {
                expression {
                    BRANCH_NAME == 'PET-CLINIC'
                }
            }
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
             when {
                expression {
                    BRANCH_NAME == 'PET-CLINIC'
                }
            }
            steps {
                echo 'Deploying....'
            }
        }
    }
}