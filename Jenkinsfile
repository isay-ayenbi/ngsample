node {
   stages {
      stage('Setup') {
          steps {
             sh 'npm install'
          }
       }
       
       stage('Build') {
          steps {
            sh 'npm run build --prod'
            }
        }
   }
}