pipeline {
agent any

tools {
    maven 'Maven'
}

stages {
    stage('Build and Test') {
        steps {
            bat 'mvn clean test package'
        }
    }
}

}
