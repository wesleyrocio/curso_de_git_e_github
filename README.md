17/10/2021 - Aprendendo a usar GIT log 001
13/08/2024 - Uma Nova Modificação
2. Renomear o arquivo dentro do Git (se ele já existir, mas não estiver sendo rastreado):

Adicione o arquivo ao stage: git add README.TXT
Renomeie o arquivo: git mv README.TXT README.md
Faça o commit: git commit -m "Renomeando README.TXT para README.md"
3. Remover o arquivo do .gitignore (se ele estiver sendo ignorado):

Edite o arquivo .gitignore: Abra o arquivo .gitignore em um editor de texto e remova a linha que menciona README.TXT.
Adicione o arquivo ao stage: git add README.TXT
Importante:

Após modificar o .gitignore: Rode git clean -f para remover quaisquer arquivos não rastreados que correspondam aos padrões de ignorância antes de fazer um commit.
Em resumo: