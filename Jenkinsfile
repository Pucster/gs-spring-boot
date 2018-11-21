node {
    try {
        wrap([$class: 'AnsiColorBuildWrapper', colorMapName: 'xterm']) {
            wrap([$class: 'TimestamperBuildWrapper']) {
              stage('FRIGHT') {
                echo "And we're running!"
                echo "Testing webhook"
                echo "NO CSRF!!!!"
                sh('env')
                echo "${env.JENKINS_TYPE}"
                // // echo "Also, anonymous overall read rights and other rights!"
              }
            }
        }
    } catch (def e) {
        echo e.printStackTrace()
        error e.message
    }
}
