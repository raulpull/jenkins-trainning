pipeline {
   agent any
   parameters {
       string(name: 'Name', defaultValue: 'Super World', description: 'Who you want to say hello?')
   }
   stages {
      stage('Hello') {
         steps {
            echo "Hi ${params.Name}"
         }
      }
      stage('Bye') {
         steps {
            echo "See you ${params.Name}"
         }
      }
   }
}
