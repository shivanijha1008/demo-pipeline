pipeline {
    
agent { node { label 'master' } } 
parameters{
        string(name:'Filename', defaultvalue:'', description:' Pls supply filename')
}

stages {
   stage('Read demo file') {
            steps {
                sh "cat ${param.FileName}"
            }
        }
    stage('Read Readme.md file') {
            steps {
                sh 'cat README.md'
            }
        }
    
}

}

