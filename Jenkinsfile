node {
    stage('clone') {
        checkout scm
    }
    stage('test') {
        sh 'test `ls | wc -l` -ge 2'
    }
}