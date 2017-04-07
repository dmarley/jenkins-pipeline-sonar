node('maven') {

   stage('checkout navUnit')
   git url: 'https://github.com/dmarley/navUnit.git'

   stage('hello world')
   echo 'Hello World' 

   stage('list pwd')
   sh 'pwd'

   stage('execute navUnit')
   sh './gradlew phantomJsTest'


}
