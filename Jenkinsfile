//Jenkins file to do build
node {
   def mvnHome = tool 'Maven3.2.1'

    stage('Clone sources') {
        git branch: 'master',url: 'git@git.corp.adobe.com:viraina/unified-dev-portal.git'
    }
}
