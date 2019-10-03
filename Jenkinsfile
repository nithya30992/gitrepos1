node{
   stage('SCM Checkout'){
     git 'https://github.com/nithya30992/gitrepos1'
     }
     stage('Compile-Package'){
        // Get maven home path
        def mvnHome = tool name: 'NewMaven-3', type: 'maven'
        sh "${mvnHome}/bin/mvn package"
     }
     
}     
