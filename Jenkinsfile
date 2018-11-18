node {
    try {
        wrap([$class: 'AnsiColorBuildWrapper', colorMapName: 'xterm']) {
            wrap([$class: 'TimestamperBuildWrapper']) {
              stage('FRIGHT') {
                echo "And we're running!"
                echo "Testing webhook"
                echo "NO CSRF!!!!"
              }
            }
        }
    } catch (def e) {
        echo e.printStackTrace()
        error e.message
    }
}
