pipeline{
  agent any
  options {}
  stages {
    stage('run on main'){
      when {
        branch "main"
      }
      steps {
        echo "hello main"
      }
    }
    stage("run on new feature branch"){
      when {
        branch "new-feature"
      }
      steps {
        echo "This is new feature"
      }
    }
  }
  
}
