def frontendImage="visse0001/frontend"
def backendImage="visse0001/backend"
def backendDockerTag=""
def frontendDockerTag=""
def dockerRegistry=""
def registryCredentials="dockerhub"

pipeline {
    agent {
        label 'agent'
    }
    stages {
        stage('Get code') {
            steps {
                checkout scm
            }
        }
    }
}