pipeline {  
    agent any  
        stages {  
       	    stage('pullcheckout') {  
           	    steps {  
                    git credentialsId: 'github', url: 'https://github.com/Sakshu7/Online_Book_Store.git'
              	    }  
         	    } 
            stage('build') {  
           	    steps {
                    sh "mvn clean package"
              	    } 
            }
        }
}
