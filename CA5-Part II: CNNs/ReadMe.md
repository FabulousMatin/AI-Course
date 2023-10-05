1. Jupyter file is coded for internal GPU processing for Nvidia-supported GPUs and needed Cuda and cuDNN installed.
2. To avoid Memory leaks, you can turn on/off `show_train` in metrics.
3. Ignore keras.sequential.fit warning, due to data is batched outside of keras model, and callback functions are applying on unbatched datas.