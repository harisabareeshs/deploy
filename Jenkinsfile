node('e2enode'){
    stage('Cloning Git') {
        checkout scm
    }
        
    
        stage ('Depoly') {
            nodejs('nodejs') {
        sh 'npm start &'
                echo "deployed"
    }
       
        }
}
