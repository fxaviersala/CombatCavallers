pipeline {
    agent any
    stages {
        stage("compilar") {
            steps {
                echo "compilar"
                dotnetBuild sdk: 'net5'
            }
        }
    }
}