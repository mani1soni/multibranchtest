pipeline{
    stages{
        stage("master"){
            steps{
                sh "python3 add.py"
            }
        }
        stage("manish"){
            steps{
                sh "python3 sub.py"
            }
        }
    }
}