pipeline{
    agent any
    parameters {
  choice choices: ['dev', 'main', 'stage'], description: 'choose branch name', name: 'branch'
        }
    stages{
        stage("demo"){
            steps{
                echo "this is demo"
            }
        }
         stage("demo1"){
            steps{
                echo "this is demo1"
            }
        }
    }
}
