pipleline {
  tools {
   maven 'Maven'
  }
  agent any
  stages {
    stage ('Initlialize') {
      steps {
        sh ***
              echo "PATH = ${PATH}"
              echo "M2_HOME = ${M2_HOME}"
        ***
      }
    } 
    stage ('Bulid'){
      sh 'mvn clean package'
    }  
  }
}

  
