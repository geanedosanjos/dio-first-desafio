Anotações 

**Git** é um sistema de controle de versão, criado por Linus Torvalds, para desenvolver o Kernel do Linux. Com ele você pode fazer e salvar cada alteração em seu projeto e futuramente essas alterações poderão ser consultadas ou revertidas. É como se você criasse um ponto de restauração no seu sistema, só que no Git realmente funciona!



## Importância

- Controle de versão
- Armazenamento em nuvem
- Trabalho em equipe
- Melhorar o seu código
- Reconhecimento



## Comandos

## Ciclo de Vida

- Criando uma pasta

​       $*mkdir projeto*

​       $*cd projeto*

- Iniciar como um repositório GIT

$ *git init*

- Adicionando um arquivo e em seguida verificar status

$ *echo* *"hello word"* >*hello.txt*

$*git status*

- Logo o arquivo será listado como **''Untracked files"**,sendo assim o Git não

não está "trackeando" este arquivo. Para que Git comece a ser responsável 

por esse arquivo,use **git add**

$*git add* *hello.txt*

$*git status*

- Em seguida o arquivo será listado como *"Changes to be committed"*

$*git commit* -*m "Primeiro commit"*

$*git status*

- Após o *commit*,o *git status* dirá (*"nothing to commit, working tree clean"*)
- Pode-se dizer então que o arquivo `hello.txt` está **unmodified** (não há modificações, se comparado com o último *commit*).





## Status

- **TRACKED**: Arquivos que já estão inseridos no repositório

  - **UNMODIFIED**: Não foram modificados por você.
  - **MODIFIED**: Foram modificados por você.
  - **STAGED**:  Os arquivos que acabaram de ser mudados

- **UNTRACKED**: 

  

