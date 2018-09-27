node{
    stage('test'){ 
      echo "Shared Pipeline Test"
      sayHello 'Chander'
    }
    stage('build')
    {
def functions = libraryResource "org/functions.sh"
writeFile file: 'functions.sh', text: functions

echo "bye"

}
}
