node{
    stage('test'){ 
      echo "Shared Pipeline Test"
      sayHello 'Chander'
    }
    stage('build')
    {
def scriptContent = libraryResource "org/${scriptName}"
writeFile file: "${scriptName}", text: scriptContent
sh "chmod +x ${scriptName}"
}
}
