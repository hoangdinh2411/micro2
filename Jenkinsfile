pipeline{
  agent any
  stages {
    stage('run on main'){
      when {
        branch "main"
      }
      steps {
        echo "hello main jenkins file 1"
      }
    }
    stage("run on new feature branch"){
      when {
        branch "new-feature"
      }
      steps {
        echo "This is new feature on jenkins file 1"
      }
    }
  }
  
}
