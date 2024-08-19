pipeline {
    agent any

    stages {
        stage('Create Folder') {
            steps {
                script {
                    // Define the folder path
                    def folderPath = "C:/Users/sheen/OneDrive/Desktop/handson-assesment-Shivansh070"

                    // Create the folder if it doesn't exist
                    if (!fileExists(folderPath)) {
                        sh "mkdir -p ${folderPath}"
                        echo "Folder created at ${folderPath}"
                    } else {
                        echo "Folder already exists at ${folderPath}"
                    }
                }
            }
        }
    }
}
