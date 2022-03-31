pipeline{
agent any
stages 
{
stage('install') 
{
steps{
npm install
}
}
stage('build') 
{
steps{
npm run build
}
}
stage('Build docker image ') 
{
steps{
echo "Build docker image  the Project.........."

}
stage('Deploy') 
{
steps{
echo "Deploying the Project.........."
}
}
}
}