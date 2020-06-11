#!/usr/bin/env groovy
library 'mylib'
pipeline {
    agent any
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    sh """
                    pwd
                    ls
                    """
                    log.info 'Starting'
                    log.warning 'Nothing to do!'
                }
            }
        }
    }
}
