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
                sh  "docker run --name myapache -d -p 42000:80 22050108_webimage:1.0"
                echo "S2_22050108 : Web Server Creation Completed"
            }
        }
        
       

    }   
}
