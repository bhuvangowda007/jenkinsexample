pipeline {
 
agent any
 environment{ 
    PATH = "/usr/local/bin: C:/Program Files/Git/bin;C:/Program Files/Docker/Docker/resources/bin;${env.PATH}"
    
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

