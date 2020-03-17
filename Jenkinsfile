pipeline {
   agent any
   parameters {
       string(name: 'Name', defaultValue: 'World', description: 'Who you want to say hello?')
   }
   stages {
      stage('Hello') {
         steps {
            echo "Hello ${params.Name}"
         }
      }
      stage('Bye') {
         steps {
            echo "Bye ${params.Name}"
         }
      }
   }
}
