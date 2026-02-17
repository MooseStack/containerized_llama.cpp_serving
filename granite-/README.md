1. Serve model on CPU:
     - `podman build -t llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest -f gpt-oss-20b-gguf/cpu-x86-64.Containerfile`
     - `podman run -it -p 8080:8080 localhost/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest`
  
2. Push to Dockerhub #TODO - setup CI/CD for this
     - `podman tag localhost/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest`
     - `podman push docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest`
     - `podman tag localhost/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:latest docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:server-b6265`
     - `podman push docker.io/moosestack/llama-cpp_gpt-oss-20b-gguf_cpu-x86-64:server-b6265`