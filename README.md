# Curso de Engenharia de Dados

## Caderno de Notas: Git

### Estados do Git
<code>
+------------------+------------------+------------------+------------------+
|                                                                           |
|    Untracked     |    Unmodified    |     Modified     |      Staged      |
+------------------+------------------+------------------+------------------+
|                  |                  |                  |                  |
|   add file  ---------------------------------------------------->         |
|                  |                  |                  |                  |
|                  |   edit file ------------->          |                  |
|                  |                  |                  |                  |
|                  |                  |    Stage file ------------>         |
|                  |                  |                  |                  |
|         <------------ Remove file   |                  |                  |
|                  |                  |                  |                  |
|                  |                  |          <------------- Commit      |
|                  |                  |                  |                  |
+------------------+------------------+------------------+------------------+
</code>

### Configuração Inicial
<table>
<tr><td>Comando</td><td>Descrição</td></tr>
<tr><td><b>$ git config --global user.name "nome do usuario"</b></td><td>para adicionar o nome do usuário</td></tr>
<tr><td><b>$ git config --global user.emai "seu_email@dominio.com"</b></td><td>para adicionar o email do usuário</td></tr>
</table>

### Manipulando o repositório local
<table>
<tr><td>Comando</td><td>Descrição</td></tr>
<tr><td><b>$ git status</b></td><td>consultar o status dos arquivos no repositório</td></tr>
<tr><td><b>$ git add .</b></td><td>enviar os arquivos modificados para a área de "staged" (passo antes do commit)</td></tr>
<tr><td><b>$ git commit -m "Notas importantes da versão"</b></td><td>Efetiva as alterações da área "staged" e retorna os arquivos para a área "unmodified"</td></tr>
<tr><td><b>$ git push</b></td><td>envia as alterações para o respostório remoto</td></tr>
</table>


### Manipulando o respositório remoto 
<table>
<tr><td>Comando</td><td>Descrição</td></tr>
<tr><td><b>$ git feth</b></td><td>carrega os arquivos do repositório remoto no local</td></tr>
<tr><td><b>$ git pull</b></td><td>faz um merge dos arquivos do repositório remoto com os arquivos locais</td></tr>
<tr><td><b>$ git restore {nome_do_arquivo}</b></td><td>restaura a versão que foi alterado mais ainda não está na área de staged</td></tr>
<tr><td><b>$ git restore --staged {nome_do_arquivo}</b></td><td>restaura a versão que está na área de staged</td></tr>
</table>


### Visualizar históricos 
<table>
<tr><td>Comando</td><td>Descrição</td></tr>
<tr><td><b>$ git log</b></td><td>lista histórico das alterações realizadas</td></tr>
<tr><td><b>$ git diff --staged</b></td><td>verificar a diferença entre o arquivo e o que está na área de staged</td></tr>
</table>



<div>
<a href="https://instagram.com/rbt.freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/rbt-freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>
