pipeline {

    agent any

    environment {
        def BUILDVERSION = sh(script: "echo `date +%s`", returnStdout: true).trim()
    }

    stages {
        stage("Awesome Stage") {
            steps {
                echo "Current build version is :: $BUILDVERSION"
            }
        }
    }
}
