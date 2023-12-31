# Atividade SENAI Versionamento :computer:

## Atividade 1 - Criação e unificação de um repositório remoto para controle de versionamento de códigos-fonte

#### Descrição:
Para resolver a situação-problema apresentada, você deve buscar uma solução para preservar o histórico de alterações do código-fonte do projeto, bem como realizar a conciliação de alterações em um mesmo repositório.


### Lista de Atribuições para conclusão da atividade :white_check_mark:
---
- [x]  criar um repositório on-line 
- [x]  criar um arquivo index.txt no repositório remoto para simular uma alteração feita por outro programador, elencando os principais comandos na sequência indicada a seguir, utilizados para gerenciar o versionamento de seu código e publicar no repositório remoto:
```
    git status
    git add
    git commit
    git push
    git checkout
    git merge
    git pull
    git remote
```
- [x]  criar um arquivo index.txt no repositório local, copiar e colar as linhas de código indicadas abaixo:
```
<HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
   <H1> TÍTULO1 </H1>
</BODY>
</HTML>
```
- [ ]  publicar seu arquivo na branch main;
- [ ]  criar uma nova branch, chamada feature1;
- [ ]  na branch feature1, publicar o mesmo arquivo;
- [ ]  realizar seguinte alteração na linha h1 do arquivo da branch main:
```
<HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
    <H1> VERSIONAMENTO </H1>
</BODY>
</HTML>
```
 

- [x]  realizar seguinte alteração na linha h1 do arquivo da branch feature1:
```
 <HTML>
<HEAD><TITLE>ATIVIDADE DE VERSIONAMENTO</TITLE></HEAD>
<BODY>
   <H1> GIT </H1>
</BODY>
</HTML>
```
- [ ]  realizar o merge da branch feature1 com a branch main;
- [ ]  resolver os conflitos apresentados.
- [ ]  Entregar atividade :tada: :smile:

### Tecnologias
---
#### IDLE 
- Visual Studio Code

Obs: O vsCode não possui suporte de visualização MarkDown para emoji e Checkbox. Então foi necessário instalar as extensões:
- Markdown Emoji
- Markdown Checkboxes