node {
  stage ('checkout') {
    git branch:'main',url:'https://github.com/Nagarjunareddy55/devops1.git'
  }
  stage ('build') {
    sh 'sudo apt-get update'
    sh 'sudo apt install default-jdk -y'
    sh 'sudo apt install maven -y'
    sh 'mvn clean package'
    }
}
