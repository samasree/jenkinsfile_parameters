pipeline {
  agent any
  parameters {
    string(name: 'Greeting', defaultValue: 'Hello', description: 'Greeting')
  }
  stages {
    stage('Build') {
      steps {
        echo "${params.Greeting} World!"
      }
    }
  }
}
