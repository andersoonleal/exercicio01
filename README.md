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


 
<img width="468" alt="Imagem2" src="https://github.com/user-attachments/assets/21b507cf-df60-4a53-a620-1f242e40d6a3">


A) No working dir, executar o comando:
   echo 01 > arquivo.txt
<h4> 
   R: 
<h4>   
</h4>
</h4>
</h4>
<h4>


![image](![alt text](![alt text](<img width="468" alt="Imagem2" src="https://github.com/user-attachments/assets/21b507cf-df60-4a53-a620-1f242e40d6a3">
))


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



![image](![alt text](![alt text](image-2.png))


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


![image](![alt text](![alt text](image-3.png))


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

![image](![alt text](![alt text](image-4.png))


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



![image](![alt text](![alt text](image-5.png))



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

![image](![alt text](![alt text](image-6.png))


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


![image](![alt text](![alt text](image-7.png))


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



![image](![alt text](![alt text](image-8.png))


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


![image](![alt text](![alt text](image-9.png))


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

![image](![alt text](![alt text](![alt text](image-10.png))

![image](![alt text](![alt text](![alt text](image-11.png))


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

![image]![alt text](![alt text](image-12.png))


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

![image](![alt text](![alt text](image-13.png))
