node {
  stage ('checkout') {
    git branch:'main',url:'https://github.com/Nagarjunareddy55/devops1.git'
  }
  stage ('build') {
    sh '''apt update'''
    sh '''apt install default-jdk -y'''
    sh '''apt install maven -y'''
    sh '''mvn clean package'''
    }
}
