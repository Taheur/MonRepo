node {
    stage('Clone') {
        git 'https://github.com/Taheur/MonRepo.git'
        bat '''
        javac Main.java
        java Main
        '''
    }
    stage('Build') {
        bat '''javac Main.java'''
    }
    stage('Run') {
        bat '''
        java Main
        '''
    }
}
