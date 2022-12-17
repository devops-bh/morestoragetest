node {
    stage("Build") {
      sh 'git version'
      echo pwd
      sh 'rm -r --force morestoragetest'
      sh 'git clone https://github.com/devops-bh/morestoragetest.git'
      sh 'ls morestoragetest'
      sh 'cd morestoragetest && git branch'
      echo pwd
      sh 'chmod 777 morestoragetest/test.sh'
      sh 'morestoragetest/test.sh'
    } 
}
