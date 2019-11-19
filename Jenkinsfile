pipeline {
   agent any

   stages {
      stage('Build') {
        steps {
          echo 'Building chat image...'
          echo "Running ${env.BUILD_ID} ${env.BUILD_DISPLAY_NAME} on ${env.NODE_NAME} and JOB ${env.JOB_NAME}"
          sh ‘docker-compose build it‘
        }
   }
}
