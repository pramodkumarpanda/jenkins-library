#!/usr/bin/env groovy
library 'mylib@master'
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
