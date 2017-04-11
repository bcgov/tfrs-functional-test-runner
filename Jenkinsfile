node('maven') {
   stage('checkout navUnit')
   git url: 'https://github.com/dmarley/navUnit.git'

   stage('execute navUnit')
   sh './gradlew phantomJsTest'
}
