pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        readYaml(file: 'userspec.yaml', text: 'Cluster:')
      }
    }
  }
  environment {
    test = 'lobe'
  }
}
