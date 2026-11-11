# kubectl

### Sumário
- [Descrição](#descrição)
- [Endereços na Web](#endereços-na-web)
- [Instalação](#instalação)

---

### Descrição

O **kubectl** é uma ferramenta de linha de comando fornecida pelo Kubernetes para comunicação com o plano de controle(control plane) de um cluster Kubernetes, utilizando a API do Kubernetes.


---

### Endereços na Web

- [Site Kubernetes: kubectl](https://kubernetes.io/docs/reference/kubectl/)

---

### Instalação

Instalação do kubectl:

```bash
# Baixar a versão mais recente estável do kubectl
curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

# Tornar executável
chmod +x kubectl

# Mover para o PATH
sudo mv kubectl /usr/local/bin/
```

---
