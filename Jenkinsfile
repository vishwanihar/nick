properties([[$class: 'GithubProjectProperty', displayName: '', projectUrlStr: 'https://github.com/vishwanihar/nick.git/'], gitLabConnection(''), pipelineTriggers([githubPush()])
pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'pwd' 
                sh 'cat'
            }
        }
        stage('Test'){
            steps {
                sh 'java -version'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls'
                sh 'pwd'
            }
        }
    }
}
