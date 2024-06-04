pipeline{
      //agent { docker {image 'maven:3.6.3' }}
      agent { docker {image 'node:20.4' }}
      stages{
            stage('Build'){
                  steps{
                        //sh 'mvn --version'
                        sh 'node --version'
                        echo "building an application"
                  }
            }
            stage('Test'){
                  steps{
                        echo "Testing an application"
                  }
            }
            stage('Deploy'){
                  steps{
                        echo "Deploying an application"
                  }
            }
            

      }

}
      


