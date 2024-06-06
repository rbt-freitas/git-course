### Curso de Engenharia de Dados

## Caderno de Notas: Git

# Estados do Git
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

# Configuração Inicial

Adiciona o nome do usuário
$ git config --global user.name "nome do usuario"

Adiciona o email do usuário
$ git config --global user.emai "seu_email@dominio.com"


# Como manipular o respositório

Verifica o status dos arquivos no repositório
<b>$ git status</b>

Verifica a diferença entre arquivos
<b>$ git diff --staged</b>

Envia os arquivos modificados para a área de "staged" (passo antes do commit)
<b>$ git add .</b>

Efetiva as alterações da área "staged" e retorna os arquivos para a área "unmodified"
<b>$ git commit -m "Notas importantes da versão"</b>


<div>
<a href="https://instagram.com/rbt.freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
<a href="https://www.linkedin.com/in/rbt-freitas" target="_blank"><img loading="lazy" src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>   
</div>
