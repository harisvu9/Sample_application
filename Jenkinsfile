node {
  stage('checkout'){
    checkout scm
  }

  stage('build'){
    sh 'mvn clean install'
  }
  stage('sonar'){
    sh 'mvn sonar:sonar -Dsonar.host.url=http://54.213.82.124:9000 -Dsonar.login=0b6b9825ab4aa440dbd599b899c3df674ec022e2'
  }
  stage('package'){
    sh 'echo "Jenkinsfile"'
  }
  stage('deploy'){
    sh 'echo "Jenkinsfile"'
  }
}
