pipeline {
  agent any
  parameters {
    string(name: 'Greeting', defaultvalue: 'Hello', description: 'Greeting')
  }
  stages {
    stage('Build') {
      steps {
        echo "${params.Greeting} World!"
      }
    }
  }
}
