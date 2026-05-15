pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Compiling the source code and preparing the application package with Maven.'
            }
        }

        stage('Unit and Integration Tests') {
            steps {
                echo 'Executing unit checks with JUnit and validating component interaction through Selenium'
            }
        }

        stage('Code Analysis') {
            steps {
                echo 'Reviewing the codebase with SonarQube to identify quality issues and coding standard violations'
            }
        }

        stage('Security Scan') {
            steps {
                echo 'Scanning project dependencies with OWASP Dependency Check to detect known vulnerabilities'
            }
        }

        stage('Deploy to Staging') {
            steps {
                echo 'Publishing the latest application build to a staging AWS EC2 environment for validation'
            }
        }

        stage('Integration Tests on Staging') {
            steps {
                echo 'Running API and workflow checks in the staging environment using Postman'
            }
        }

        stage('Deploy to Production') {
            steps {
                echo 'Releasing the verified application build to the production environment using Docker'
            }
        }
    }
}