pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
                echo 'Tool: Maven'
                echo 'Task: Build the code using Maven to compile and package the application.'
            }
        }
        stage('Unit and Integration Tests') {
            steps {
                echo 'Running Unit and Integration Tests...'
                echo 'Tool: JUnit for unit tests and Selenium for integration tests'
                echo 'Task: Run unit tests to ensure code functions as expected.'
                echo 'Task: Run integration tests to ensure components work correctly together.'
            }
        }
        stage('Code Analysis') {
            steps {
                echo 'Code Analysis'
                echo 'Tool: SnyK'
                echo 'Task: Analyse code for vulnerabilities and code quality issues.'
            }
        }
        stage('Security Scan') {
            steps {
                echo 'Security Scanning'
                echo 'Tool: SonarQube'
                echo 'Task: Scan code for security vulnerabilities.'
            }
        }
        stage('Deploy to Staging') {
            steps {
                echo 'Deploying to Staging'
                echo 'Tool: AWS EC2'
                echo 'Task: Deploy the application to a staging server for further testing.'
            }
        }
        stage('Integration Tests on Staging') {
            steps {
                echo 'Integration Testing on Staging'
                echo 'Tool: Selenium'
                echo 'Task: Run integration tests on staging environment to make sure everything works in production deployment.'
                
            }
        }
        
        }
    }
}
