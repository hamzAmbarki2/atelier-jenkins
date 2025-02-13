pipeline {
    agent any
    triggers {
        pollSCM('H/5 * * * * *') // Toutes les 5 secondes
    }
    stages {
        stage('Test') {
            steps {
                echo "Build déclenché à: ${new Date()}"
            }
        }
    }
}
