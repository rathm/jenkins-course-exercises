node {
    stage "stage 1"
        echo "#### build ####"
        sh 'python3 mod_add.py'
    stage "stage 2"
        echo "#### test ####"
        sh 'python3 -m test_add.py'
}
