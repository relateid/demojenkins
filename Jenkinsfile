node {
    git 'https://github.com/relateid/demojenkins.git'
    if (!fileExists ('Dockerfile')) {
      echo 'NO Docker file'
    }
    sh 'pwd'
    sh 'ls -lart'
    sh 'sudo docker ps'
    echo '.......................................'
    //sh 'docker build   --file .docker/Dockerfile   -t php-docker .'
    // kubernetes.image().withName("demojenkins").build().fromPath(".")
}
