node {
    stage("Build") {
      sh 'git version'
      sh 'git clone https://github.com/devops-bh/morestoragetest.git'
      sh 'cd morestoragetest'
      sh 'git branch'
      sh 'git pull'
      sh 'chmod 777 test.sh'
      sh './test.sh'
    } 
}
