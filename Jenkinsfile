pipeline {
         agent any
         stages {
                 stage('Build') {
                 steps {
                     echo 'staring build the app'
                 }
                 }
                 stage('Test') {
                 steps {
                    input('Do you want to proceed?')
                 }
                 }
             
                 stage('Product') {
                     steps {
                                echo "App is Ready"
                              }
                 
              }
}
}
