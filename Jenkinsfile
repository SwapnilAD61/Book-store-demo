pipeline {  
    agent any  
        stages {  
       	    stage("git_checkout") {  
           	    steps {  
                    git credentialsId: 'github', url: 'https://github.com/Sakshu7/Online_Book_Store.git'
              	    }  
         	    } 
            stage("Build") {  
           	    steps {
                    sh "mvn clean package"
              	    } 
        }
}
