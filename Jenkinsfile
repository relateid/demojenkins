node {

    checkout scm

    env.DOCKER_API_VERSION="1.23"
    
    sh "git rev-parse --short HEAD > commit-id"
    
    stage "Build"
    
        sh "docker ps"
}
