pipeline {
      agent {
         kubernetes {
              yamlFile 'pod1.yaml'
            }
         }
          stages {
              stage ('Run nginx') {
                 steps {
                       sh 'echo hello > /usr/share/nginx/html/index.html'
                     }
                   }
                }
             }

             
