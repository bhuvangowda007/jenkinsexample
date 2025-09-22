pipeline {
 
agent any
 environment{ 
    PATH = "/usr/local/bin:${env.PATH}"
    
}
stages {
     stage('Clone Repository') {
steps {
 echo "${env.PATH}"
  sh "echo ${env.PATH}"
}
}
}
}

