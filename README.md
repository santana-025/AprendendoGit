Aprendendo o git

Principais comandos 

Abrir o Terminal no VSCode : Ctrl + ' (Aspas Simples)

git init : 
	Inicia um novo repositorio git local na pasta atual


git status : 
	Verifica o stts atual do repositorio, incluindo arquivos modificadoa e arquivos na area de stage


git add "Nome do arquivo" : 
	deixa o arquivo pronto para ser comitado 


git add . : 
	Adiciona Tudo


git commit -m "Descrição da mudança" = 
	Grava as alteraçãoes feitas na area de trabalho como uma nova versão

git Log = 
	Ver o Historico de commites


HEAD -> = Seletor mostrando onde estamos no versionamento do codigo

master / main = A Versão principal do versionamento


git checkout master = Ir para a versão principal

git checkout (id do commit) = ir para o commit especifico

git checkout -b nome = Cria uma ramificação ou uma branch

git branch = lista/motra em qual ramificação voce esta
 
 * no codigo acima mostra onde voçê está

	  master
	* somar

git merge + (nome da branch) : estando na main ou master, junta a ramificação selecionado com a main/master

git remote add origin https://github.com/santana-025/AprendendoGit.git : 
Comando para adicionar um repositorio remoto (Git Hub)

git branch -M main = Renomeia a master para main 

git push -u origin main 

git push
Trazer para maquina 



        Do Github (repositorio Remoto > Repositorio Local) Para Pc

> Escolhe o lugar onde vai colocar o repositorio
> Abra o terminal do windows 

comando 1: cd G:\Meu Drive\Repos
    cd = mostra o caminho da pasta

comando 2 : git clone "Url do botão botão code no github" 
    Clona o repositorio remoto para o local 

comando 3 :cd Repos
    está na pagina do Repositorio 

comnando 4 :code . 
    Abre no Vscode



