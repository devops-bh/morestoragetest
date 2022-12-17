node {
    stage("Build") {
      sh 'git version'
      sh 'git pull'
      sh 'chmod 777 test.sh'
      sh './test.sh'
    } 
}
