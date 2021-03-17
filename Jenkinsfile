node {
    stage "checkout"
        echo "### checkout ####"
        checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/rathm/jenkins-course-exercise-1.git']]])
    stage "build"
        echo "#### build ####"
        sh 'python3 mod_add.py'
    stage "test"
        echo "#### test ####"
        sh 'python3 -m test_add.py'
}
