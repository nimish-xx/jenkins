node('master') {
  echo 'Hello World.......'
  try {
    stage 'Checkout & prepare'
    echo "Checkout--------------"

    stage 'Build'
    echo "Build --------------"

  } catch (pipelineException) {
    echo "Failed --------------"

  }
}
