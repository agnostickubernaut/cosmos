node {    
      def app     
      stage('Clone repository') {               
             
//            checkout scm    
      }     
      stage('Build image') {         
       
            app = docker.build("jagadeesh/demo")    
       }     
      stage('Test image') {           
            app.inside {            
             
             sh 'docker images'        
            }    
        }
}
