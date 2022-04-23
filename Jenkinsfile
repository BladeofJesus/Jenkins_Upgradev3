pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is BladeOfJesus doing pipeline levelup!!!! '
                        echo 'We are Starting the Testing'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area Area here can be QA , DEV ,UAT"
                  }
            }
            
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area"
                  }
            }
            
      }
}
