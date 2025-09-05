Serve various models using [llama.cpp](https://github.com/ggml-org/llama.cpp)

# Model Serving

1. [gpt-oss-20b-gguf](https://huggingface.co/ggml-org/gpt-oss-20b-GGUF) on an x86-64 CPU
   - Dockerhub Image: `docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest`
   - Docker / Podman run: `podman run -it -p 8080:8080 docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest`
