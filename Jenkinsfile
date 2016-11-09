node('master') {
  echo 'Hello World.......'
  try {
    stage 'Checkout & prepare'
    echo 'Checkout & prepare'
    
    stage 'Build'
    echo "Build --------------"
    echo 'Test case...'
    echo 'Sonar...'

    stage 'Deploy to DEV'
    echo 'Deploy to Dev'

    input 'Is the app ok in DEV?'
    stage 'Deploy to INT'
    echo 'Deploy to INT'

    input 'Is the app ok in INT?'
    stage 'Deploy to QA'
    echo 'Deploy to QA'

  } catch (pipelineException) {
    echo "Failed --------------"

  }
}
