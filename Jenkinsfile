node {
    stage('Réunion') 
    {
        git 'https://github.com/priximmo/jenkins-helloworld.git'
    }
    
    stage('Nos Décisions') 
    {
        sh 'javac Main.java'
    }    
    
    stage('Action') 
    {
        sh 'java Main'
    }      
}
