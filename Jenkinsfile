node{
    stage('test'){ 
      echo "Shared Pipeline Test"
      sayHello 'Chander'
    }
    stage('build')
    {
def scriptContent = libraryResource "org/functions.sh"
sh "chmod +x functions.sh"
}
}
