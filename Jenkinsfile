node {
   stage('Preparation') {
      git 'https://github.com/ja573/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}
