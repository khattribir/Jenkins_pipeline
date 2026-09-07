pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building application using Maven'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Running JUnit and TestNG tests'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Running SonarQube analysis'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Running OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to AWS Staging Server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running Selenium Tests'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying to AWS Production Server'
            }
        }

    }
}
