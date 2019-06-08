# TensorFlow 2.0

Run the following command to start the Jupyter server:

    # TensorFlow 1.x
    docker run -it --rm -v $PWD:/tf/notebooks -p 8888:8888 tensorflow/tensorflow:latest-py3-jupyter
    # TensorFlow 2.x
    docker run -it --rm -v $PWD:/tf/notebooks -p 8888:8888 tensorflow/tensorflow:2.0.0b0-py3-jupyter