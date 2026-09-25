Jenkinsfile (Scripted Pipeline)
node {  
    stage('Build') { 
         
	echo "checking java version"
        sh 'java --version'
    }
    stage('Test') { 
        
	echo "jenkin version"
	sh 'jenkins --version'
    }
    stage('Deploy') { 
       
	echo "git version"
	sh 'git --version'
    }
}
