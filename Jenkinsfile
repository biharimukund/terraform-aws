#!/usr/bin/env groovy

pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                 sh 'cd basic_webserver'
                 sh 'make all'
            }    
        }
    }
}

