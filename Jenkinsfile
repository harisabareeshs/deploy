node('e2enode'){
    stage('Cloning Git') {
        checkout scm
    }
        
    stage('Install dependencies') {
        nodejs('nodejs') {
            sh 'npm install'
            echo "Modules installed"
        }
        
        stage ('Depoly') {
            nodejs('nodejs') {
        sh 'npm start &'
                echo "deployed"
    }
       
