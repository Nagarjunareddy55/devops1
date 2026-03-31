node {
  stage ('checkout') {
    git branch:'main',url:'https://github.com/Nagarjunareddy55/devops1.git'
  }
  stage ('build') {
    sh 'sudo -i'
    sh 'apt-get update'
    sh 'apt install default-jdk -y'
    sh 'apt install maven -y'
    sh 'mvn clean package'
    }
}
