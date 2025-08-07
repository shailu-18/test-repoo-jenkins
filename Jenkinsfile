pipeline {
    agent any

    stages {
        stage('Build from git') {
            steps {
               bat '''
               git clone https://github.com/shailu-18/test-repoo-jenkins.git
               echo done
               '''
            }
                
        }
    }
}
