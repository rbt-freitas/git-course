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

<table>
<thead>### Configuração Inicial</thead>
<tr><td><b><b>$ git config --global user.name "nome do usuario"</b></td><td>para adicionar o nome do usuário</td></tr>
<tr><td><b><b>$ git config --global user.emai "seu_email@dominio.com"</b></td><td>para adicionar o email do usuário</td></tr>
<thead>### Como manipular o respositório</thead>
<th><td>Comando</td><td>Descrição</td></tr>
<tr><td><b>$ git status</b></td><td>consultar o status dos arquivos no repositório</td></tr>
<tr><td><b>$ git diff --staged</b></td><td>verificar a diferença entre arquivos</td></tr>
<tr><td><b>$ git add .</b></td><td>enviar os arquivos modificados para a área de "staged" (passo antes do commit)</td></tr>
<tr><td><b>$ git commit -m "Notas importantes da versão"</b>Efetiva as alterações da área "staged" e retorna os arquivos para a área "unmodified"</td></tr>
</table>

<div>
<a href="https://instagram.com/rbt.freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/rbt-freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>
