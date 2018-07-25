pipeline {
    agent any 
           stages {
            
            stage('build'){    
                steps{                
                // sh 'ant -f build.xml -v'
                 archiveArtifacts  artifacts: 'src/*.java', fingerprint: true
                
                }
            }
   
   
        }
        
}      

