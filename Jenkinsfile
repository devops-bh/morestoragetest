node {
    stage("Build") {
      sh 'git version'
      sh 'git branch'
      sh 'git pull'
      sh 'chmod 777 test.sh'
      sh './test.sh'
    } 
}
