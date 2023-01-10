node{
   stage('SCM Checkout'){
     git 'https://github.com/Ajayab05/demo-counter-app.git'
   }
   stage('unit testing'){
     sh  'maven test'
   }
}
