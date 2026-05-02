pipeline {
    agent any

    stages {
        stage('BUILD') {
            steps {
                echo 'STAGE 1: BUILD - Using Maven to compile and package the code.'
                echo 'TOOL: Maven'
            }
        }
        stage('UNIT AND INTEGRATION TESTS') {
            steps {
                echo 'STAGE 2: UNIT AND INTEGRATION TESTS - Running unit tests with JUnit and integration tests with TestNG.'
                echo 'TOOLS: JUnit, TestNG'
            }
        }
        stage('CODE ANALYSIS') {
            steps {
                echo 'STAGE 3: CODE ANALYSIS - Analysing code quality using SonarQube to ensure industry standards.'
                echo 'TOOL: SonarQube'
            }
        }
        stage('SECURITY SCAN') {
            steps {
                echo 'STAGE 4: SECURITY SCAN - Scanning for vulnerabilities using OWASP Dependency-Check.'
                echo 'TOOL: OWASP Dependency-Check'
            }
        }
        stage('DEPLOY TO STAGING') {
            steps {
                echo 'STAGE 5: DEPLOY TO STAGING - Deploying the application to AWS EC2 staging instance.'
                echo 'TOOL: AWS CLI'
            }
        }
        stage('INTEGRATION TESTS ON STAGING') {
            steps {
                echo 'STAGE 6: INTEGRATION TESTS ON STAGING - Running integration tests on staging environment.'
                echo 'TOOL: Selenium'
            }
        }
        stage('DEPLOY TO PRODUCTION') {
            steps {
                echo 'STAGE 7: DEPLOY TO PRODUCTION - Deploying application to AWS EC2 production instance.'
                echo 'TOOL: AWS CLI'
            }
        }
    }
}