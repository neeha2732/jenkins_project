pipeline{
      agent any
      stages{
            stage('Build'){
                  steps{
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

      post{
                  always{
                        echo "i will run always"
                  }
                  success{
                        echo "i will run if you are successful"
                  }
                  failure{
                        echo "i will run if you fail"
                  }
            }
      changed{
            echo "i will changed three to fourth build"
      }

}
