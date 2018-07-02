node {
   stage('Preparation') {
      git 'https://github.com/jodler303/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
