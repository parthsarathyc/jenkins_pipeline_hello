node {
    stage('build'){
        echo "building"
    }
}

stage('Get approval'){
    input "start testing?"
}
node {
    stage('test'){
        echo "testing"
    }
node {
    stage('test'){
        echo "Pre deployment tests"
    }
}
stage('Get approval'){
    input "Deploy to qa?"
}
node {
    stage('deploy to qa'){
        echo "deploying"
    }

}
