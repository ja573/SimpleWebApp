node {
   stage('Preparation') {
      git 'https://github.com/ja573/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
   stage('Deploy') {
      sh "git push https://git.heroku.com/gentle-savannah-28192.git master"
   }
}
