# repositorio_do_senac
aula de repositório do senac

Comandos básicos do Git

### Configuração Inicial
- **`git config --global user.name "Seu Nome"`**: Define seu nome de usuário que será associado aos commits.
- **`git config --global user.email "seuemail@example.com"`**: Define seu endereço de e-mail que será associado aos commits.

### Criar um Repositório
- **`git init`**: Inicializa um novo repositório Git no diretório atual.

### Clonar um Repositório
- **`git clone https://github.com/usuario/repo.git`**: Copia um repositório remoto para seu computador, criando uma cópia local.

### Adicionar Mudanças
- **`git add .`**: Adiciona todas as mudanças feitas nos arquivos do diretório atual ao índice para o próximo commit.
- **`git add nome_do_arquivo`**: Adiciona um arquivo específico ao índice.

### Fazer um Commit
- **`git commit -m "Mensagem do commit"`**: Registra as mudanças adicionadas ao índice com uma mensagem descritiva.

### Verificar o Status
- **`git status`**: Exibe o estado atual do repositório, incluindo arquivos modificados, adicionados e não rastreados.

### Ver o Histórico de Commits
- **`git log`**: Mostra um histórico dos commits feitos no repositório, incluindo mensagens e autores.

### Sincronizar com o Repositório Remoto
- **`git pull origin main`**: Puxa (atualiza) as mudanças do repositório remoto para sua branch local.
- **`git push origin main`**: Envia suas mudanças locais para o repositório remoto.

### Criar uma Nova Branch
- **`git branch nome-da-branch`**: Cria uma nova branch para desenvolver novas funcionalidades ou corrigir bugs.

### Mudar para Outra Branch
- **`git checkout nome-da-branch`**: Muda para a branch especificada, permitindo que você trabalhe em outra parte do projeto.

### Mesclar Branches
- **`git merge nome-da-branch`**: Mescla as mudanças da branch especificada na branch atual.

### Remover um Arquivo
- **`git rm nome_do_arquivo`**: Remove um arquivo do diretório e do índice, preparando-o para o próximo commit.

### Reverter Mudanças
- **`git checkout -- nome_do_arquivo`**: Desfaz alterações em um arquivo, retornando à versão mais recente do commit.

Esses comandos ajudam a gerenciar seu código e colaboração em projetos. Se precisar de mais detalhes sobre algum comando específico, é só avisar!