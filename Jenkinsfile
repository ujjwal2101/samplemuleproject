node {
 def buildStage = [Build,Sonar,Packaging,Deploy]
      
      buildStage.each {x -> 
           println "$x"
           stage('$x') {
               echo "sample testing"

}
}
stage('Build')
{
    echo "Testing1"
}
stage('Sonar')
{
    echo "Testing2"
}
stage('Packaging')
{
    echo "Testing3"
}
stage('Deploy')
{
    echo "Testing4"
}
}
