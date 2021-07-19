pipeline {
  agente {
    dockeer {
      image "node:8-alpine"
    }
  }
  stages {
    stage("Build") {
      steps {
        sh "npm install"
      }
    }
  }
}
