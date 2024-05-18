pipeline {
    agent any
    stages {
        stage('Clone and List Files') {
            steps {
                script {
                    // Clean up workspace to avoid conflicts
                    // deleteDir()

                    // Clone the second repository
                    git url: 'https://github.com/omar-el-esawy/dida', branch: 'main'

                    // List the files in the cloned repository
                    bat '"C:\\Program Files\\Git\\bin\\bash.exe" -c "ls"'
                }
            }
        }
    }
}
