node {
    stage('clone') {
        git 'https://github.com/TrimedGit/jenkins.git'
    }
    stage('build') {
        git 'https://github.com/TrimedGit/jenkins.git'
        sh 'javac Main.java'
    }
    stage('run') {
        echo "start"
        sh 'java Main'
    }
}
