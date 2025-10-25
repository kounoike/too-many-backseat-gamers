# TODO: fix tag
FROM ollama/ollama:latest
ARG MODEL=qwen3:8b
ENV MODEL=${MODEL}

RUN ollama serve & sleep 2 && ollama pull ${MODEL}
