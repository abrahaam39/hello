node {
      stage('clone') {
         git 'https://github.com/abrahaam39/hello.git'
      }
      stage('build') {
          sh label:'',script : 'javac Main.java'
      }
      stage('run') {
         sh label:'',script : 'java Main'
         sh label:'',script : 'echo "bravo souna"   
      }
   }       
