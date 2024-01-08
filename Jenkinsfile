pipeline {
    agent {
        node {
            label 'Maven-Agent'
        }
    }

    stages {
        stage('clone this particular repository') {
            steps {
                git branch: 'main', url: 'https://github.com/SNikhil786/devops-project-workshop.git'
            }
        }
    }
}
