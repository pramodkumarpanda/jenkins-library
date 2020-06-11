#!/usr/bin/env groovy
library 'mylib@master'
pipeline {
    agent none
    stages {
        stage ('Example') {
            steps {
                // log.info 'Starting' 
                script { 
                    mylib.info 'Starting'
                    mylib.warning 'Nothing to do!'
                }
            }
        }
    }
}
