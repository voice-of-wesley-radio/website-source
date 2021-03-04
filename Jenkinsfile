pipeline {
        agent any
        stages{
                stage('Checkout') {
                        steps {
                                checkout scm
                        }
                }
                stage('List Project') {
                        steps {
                                sh(script: 'find . -type f', label: 'List Project')
                        }
                }
        }
}
