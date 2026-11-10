# Kind CREATE CLUSTER

### Sumário
- [Descrição](#descrição)
- [Sintaxe](#sintaxe)
- [Opções](#opções)
- [Exemplos](#exemplos)

---

### Descrição

O **kind create cluster** cria um cluster Kubernetes local usando "nodes" de containeres Docker.

---

### Sintaxe

kind **create cluster** [OPTIONS]

---

### Opções

As opções podem ser vistas por meio dos comandos `kind create --help` e `kind create cluster --help` sendo elas:

- **--config** -> Aponta o caminho do arquivo de configuração do kind.
- **-n**, **--name** -> Atribuiu o nome ao cluster, substitui KIND_CLUSTER_NAME, configuração (default).

---

### Exemplos

Ex:
```bash
kind create cluster --name nome_cluster
```

Ex2:
```bash
kind create cluster --name nome_cluster --config nome_arquivo.yaml
kind create cluster --name mycluster --config cluster.yaml
```

---
