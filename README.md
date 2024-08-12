<h4 align="center">
⬇️ * # Exercicio01 # * ⬇️
</h4>
<h4 align="center">
  * Exercicio01_CICD_Impacta: *
</h4>

<h4>
  ! CONFIGS INICIAIS !
<h4> 
   R: 
<h4>
</h4>
</h4>
</h4>
<h4>


 
<img width="468" alt="Imagem1" src="https://github.com/user-attachments/assets/e55aa918-bd5d-43fe-8d18-58258e91fca9">



A) No working dir, executar o comando:
   echo 01 > arquivo.txt
<h4> 
   R: 
<h4>   
</h4>
</h4>
</h4>
<h4>


<img width="468" alt="Imagem2" src="https://github.com/user-attachments/assets/21b507cf-df60-4a53-a620-1f242e40d6a3">


B) Adicionar o arquivo no staging e conferir o status:
<h4> 
 R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4> 
<h4>
</h4>
</h4>
</h4>
<h4>



<img width="468" alt="Imagem3" src="https://github.com/user-attachments/assets/738018a7-12c5-43d8-8079-83748dcc5cd0">



C) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt":
<h4> 
R:
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "git add example - arquivo.txt" .
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


<img width="468" alt="Imagem4" src="https://github.com/user-attachments/assets/e4853e6d-8ff8-4f58-b131-e15f215e5605">



D) Sobrescrever o conteúdo do arquivo.txt:
   echo 02 > arquivo.txt
<h4> 
R:
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 02 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

<img width="468" alt="Imagem5" src="https://github.com/user-attachments/assets/5f213908-f1da-4987-97ee-b6744f98b94b">



E) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



<img width="468" alt="Imagem6" src="https://github.com/user-attachments/assets/dff63255-aa71-44f1-88d5-cbe43f623e1b">




F) Adicionar novamente o arquivo no staging e conferir o status:
<h4>
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

<img width="468" alt="Imagem7" src="https://github.com/user-attachments/assets/5ae8e764-abf2-4159-a11b-ca8753f7de23">



G) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>




H) Sobrescrever o conteúdo do arquivo.txt:
 echo 03 > arquivo.txt
<h4>
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 03 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


<img width="468" alt="Imagem8" src="https://github.com/user-attachments/assets/f541aaf2-ee23-440c-91b3-d97db5130514">



I) Verificar o diffing no arquivo:
<h4>
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



<img width="468" alt="Imagem9" src="https://github.com/user-attachments/assets/f320a633-0998-4046-9e57-74d252f7e921">



J) Fazer o restore do arquivo da área de staging e verificar o status:
<h4>
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git restore arquivo.txt 
</h4>
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


<img width="468" alt="Imagem10" src="https://github.com/user-attachments/assets/254d03e3-53c9-4131-a5b1-92e5901b83af">



K) Realizar o commit do arquivo e verificar o log:
<h4>
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "Primeiro Commit - Arquivo.txt"
</h4>
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git log
<h4>
</h4>
</h4>
</h4>
<h4>

<img width="468" alt="Imagem11" src="https://github.com/user-attachments/assets/3a9f8f38-450c-46b2-a871-65940468d780">


<img width="468" alt="Imagem12" src="https://github.com/user-attachments/assets/f89427df-fcc2-4c19-b3a4-7d5c903ed772">



L) Adicionar um arquivo gitignore com o seguinte conteúdo:
 *.txt
<h4> 
R: 
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ vi .gitignore
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

<img width="468" alt="Imagem13" src="https://github.com/user-attachments/assets/5f796e7f-93e2-4592-9275-cb517cab1ceb">



M) Criar um arquivo novo.txt e verificar o status:
<h4> 
R:
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > novo.txt
</h4>
<h4>
@andersoonleal ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

<img width="468" alt="Imagem14" src="https://github.com/user-attachments/assets/25ad0033-b571-419a-a95e-1c4d0ad87883">

