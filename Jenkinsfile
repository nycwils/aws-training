node {
    def app

    stage("Clone repository") {
        checkout scm
    }

    stage("Build image") {
        //this builds the docker image
        //app = docker.build("nyuwilson/wilson:jenkinsdockerpush")
        echo "Hello"
        sh "echo hello from the shell"
    }

    stage("Test image") {

        echo "Hello"
        sh "echo hello2 from the shell2"
       
    }

  

}
