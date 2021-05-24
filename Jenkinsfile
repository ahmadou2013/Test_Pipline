node {
    stage('Clone') {
        git 'https://github.com/ahmadou2013/Test_Pipline.git'
    }
    stage('Build') {
        sh 'javac Main.java'
    }
    stage('Run') {
        sh 'java Main'
    }
}
