pipeline{
    agent{
        docker{
            image "node"
        }
    }
    stages{
        stage("build"){
            script {
            sh node version
        }
        }
    }
}
