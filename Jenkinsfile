node{
    stage('test'){ 
      echo "Shared Pipeline Test"
      sayHello 'Chander'
    }
    stage('build')
    {
def functions = libraryResource "org/functions.bat"
writeFile file: 'functions.bat',
bat "functions.bat"
echo "bye"

}
}
