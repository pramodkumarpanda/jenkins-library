#!/usr/bin/env groovy
library identifier: 'mylib@master'
pipeline {
    agent none
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
