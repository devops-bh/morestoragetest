node {
    stage("Build") {
      sh 'git version'
      echo pwd
      sh 'rm -r --force morestoragetest'
      sh 'git clone https://github.com/devops-bh/morestoragetest.git'
      sh 'ls morestoragetest'
      sh 'cd morestoragetest && git branch'
        // don't be tricked by the "cd <directory>"
        // Jenkins may tempoary CD into that directory but it will not stay in the directory 
        // so will need to do <git-repo-dir-name>/....
      echo pwd
      sh 'chmod 777 morestoragetest/test.sh'
      sh 'morestoragetest/test.sh'
    } 
}
