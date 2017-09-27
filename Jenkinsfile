//Jenkins file to do build
node {
   def mvnHome = tool 'Maven3.2.1'

    stage('Clone sources') {
        git branch: 'master',url: 'https://github.com/vishalraina/aem-project-archetype.git'
    }
}
