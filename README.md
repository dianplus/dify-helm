# Dify Helm Chart

[![Github All Releases](https://img.shields.io/github/downloads/maskshell/dify-helm/total.svg)](https://github.com/maskshell/dify-helm/releases)

Deploy [langgenius/dify](https://github.com/langgenius/dify), an LLM-based chatbot app on Kubernetes with Helm chart.

## Installation

```shell
helm repo add dify https://maskshell.github.io/dify-helm
helm repo update
helm install my-release dify/dify
```

## Supported Components

### Components that could be deployed on Kubernetes in the current version

- [x] core (`api`, `worker`, `sandbox`)
- [x] ssrf_proxy
- [x] proxy (via built-in `nginx` or `ingress`)
- [x] redis
- [x] postgresql
- [x] persistent storage
- [ ] object storage
- [x] weaviate
- [ ] qdrant
- [ ] milvus

### External components that can be used by this app with proper configuration

- [x] redis
- [x] postgresql
- [x] object storage
- [x] weaviate
- [x] qdrant
- [x] milvus
- [x] pgvector
- [x] Tencent Vector DB

## Contributors

[![Contributors](https://contrib.rocks/image?repo=maskshell/dify-helm)](https://github.com/maskshell/dify-helm/graphs/contributors)
