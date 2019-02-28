node('maven'){
    stage('Checkout'){
        echo "Cloning the Repo"
        git credentialsId: 'lokeshgithub', url: 'https://github.com/sanquestbatch2/batch2.git'
    }
    
    stage('runningScript'){
        echo "Running the Script"
        sh "sh test.sh"
    }
    
    stage('Final'){
        echo "The job is completed successfully"
    }
}
