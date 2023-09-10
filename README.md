# Bug repro for Ollama server go libraries

```shell
% go mod download
...
...


% go build .
../../go/pkg/mod/github.com/jmorganca/ollama@v0.0.18/llm/ggml_llama.go:31:12: pattern llama.cpp/ggml/build/*/bin/*: no matching files found
```
