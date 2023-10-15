pipeline {
    agent {
     node{
         label 'maven'
     }   
    }

    stages {
        stage('clone') {
            steps {
                git branch: 'main', url: 'https://github.com/Fl0key/tweet-trend-new.git'
            }
        }
    }
}