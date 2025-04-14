# git-aula1
<h1>Primeira aula de comandos git do curso Geração Tech</h1>
<h3>Processo usado para a criação e alocação do arquivo nesse repositório</h3>
<h6>Como já tinha usado o git antes, não precisei usar o git config username...</h6>
<ol>
  <li>Criar repositório pelo git hub (localmente)</li>
  <li>Criar uma pasta na área de trabalho contendo um arquivo onde eu ia colocar meu repositório</li>
  <li>No caminho dos meus arquivos, digitei "cmd"</li>
  [git1](https://github.com/user-attachments/assets/6ae4e4f1-327e-4f73-ae16-8c0d0c0f3b0b)
  <li>No terminal, digitei "git clone https://github.com/Julia-maria56/git-aula1" (esse link pode ser encontrado na engrenagem que tem quando se entre no repositório, mas tem que ter atenção para o link ser do https)</li>
  <li> Com isso, o arquivo do repositório git hub aparecerá dentro do arquivo na área de trabalho</li>
  <li>Agora, entre no repositório através do terminal (você perceberá que estou dentro da minha pasta que coloquei o arquivo do repositório e que usei o comando "cmd git-aula1"</li>
  ![git2](https://github.com/user-attachments/assets/9a7d85bc-8662-43f4-9a25-4c8fbfd90cc5)
  <li>Depois disso, é só dar um "code ."</li>
  </ol>
  <li>Após estar dentro do vscode, aperte "ctrl+ aspas" e coloque o terminal no modo bash.  </li>
  <h4>No terminal e a´pos adicionar os arquivos desejados, faça os seguintes comandos</h4>
  <ul>
    <li>git add . //para adicionar todos os arquivos</li>
    <li>git commit -m "mensagem"</li>
    <li>git push origin main</li>
  </ul>

  <h1>Sobre as branches</h1>
  <h3>Se eu quiser criar uma branch, eu devo seguir os seguintes passos:</h3>
  <ol>
    <li>No terminal do vscode, digitar: "git checkout -b [nome branch]"</li>
    <li>git add .</li>
    <li>git commit -m "uma nova versão"</li>
    <li>git push origin [nome da branch]</li>
  </ol>
  <h4>Para voltar à main:git checkout main </h4>

  <h1>E se eu quiser tranformar uma branch remota em local?</h1>
  <h3>No github, apertei em "2 branches" e criei uma nova branch chamada "alternativa-b", com base em "alternativa-a"</h3>
  <h3>Após remotamente alterar a branch alternativa-b, fui no terminal bash do vscode e digitei os comandos:</h3>
  <ul>
    <li>git fetch</li>
    <li>git checkout alternativa-b</li>
  </ul>

  <h1>Se eu quiser juntar duas branchs localmente:</h1>
  <h3> Eu devo entrar na branch que eu quero que receba as modificações. No meu caso, foi a branch "alternativa-a"</h3>
  <h3>Então, eu usei o comando "git checkout alternativa-a". Depois:</h3>
  <ul>
    <li>git merge alternativa-b</li>
    <li>git add .</li>
    <li>git commit -m "alternativas A e B unidas"</li>
    <li>git push origin alternativa-a</li>
  </ul>

  <h1>Pull request (juntar duas branchs remotamente</h1>
  <h3>Você vai para a sessão de pull request e lá escolhe a base, no caso main e a outra branch que vai "entrar" na main, no caso, alternativa-a</h3>
  <h3>Depois, é só escrever uma mensagem, ver se não tem conflito e "merger" as duas branchs</h3>
  <h4>Para transferir essa alteração remota para o meu vscode, usa-se <h2>git pull origin main</h2></h4>

  <h1>Caso eu altere remotamente uma branch, mas a queira localmente, eu uso:</h1>
  <h3>git checkout alternativa-b</h3>
  <h3>git pull origin alternativa-b</h3>

  <h1>Caso eu queira adicionar uma branch "alternativa-b" remota em uma main local, eu devo:</h1>
  <ul>
    <li>git checkout main</li>
    <li>git pull origin alternativa-b</li>
     <li>git add .</li>
    <li>git commit -m "Main"</li>
    <li>git push origin main</li>
  </ul>
  

  
