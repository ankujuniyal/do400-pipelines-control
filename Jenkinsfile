node('nodejs') {
stage('Checkkkkkkkkkkkkkkkkkkout') {
git branch: 'main',
url: 'https://github.com/ankujuniyal/do400-pipelines-control'
}
stage('Backend Tests') {
sh 'node ./backend/test.js'
}
stage('Frontend Tests') {
sh 'node ./frontend/test.js'
}
stage('echo') {
echo 'hi'
}
}
