node {
    git 'https://github.com/relateid/demojenkins.git'
    if (!fileExists ('Dockerfile')) {
      echo 'NO Docker file'
    }
    sh 'ls -lart'
    echo '.......................................'
    
    # kubernetes.image().withName("demojenkins").build().fromPath(".")
}
