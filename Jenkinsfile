pipeline {
    agent any

    stages {
        
        stage ('Testing Stage') {

            steps {
                
                    sh 'mvn test'
                }
            
        }


        stage ('Install Stage') {
            steps {
                
                    sh 'mvn install'
                }
            
        }
        
        stage ('Echo Branch') {

            steps {
                
                    echo "This is QA branch"
                }
            
        }
    }
}
