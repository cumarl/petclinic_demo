#!/usr/bin/env groovy
node {
    wrap([$class: 'AnsiColorBuildWrapper']) {
        stage('HelloWorld') {
            echo 'Hello World'
        }

        stage('git clone') {
            git clone "https://github.com/hamid2013/spring-petclinic.git"
        }
    }
}