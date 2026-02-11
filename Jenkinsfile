pipeline { 
  agent any 
  stages {
    stage ('version') {
       steps {
         bat '"C:\\Users\\ADMIN\\AppData\\Local\\Programs\\Python\\Python312\\python.exe /c python --version'
       }
    } 
    stage ('Hello') {
      steps {
        bat '"\\Windows\\System32\\cmd.exe" /c python example.py'
      }
    }
  }
}
