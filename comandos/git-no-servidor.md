## Trabalhando com Git no Servidor

**1. Iniciar versionamento no servidor**
```bash
git init --bare
```
**2. Clonando repositório do servidor**
```bash
git clone file:////nome-servidor/pasta-desenvolvimento/nome-repositorio
```
**3. Consultando nome do remoto (por padrão chama-se origin)**
```bash
git remote
```
**4. Enviando arquivos/modificações para o servidor**
```bash
git push origin <branch>
```
