## Trabalhando com arquivos na Área de preparação(stage area)

**1 Visualizando a última alteração feita**
```bash
git diff // no diretório de trabalho (compara Work Directory com Staging Area)

git diff --staged // na staged area (compara Staging Area com .Git Directory)

git diff nome-arquivo.extensao // Visualiza alterações específicas de um commit

git diff --name-only // Visualiza o nome dos arquivos alterados 

git diff -w // Visualiza alterações ignorando espaços

git show hash-commit // Visuliza todas as modificações feitas no respectivo commit
```

**2 Revertendo alterações feitas em arquivos** (Arquivos que estão na área de trabalho)
```bash
git checkout -- nome-do-arquivo.extensao
```

**3 Removendo aquivos da stage area**
```bash
git reset HEAD nome-do-aquivo.extensao
```