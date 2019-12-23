# Configurações

**Obs1:** (Exemplo Windows) Acesse o menu iniciar, localize o ícone do Git Bash, clique com o direito do mouse e em propriedades altere para o local onde normalmente ficam os seus projetos. Exemplo: D:\xampp\htdocs

**Obs2:** No Git Bash a maioria dos comandos são inicializados com $, no entanto são inseridos automaticamente pela ferramenta. Por este motivo ocultei nos exemplos abaixo.


**1. Locomovendo-se pelas pastas do projeto**
```bash
cd nome-da-pasta

cd .. // Retorna 1 nível

cd - // Retorna para a pasta que estávamos anteriormente
```

**2. Abre o Windows Explorer**
```bash
explorer
```

**3. Abre o Explorer do Windows na pasta que estamos atualmente**
```bash
explorer .
```

**4. Configura nome de usuário**
```bash
git config --global user.name nome-de-usuario
```

**5. Configura email de usuário**
```bash
git config --global user.email email@email.com.br
```

**6. Configura editor padrão**
```bash
git config --global core.editor nome-editor
```

**7. Configura a mergetool (meld)**
```bash
git config --global merge.tool meld
```

**8. Edita configurações globais**
```bash
git config --global -e

// Exemplo editor = atom --wait
```

**9. Armazena senha (https)**
```bash
git config --global credential.helper cache
```

**10. Remove senha armazenada (https)**
```bash
git config --global --unset credential.helper
```

**11. armazena senha temporariamente (https)**
```bash
git config --global credential.helper 'cache --timeout=3600' // (3600 segundos = 1 hora)
```

**12. Remove configuração setada**
```bash
git config --global --unset propriedade
git config --global --unset core.editor // exemplo
git config --global --unset user.email // exemplo
```

**13. Visualiza as configurões de usuário**
```bash
git config -l
```

**14. Visualiza as configurões de usuário**
```bash
git config --list
```

**15. Verifica versão do git bash**
```bash
git --version
```