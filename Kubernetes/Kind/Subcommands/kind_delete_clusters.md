# Kind DELETE CLUSTERS

### Sumário
- [Descrição](#descrição)
- [Sintaxe](#sintaxe)
- [Opções](#opções)
- [Exemplos](#exemplos)

---

### Descrição

O **kind delete clusters** deleta um ou mais clusters.

---

### Sintaxe

kind **delete clusters** [OPTIONS]

---

### Opções

As opções podem ser vistas por meio dos comandos `kind delete --help`, `kind delete cluster --help`, `kind delete clusters --help` sendo elas:

- **-A**, **--all** -> Deleta todos os clusters.

---

### Exemplos

Ex:
```bash
kind delete clusters nome_cluster
kind delete clusters mycluster
```

Ex2:
```bash
kind delete clusters -A
```

---
