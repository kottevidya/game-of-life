node {
   stage('SCM') {
         git 'https://github.com/kottevidya/game-of-life.git'
   }
   
   stage ('build the packages') {

    

          sh 'mvn package'
   }

   
   
   stage ('archival') {



         archive 'gameoflife-web/target/*.xml'
   }
