pipeline {
    
  agent {
    node  {
     label 'master'
      customWorkspace env.BRANCH
    }
  }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "ls"
                sh "echo $branch && pwd"
                sh 'printenv'
                
            }
        }
    }
}
