node {
 stage('SCM checkout'){
   git 'https://github.com/arihanthreddy/git-real'
 }
 stage('Compile-Package'){
 def mvnHome = tool name: 'M2_HOME', type: 'maven'
 sh "${mvnHome}/bin/mvn package"
 }
}
