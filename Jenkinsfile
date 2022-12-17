node {
    stage("Build") {
      sh 'git version'
      sh 'rm -r --force morestoragetest'
      sh 'git clone https://github.com/devops-bh/morestoragetest.git'
      sh 'cd morestoragetest && git branch'
      sh 'chmod 777 test.sh'
      sh './test.sh'
    } 
}
