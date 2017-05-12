node('maven') {
   stage('checkout navUnit')
   git url: 'https://github.com/bcgov/navUnit.git'

   stage('execute navUnit')
   sh './gradlew phantomJsTest'
}
