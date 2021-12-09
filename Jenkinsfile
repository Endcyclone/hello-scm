node {
    stage('ハローワールド') {
        sh 'echo "Hello from Jenkinsfile!!!"'
    }
    stage('gitをクローン') {
        git('https://github.com/Endcyclone/hello-scm.git')
    }
    stage('ファイル確認') {
        sh 'ls -l'
    }
}