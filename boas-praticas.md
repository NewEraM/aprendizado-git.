# Inicializar um novo repositório Git
git init

# Adicionar arquivos ao índice
git add .

# Criar um commit com uma mensagem descritiva
git commit -m "Iniciar projeto com estrutura básica"

# Criar uma nova branch para uma funcionalidade
git checkout -b nova-funcionalidade

# Mesclar a branch de funcionalidade na branch principal
git checkout main
git merge nova-funcionalidade
    
# Use git add . para adicionar todos os arquivos modificados ao staging.
# Execute git commit -m "mensagem" para criar o commit.

# Configure o repositório remoto com git remote add origin URL.
# Use git pull origin branch para puxar mudanças do repositório remoto.


# Abra os arquivos com conflitos e edite manualmente para resolver os conflitos.
# Use git add arquivo para marcar os conflitos como resolvidos.
# Faça um commit para concluir o merge.

# Adicione arquivos sensíveis ao arquivo .gitignore para evitar que sejam adicionados ao repositório.
# Remova arquivos sensíveis já adicionados com git rm --cached arquivo. 
# Faça um commit para aplicar as mudanças.

EXEMPLO .gitignore:

	# Adicionar arquivos sensíveis ao .gitignore
echo "config.json" >> .gitignore
git rm --cached config.json
git commit -m "Remover arquivo sensível"


