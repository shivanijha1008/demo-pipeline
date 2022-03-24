pipeline {
    agent {node{label 'master'}}

    stages{
        stage{'Read demo file'}{
            steps{
                sh 'cat demo.txt'
            }
        }
        
        stage{'Read README.md file'}
        steps{
            sh 'cat README.md'
        }
    }
}
