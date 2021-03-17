node {
  stages {
    stage("build") {
      steps {
        echo "************* build ************"
        sh 'python3 mod_add.py'
      }
    stage("test")
      steps {
        echo "#### test ####"
        sh 'python3 -m test_add.py'
      }
    } 
  }
}
