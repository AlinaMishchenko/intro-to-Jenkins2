pipeline {
 agent { docker { image 'naven:3.3.3' } }
 stages {
  stage( 'build') {
    steps {
     sh 'mvn —version'
    }
  }
}
}
