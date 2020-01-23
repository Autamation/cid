node{
 stage('SCM Checkout'){
git 'https://github.com/Autamation/cid.git'
}
stage('Compile-Package'){
   def mvnHome = tool name: 'M2_HOME', type: 'maven'
      bat "${mvnHome}/bin/mvn package"
 bat 'mvn package'
}
}
