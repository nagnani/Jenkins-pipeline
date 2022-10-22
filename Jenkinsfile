node {

     stage('code clone') {
        git 'https://github.com/nagnani/Jenkins-pipeline.git'
    } 
    
      stage('code clean') {
         sh 'mvn clean'
    }

      stage('mvn validate') {
         sh 'mvn validate'
    }

      stage('mvn compile') {
         sh 'mvn compile'
    } 
 
         stage('mvn test') {
         sh 'mvn test'
    } 
 
         stage('mvn package') {
          sh 'mvn package'
    }  
}    

