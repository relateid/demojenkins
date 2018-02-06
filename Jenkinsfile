node {
    git 'https://github.com/relateid/demojenkins.git'
    if (!fileExists ('Dockerfile')) {
      echo 'NO Docker file'
    }
    kubernetes.image().withName("demojenkins").build().fromPath(".docker/Dockerfile")
}
