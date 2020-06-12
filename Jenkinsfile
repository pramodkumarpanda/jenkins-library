#!/usr/bin/env groovy
library 'testlib'
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
              
                }
            }
        }
    }
}
