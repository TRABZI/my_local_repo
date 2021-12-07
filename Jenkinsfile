node {
    stage('Clone') {
        git 'https://github.com/TRABZI/my_local_repo.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
