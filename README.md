## 📘 Comandos Git e Linux mais usados

### 🧠 Comandos Git

| Comando                         | Significado                                                                 |
|--------------------------------|------------------------------------------------------------------------------|
| `git init`                     | Inicializa um novo repositório Git local                                    |
| `git clone <url>`              | Clona um repositório remoto para sua máquina local                          |
| `git status`                   | Mostra o status atual dos arquivos no repositório                           |
| `git add <arquivo>`            | Adiciona o(s) arquivo(s) ao staging (preparar para commit)                  |
| `git commit -m "mensagem"`     | Salva as alterações com uma mensagem descritiva                             |
| `git push origin <branch>`     | Envia os commits locais para o repositório remoto                           |
| `git pull`                     | Baixa as atualizações do repositório remoto e aplica no local               |
| `git log`                      | Mostra o histórico de commits                                               |
| `git branch`                   | Lista as branches (ramificações) existentes                                 |
| `git checkout <branch>`        | Muda para outra branch                                                      |
| `git merge <branch>`           | Mescla uma branch com a atual                                               |
| `git remote -v`                | Mostra os repositórios remotos vinculados                                   |
| `git reset --hard HEAD~1`      | Remove o último commit (⚠️ irreversível)                                    |
| `git config --global user.name "Seu Nome"`  | Configura seu nome global no Git                            |
| `git config --global user.email "seu@email.com"` | Configura seu e-mail global no Git                 |

---

### 🐧 Comandos Linux

| Comando              | Significado                                                       |
|---------------------|-------------------------------------------------------------------|
| `ls`                | Lista os arquivos e pastas do diretório atual                     |
| `ls -l` | Mostra os arquivos e pastas com detalhes como tamanho, dono e permissões      |
| `ls -a` | Mostra todos os arquivos, até os ocultos (que começam com ponto)              |
| `cd <pasta>`        | Acessa a pasta indicada                                           |
| `pwd`               | Mostra o caminho completo do diretório atual                      |
| `mkdir <pasta>`     | Cria uma nova pasta                                               |
| `touch <arquivo>`   | Cria um novo arquivo vazio                                        |
| `rm <arquivo>`      | Remove um arquivo                                                 |
| `rm -r <pasta>`     | Remove uma pasta e todo o seu conteúdo                            |
| `cp <origem> <dest>`| Copia arquivos ou pastas                                          |
| `mv <origem> <dest>`| Move arquivos/pastas ou renomeia                                  |
| `cat <arquivo>`     | Mostra o conteúdo do arquivo                                      |
| `clear`             | Limpa a tela do terminal                                          |
| `sudo`              | Executa comandos como administrador                               |
| `chmod +x <arquivo>`| Torna um arquivo executável                                       |
| `mkdir outono inverno verao` | Cria várias pastas de uma vez só, sem precisar digitar um por um |
| `cat cobol.txt` | Mostra o conteúdo do arquivo "cobol.txt" |
| `nano cobol.txt` | Abre o editor de texto "nano" para editar o arquivo "cobol.txt" |
| `cp cobol.txt inverno.txt` | Copia o arquivo "cobol.txt" e cria uma cópia chamada "inverno.txt" |
| `cp cobol.txt java.txt verao/` | Copia os arquivos "cobol.txt" e "java.txt" para a pasta "verao" |
| `cp -r verao/ outono/` | Copia a pasta "verao" (com tudo dentro) para dentro da pasta "outono" |
| `Ctrl + C` | Interrompe o comando em execução no terminal |

---

### 🧠 Padrões de Commits com Emojis (Convencional e Visual)

<table>
  <tr>
    <td>

<!-- COLUNA 1 -->

| Tipo do Commit              | Emoji                       | Palavra-chave  |
|----------------------------|-----------------------------|----------------|
| Commit inicial             | 🎉 `:tada:`                 | init           |
| Novo recurso               | ✨ `:sparkles:`             | feat           |
| Bugfix                     | 🐛 `:bug:`                  | fix            |
| Refatoração                | ♻️ `:recycle:`              | refactor       |
| Estilização de interface   | 💄 `:lipstick:`             | feat           |
| Comentários                | 💡 `:bulb:`                 | docs           |
| Documentação               | 📚 `:books:`                | docs           |
| Texto                      | 📝 `:pencil:`               | docs           |
| Limpeza de Código          | 🧹 `:broom:`                | cleanup        |
| Removendo um arquivo       | 🗑️ `:wastebasket:`          | remove         |
| Testes                     | 🧪 `:test_tube:`            | test           |

</td>
<td>

<!-- COLUNA 2 -->

| Tipo do Commit              | Emoji                       | Palavra-chave  |
|----------------------------|-----------------------------|----------------|
| Adicionando um teste       | ✅ `:white_check_mark:`     | test           |
| Teste de aprovação         | ✔️ `:heavy_check_mark:`     | test           |
| Performance                | ⚡ `:zap:`                   | perf           |
| Configuração               | 🔧 `:wrench:`               | chore          |
| Mover/Renomear             | 🚚 `:truck:`                | chore          |
| Adicionando dependência    | ➕ `:heavy_plus_sign:`      | build          |
| Removendo dependência      | ➖ `:heavy_minus_sign:`     | build          |
| Package.json em JS         | 📦 `:package:`              | build          |
| Atualizando submódulo      | ⬆️ `:arrow_up:`            | build          |
| Infraestrutura             | 🧱 `:bricks:`               | ci             |
| Deploy                     | 🚀 `:rocket:`               | chore          |

</td>
  </tr>
</table>

### 💻 Exemplos

| Comando Git                                                                 | Resultado no GitHub                                                                 |
|-----------------------------------------------------------------------------|--------------------------------------------------------------------------------------|
| `git commit -m ":tada: Commit inicial"`                                     | 🎉 Commit inicial                                                                   |
| `git commit -m ":books: docs: Atualização do README"`                      | 📚 docs: Atualização do README                                                      |
| `git commit -m ":bug: fix: Loop infinito na linha 50"`                     | 🐛 fix: Loop infinito na linha 50                                                   |
| `git commit -m ":sparkles: feat: Página de login"`                         | ✨ feat: Página de login                                                             |
| `git commit -m ":bricks: ci: Modificação no Dockerfile"`                   | 🧱 ci: Modificação no Dockerfile                                                    |
| `git commit -m ":recycle: refactor: Passando para arrow functions"`        | ♻️ refactor: Passando para arrow functions                                          |
| `git commit -m ":zap: perf: Melhoria no tempo de resposta"`                | ⚡ perf: Melhoria no tempo de resposta                                               |
| `git commit -m ":boom: fix: Revertendo mudanças ineficientes"`            | 💥 fix: Revertendo mudanças ineficientes                                            |
| `git commit -m ":lipstick: feat: Estilização CSS do formulário"`           | 💄 feat: Estilização CSS do formulário                                              |
| `git commit -m ":test_tube: test: Criando novo teste"`                     | 🧪 test: Criando novo teste                                                         |
| `git commit -m ":bulb: docs: Comentários sobre a função LoremIpsum( )"`    | 💡 docs: Comentários sobre a função LoremIpsum( )                                   |
| `git commit -m ":card_file_box: raw: RAW Data do ano aaaa"`                | 🗃️ raw: RAW Data do ano aaaa                                                        |
| `git commit -m ":broom: cleanup: Eliminando blocos comentados..."`         | 🧹 cleanup: Eliminando blocos comentados e variáveis não utilizadas                 |
| `git commit -m ":wastebasket: remove: Removendo arquivos não utilizados"`  | 🗑️ remove: Removendo arquivos não utilizados do projeto                             |

