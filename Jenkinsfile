pipeline {
    agent any

    stages {
        stage('Build') {
            when {
                expression {
                    BRANCH_NAME == 'PET-CLINIC'
                }
            }
            steps {
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