pipeline {
    agent any

    stages {
        stage('Test') {
            steps {
                echo "Hello workd"
            }
        }
    }
    // stage('Update GIT') {
    //     script {
    //         catchError(buildResult: 'SUCCESS', stageResult: 'FAILURE') {
    //             withCredentials([usernamePassword(credentialsId: 'github', passwordVariable: 'GIT_PASSWORD', usernameVariable: 'GIT_USERNAME')]) {
    //                 sh "git config user.email rwim@naver.com"
    //                 sh "git config user.name realworldismine"

    //                 sh "cat deployment-user.yaml"
    //                 sh "sed -i 's+onikaze/sample-app-docker-notifiuseration/test.*+onikaze/sample-app-docker-user:${DOCKERTAG}+g' deployment-user.yaml"
    //                 sh "cat deployment-user.yaml"

    //                 sh "cat deployment-post.yaml"
    //                 sh "sed -i 's+onikaze/sample-app-docker-post/test.*+onikaze/sample-app-docker-post:${DOCKERTAG}+g' deployment-post.yaml"
    //                 sh "cat deployment-post.yaml"

    //                 sh "cat deployment-notification.yaml"
    //                 sh "sed -i 's+onikaze/sample-app-docker-notification/test.*+onikaze/sample-app-docker-notification:${DOCKERTAG}+g' deployment-notification.yaml"
    //                 sh "cat deployment-notification.yaml"

    //                 sh "git add ."
    //                 sh "git commit -m 'Done by Jenkins Job changemanifest: ${env.BUILD_NUMBER}'"
    //                 sh "git push https://${GIT_USERNAME}:${GIT_PASSWORD}@github.com/${GIT_USERNAME}/sample-app-k8s-manifest.git HEAD:main"
    //             }
    //         }
    //     }
    // }
}