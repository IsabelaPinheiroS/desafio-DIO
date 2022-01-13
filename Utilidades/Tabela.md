# Tabela de Comandos - Git

Existem diversos comandos possíveis de utilização no Git. Abaixo, estão reunidos apenas alguns deles, para fins de exemplificação:
<br>

Comando | Função 
:---------- | :------------------------------
ls | Listar as pastas em um repositório
cd .. | Voltar um diretório
mkdir (nome da pasta) | Cria novos diretórios/pastas
git status | Verifica o status do repositório
git add -A | Inserir tudo
git commit -m "mensagem" | Comitar com uma mensagem
git log | Para verificar informações
git diff | Mostra a modificação (em verde)
git reset --soft (hash do commit) | Retorna do commit, mas o arquivo ainda fica em Staged
git reset --mixed (hash do commit) | Retorna do commit e volta os arquivos para antes do Staged
git reset --hard ((hash do commit) | Ignora a existência do commit e de tudo que foi feito nele
git checkout | Muda a branch atual
git push origin | Para enviar modificações para o repositório remoto
git clone (endereço copiado) | Permite clonar um repositório público para a máquina local


**Obs.:** O git reset altera o histórico do commit

