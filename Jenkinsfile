pipeline {
   agent {
  label 'node3'
}

    stages {
        stage("Git-checkout") {
            steps {
                git credentialsId: '9d1bb485-a713-4a37-8010-0db74bb1e061', url: 'https://github.com/minj1992/spring-boot-war-example.git'
            
            }
        }  
        stage("stage-2") {
            steps {
                echo "mayuri how are you !"
            
            }
        }  
        stage("stage-3") {
            steps {
                echo "mayuri how are you !"
            
            }
        }  
    }
}
