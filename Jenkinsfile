node{
   stage('SCM Checkout'){
      def mvnHOME = tool name: '', type: 'maven'

   git 'https://github.com/madhukishore123/my-app/'
   }
   stage('Compile-package'){
      def mvnHOME = tool name: '', type: 'maven'
      sh "${mvnHOME}/bin mvn package"
   }
}
