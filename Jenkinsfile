pipeline {
  agent any
  parameters {
    choice choices: ['main', 'branch1'], description: 'select a branch to build', name: 'branch'}
    stages {
      stage ('Scm checkout') {
        steps {
        echo "pulling changes from the branch ${params.branch}"
      }
}
    }
}
