node {
    git 'https://github.com/relateid/demojenkins.git'
    if (!fileExists ('Dockerfile')) {
      echo 'NO Docker file'
    }
    sh 'ls -lart'
    echo '.......................................'
    sh 'docker build   --file .docker/Dockerfile   -t php-docker .'
    // kubernetes.image().withName("demojenkins").build().fromPath(".")
}
