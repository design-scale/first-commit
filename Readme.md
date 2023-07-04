# Comandos básicos do Git

Aqui estão alguns comandos básicos do Git e suas descrições:

### git init

```bash
git init
```
Cria um novo subdiretório chamado .git que contem todos os arquivos necessários de seu repositório.

### git push
```bash
git push
```
Este comando é usado para enviar as alterações locais para um repositório remoto. Ele envia os commits feitos na branch local para a branch correspondente no repositório remoto.

### git push origin <nome-da-branch>

```bash
git push -u origin main
```
Envia as alterações locais para um repositório remoto. Ele envia os commits feitos na branch local para a branch correspondente no repositório remoto.

### git clone

```bash
git clone
```
Clona um repositório existente. Ele cria uma cópia local de um repositório remoto, incluindo todos os arquivos, histórico de commits e branches.

### git add

```bash
git add
```

Adiciona arquivos ao índice do Git. Ele prepara os arquivos modificados ou novos para serem incluídos no próximo commit.

### git commit

```bash
git commit -m "Nome do seu Commit"
```
Cria um novo commit, registrando as alterações feitas nos arquivos adicionados ao índice. Cada commit possui uma mensagem que descreve as alterações realizadas.

### git pull

```bash
git pull
```
Obtém as alterações mais recentes de um repositório remoto. Ele combina as alterações do repositório remoto na branch atual, atualizando assim o repositório local.

### git checkout <nome-da-branch>

```bash
git checkout nome_da_branch
```
Este comando é usado para criar uma nova branch ou alternar para uma branch existente. Ele também pode ser usado para descartar alterações não comprometidas em uma branch.

### git checkout -b <nome-da-branch>

```bash
git checkout -b nome-da-branch
```
Isso criará uma nova branch com o nome especificado.

### git branch

```bash
git branch 
```
Lista, criar ou excluir branches. Ele mostra todas as branches existentes no repositório e permite a criação e exclusão de branches.

### git branch -D <nome-da-branch>

```bash
git branch -D nome-da-branch
```
Excluir uma branch específica no Git, incluindo todos os commits e alterações contidos nela

### git merge

```bash
git merge 
```
Mescla as alterações de uma branch em outra. Ele combina as alterações feitas em uma branch específica com a branch atual.

### git fetch

```bash
git fetch 
```
Busca as alterações de um repositório remoto sem mesclá-las com a branch atual. Ele atualiza o repositório local com as informações mais recentes do repositório remoto.












