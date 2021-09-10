pipeline {
    agent any

    stages {
        stage('Paket Yükleme') { 
            steps {
                sh 'dotnet restore' 
            }
        }

        stage('Derleme') { 
            steps {
                sh 'dotnet build --configuration Release' 
            }
        }
    }
}
Continue butonuna basarak sıradaki adıma geçebilirsiniz.
