node {         
      stage('Build image') {     
             sh 'ls -a'
             sh 'docker build -t jenkins-demo:${BUILD_NUMBER} . -f Dockerfile'
             sh 'docker tag jenkins-demo:${BUILD_NUMBER} jenkins-demo:latest'
             sh 'docker images'        
            }    
        }
