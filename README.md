# fraud-mlops
# Dificuldades sentidas: 
# “During deployment, the training job initially failed due to an architecture mismatch between local Apple Silicon   (ARM64) Docker builds and SageMaker’s x86_64 runtime. The issue was resolved by enforcing linux/amd64 images using Docker Buildx, ensuring full compatibility with SageMaker Training Jobs.”

