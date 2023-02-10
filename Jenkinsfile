pipeline {
     agent {
        node {
            label 'master'
        }
    }
  
    stages {
        
     stage('Stage 1_22050108') {
            steps {
                echo "S1_22050108 : Environment Preparation Completed"
            }
        }
        stage('Stage 2_22050108') {
            steps {
                sh  "docker ps -a"
                echo "S2_22050108 : Web Server Creation Completed"
            }
        }
        
       

    }   
}
