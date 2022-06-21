pipeline{
  agent none

stages {
    stage('Unit Tests') {
      agent {
        label 'apache'
      }
      steps {
	   sh 'ant -version'     
        
      }
    }
	}
}
