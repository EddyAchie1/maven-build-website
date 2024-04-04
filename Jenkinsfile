pipeline {
    agent any

    tools {
        maven "maven3.9.6"
    }

    stages {
        stage ("Git clone") {
            steps{
                git 'https://github.com/EddyAchie1/maven-build-website.git'
            }
        }

    }
}
