node('master') {
  echo 'Hello World.......'
  try {
    stage 'Checkout & prepare'
    echo "Checkout--------------"
 
    input 'Is the app ok?'

    stage 'Build'
    echo "Build --------------"

  } catch (pipelineException) {
    echo "Failed --------------"

  }
}
