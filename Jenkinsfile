#!/usr/bin/env groovy
@Library('mylib@master') _
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
