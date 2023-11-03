node {
  stage('SCM Checkout') {
    git 'https://github.com/iriteshnagpal/java-design-patterns'
  }
 stage('Compile-package') {
   def mvnHome = tool name: '', type: 'maven'
   sh "${mvnHome}/bon/mvn package"
 }
}
