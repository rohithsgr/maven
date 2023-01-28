Pipeline{
agent any
stages{
stage('Deploy'){
steps{
sh 'mvn install'
}
}
stage('test'){
steps{
sh 'mvn test'
}
}
}
}
