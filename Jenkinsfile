node {
   stage('SCM') {
      git 'https://github.com/kottevidya/game-of-life.git'
     }
   
   stage ('build the packages') {    
     sh label: 'Vidyasagar', script: 'mvn package'
   }
   stage ('archival') {
   archiveArtifacts 'gameoflife-web/target/*.war'
   }
}
