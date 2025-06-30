pipeline {
    agent any

    stages {
        stage('C&R') {
            steps {
                bat '''javac Sample.java
                       java Sample'''
            }
        }
    }
}
