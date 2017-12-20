#!groovy

podTemplate(cloud: 'jenkins-slave', label: 'mypod') {
    node('mypod') {
        stage('Run shell') {
            sh 'echo hello world'
        }
    }
}
