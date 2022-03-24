pipeline {
    
agent { node { label 'master' } } 
parameters{
        string(name:'Filename', defaultvalue:'', description:' Pls supply filename')
}

stages {
   stage('Read demo file') {
            steps {
                sh "cat ${params.FileName}"
            }
        }
    stage('Read Readme.md file') {
            steps {
                sh 'cat README.md'
            }
        }
    stage('Read from choice') {
            steps {
                sh "cat ${params.FileList}.txt"
            }
}
}

}

