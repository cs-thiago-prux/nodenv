node() {

git credentialsId: '770fc63e-e91e-4c58-b81b-5b5e035afe70', url: 'https://github.com/cs-thiago-prux/nodenv.git'



stage('old') {
tool name: '0-12-17', type: 'jenkins.plugins.nodejs.tools.NodeJSInstallation'

sh 'node app.js'


}


stage('new') {
tool name: '7-1-0', type: 'jenkins.plugins.nodejs.tools.NodeJSInstallation'

sh 'node app.js'


}







}

