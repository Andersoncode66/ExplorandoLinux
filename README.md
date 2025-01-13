# ExplorandoLinux


## 1. Identificando o Diretório Atual
Tarefa:
- Execute o comando para descobrir em qual diretório você está agora.
- Registre o caminho completo mostrado pelo terminal.
### Resposta
pwd



## 2. Listando Arquivos e Diretórios
Tarefa:
- Liste todos os arquivos e diretórios no diretório atual, incluindo os arquivos ocultos.
- Anote a diferença ao usar os comandos ls, ls -a, e ls -l.
### Resposta
ls: Lista todos os arquivios no diretório atual
ls -l: Lista com detalhes como permissões e tamanho
ls -a: Inclui arquivos ocultos (começam com .)
ls -h: Mostra tamanhos em formatos legível.
ls -la: para listar diretórios ocultos
ls ~: Listar o conteúdo do diretóri home: abra o terminal e digite: isso mostrará as pastas no diretório home do seu usuario

## 3. Movendo-se Entre Diretórios
Tarefa:
1. Navegue para o diretório  /etc.
2. Retorne ao seu diretório incial.
3. Acesse novamente o diretório anterior com um único comando.
### Resposta
cd /etc        # Para navegar até /etc
cd             # Para voltar ao diretório inicial
cd -           # Para retornar ao /etc


## 4. Criando Diretórios
Tarefa:
- Crie uma estrutura de diretórios chamada Projetos/linux no seu diretório inicial, onde linux será um subdiretório de projetos.
- Use um único comando para criar toda a estrutura.
### Resposta
mkdir -p ~/projetos/linux

## 5. Explorando Caminhos Relativos e Absolutos
Tarefa:
- Acesse o diretório projetos/linux usando o caminho relativo.
- Acesse o mesmo dirertório, mas agora usando o caminho absoluto.
### Resposta
1. cd ~ Para acessar o diretório home, usando caminho relativo usar o comando cd projetos/linux.
2. cd ~/projetos/linux


## 6. Voltando ao Diretório Anterior
Tarefa:
- Navegue para o diretório /var/log.
- Volte para o diretório anterior sem usar o caminho completo.
### Resposta
1. cd /var/log
2. cd -

## 7. Verificando Permissões
- Listee os arquivos do diretório /var com permissões detalhadas.
- Verifique se existem arquivos ou diretórios com permissões de execução.
### Resposta
1. ls -la /var
2. ls -l /var | grep 'x'

## 8. Localizando Diretórios
Tarefa:
- Use um comando para encontrar o diretório linux que você criou no seu sistema, começando a busca no diretório raiz (/).
### Resposta
1. cd /tmp
2. cd ~

## 9. Trabalhando com Diretório Inicial
Tarefa:
1. Navegue para o diretório /tmp.
2. Volte ao diretório inicial usando o atalho no terminal.
### Resposta
1. cd /tmp
2. cd -

## 10. Acessando Diretórios Específicos
Tarefa:
- Acesse o diretório /var/log/apache2 (ou similar, dependendo da sua configuração) diretamente, partindo do diretório raiz, e liste o conteúdo.
### Resposta
ps: caso de permissão negada, entre com usuário root
ls, ls -la , ls -a ,ls ~.

## 11. Desafios Extras
1. Criando Diretórios:
- Crie um diretório chamado testes, e dentro dele, crie 3 subdiretórios: arquivos, scripts, e logs.
2. Movendo-se por Caminhos Complexos:
- Navegue para o diretórios arquivos, volte ao diretório pai (testes), e então acesse o diretório logs, tudo sem usar caminhos absolutos.
3. Removendo Diretórios Vazios:
- Remova o diretório logs criado anteriormente sem apagar o restante da estrutura.



## 12. Navegando e Manipulando Arquivos e Diretórios
1. Crie uma estrutura de diretórios e subdiretórios:
- Crie o diretório projetos com os subdiretórios frontend e backend.
- Dentro de frontend, crie um arquivo chamado index.html
- Dentro de backend, crie um arquivo chamado server.js.
2. Renomeie arquivos:
- Renomeie o arquivo index.html para home.html
3. Copie e mova arquivos:
- Copie o arquivo home.html para o diretório backend
- Mova o arquivo server.js para o diretório frontend.
4. Apague arquivos e diretórios:
- Delete o arquivo server.js e o diretório backend.

## 13. Permmissões e Usuários
1. Verifique e altere permissões:
- Verifique as permissões do arquivo home.html
- Altere as permissões para que o prorietário tenha leitura e escrita, e outros usuários apenas leitura.
2. Crie um novo usuário:
- Crie um usuário chamado estudante e defina uma senha para ele.
3. Teste permissões com outro usuário:
- Faça login como o usuário estudante e tente acessar o arquivo home.html

## 14. Localização e Filtros
1. Localize arquivos específicos:
- Encontre todos os arquivos .html no diretório atual e seus subdiretórios.
2. Filtre conteúdo de arquivos:
- Crie um arquivo chamado dados.txt com uma lista de nomes.
- Use o comando grep para encontrar todos os nomes que começam com a letra "A".
10. Conte palavras e linhas:
- Conte quantas palavras e linhas existem no arquivo dados.txt

## 15. Comandos de Histórico
1. Explore o histórico de comandos:
- Liste os últimos 10 comandos que você executou.
- Exclua um comando específico do histórico.
2. Reutilize comandos:
- Use o comando history pra repetir o último comando que você executou.

## 16. Administração de Sistema
1. Liste os processos em execução:
- Use o comando ps para listar todos os processos em execução no sistema.
2. Mate um processo específico:
- Identifique o PID de um processo em execução (como o nano) e encerre-o.
3. Monitore o uso de memória:
- Use o comando free -h para verificar a memória usada e livre no sistema.

## 17. Rede
1. Verifique conectividade:
- Use o comando ping para verificar se você consegue alcançar o site www.google.com.
2. Verifique portas abertas:
- Liste todas as portas abertas no sistema usando o comando netstat ou ss.

## 18. Automação e Shell Scripts
1. Escreva um script simples:
- Crie um script chamado boas_vindas.sh que exiba a mensagem "Bem-vindo ao Linux!" quando executado.
- Torne o script executável e execute-o.
2. Automatize a criação de diretórios:
- Escreva um script que crie os diretórios Projeto1, Projeto2 e Projeto3 dentro do diretório atual.

## 19. Tarefas Avançadas
1. Compactação e Descompactação:
- Compacte o diretório projetos em um arquivo chamado projetos.tar.gz.
- Descompacte o arquivo e verifique os conteúdos.
2. Criação de um link simbólico:
- Crie um link simbólico chamado meu_link que aponte para o arquivo home.html.
3. Cron Jobs:
- Agende uma tarefa para criar um arquivo chamado log.txt no diretório /tmp todos os dias ás 10h.
