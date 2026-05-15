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
                echo 'Running unit and integration tests using JUnit and Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Performing code analysis using SonarQube'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Performing security scan using OWASP Dependency Check'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Deploying application to AWS EC2 staging server'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running staging integration tests using Postman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Deploying application to production environment using Docker'
            }
        }
    }
}