pipeline{
  agent any
    stages {
      stage('One')
        steps {
                Print 'Hello how are you'
                }
                stage('Two')
                {
                  steps
                  {
                    input('do you want to proceed?')
                    }
                    }
                 stage('Three')
                  when  {
                    not {
                          branch "master"
                    }
                    steps
                    {
                      echo "Hello"
                    
                  }
                }
    }
}
