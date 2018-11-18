node {
    try {
        wrap([$class: 'AnsiColorBuildWrapper', colorMapName: 'xterm']) {
            wrap([$class: 'TimestamperBuildWrapper']) {
              echo "And we're running!"
            }
        }
    } catch (def e) {
        echo e.printStackTrace()
        error e.message
    }
}
