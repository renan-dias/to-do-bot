# Hello World To-do-bot!

Olá, amigos!

Digam olá para o **To-do-bot**! Um bot em *nodejs* que consumirá *APIs* de *IA* para ajudar a organizar e rastrear objetivos. Imagine só, um ~~assistente virtual~~ que sabe exatamente o que você precisa fazer, quando fazer e como fazer. Ele vai te lembrar das suas tarefas, te motivar, te dar feedback e até te elogiar quando você terminar. Não é incrível?

Mais incrível será compartilha todo o desenvolvimento com vocês! 

✨Um feliz 2024!
Que seja um ano incrível para *to-dos* vocês**✨
![Logo do To-do-bot: Imagem de um robô amarelo segurando um lápis em um círculo. O robô tem grandes olhos azuis e no peitoral 'T.D' está escrito](https://th.bing.com/th/id/OIG.7WoXJNWmjG3z1zSIJuRk?pid=ImgGn)


## Ajustes e melhorias
  

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

  

 - [x] Concepção do Projeto
	 - [x] Definição do escopo
	 - [x] Análise dos requisitos
	 - [x] Planejamento
	 - [x] Estruturação do ambiente 
 
 - [ ] TO-DO
	 - [ ] Criar, editar, excluir e marcar como concluídas as tarefas.
	- [ ] Criar lembretes para tarefas específicas.
	- [ ] Criar e acessar notas.
	- [ ] Testar cada componente e funcionalidade.

  - [ ] DEPLOY do Projeto
	 - [ ] Implantar o projeto em um servidor.

 - [ ] Documentar o projeto para usuários e desenvolvedores.

 - [ ] Escolher uma licença para o projeto.

 
  ## 💭To-do_Bot

```mermaid
sequenceDiagram

participant User as Usuário participant 
Bot as Bot User->>Bot: Logar 

Bot->>User: Solicitar nome e senha 
User->>Bot: Informar nome e senha 
Bot->>User: Validar nome e senha alt Nome ou senha inválidos Bot->>User: Erro de login else Nome e senha válidos 
Bot->>User: Logado com sucesso end 
User->>Bot: Criar tarefa Bot->>User: Solicitar título, descrição, data de vencimento e se a tarefa está concluída 
User->>Bot: Informar os dados da tarefa 
Bot->>User: Criar tarefa 
Bot->>User: Tarefa criada com sucesso User->>Bot: Marcar tarefa como concluída 
Bot->>User: Solicitar o identificador da tarefa 
User->>Bot: Informar o identificador da tarefa 
Bot->>User: Marcar tarefa como concluída 
Bot->>User: Tarefa marcada como concluída com sucesso 
User->>Bot: Adicionar lembrete para uma tarefa 
Bot->>User: Solicitar o identificador da tarefa, a data de vencimento e a hora do lembrete 
User->>Bot: Informar os dados do lembrete 
Bot->>User: Adicionar lembrete 
Bot->>User: Lembrete adicionado com sucesso 
User->>Bot: Visualizar todas as tarefas 
Bot->>User: Listar todas as tarefas 
User->>Bot: Visualizar uma tarefa específica 
Bot->>User: Listar os dados da tarefa específica
```

<!-- ## 📫 Contribuindo para <nome_do_projeto>

  

Para contribuir com **To-Do-Bot**, siga estas etapas:
 

1. Bifurque este repositório.

2. Crie um branch: `git checkout -b <nome_branch>`.

3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`

4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`

5. Crie a solicitação de pull.



Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).
 -->
  
## 😄 Seja um dos contribuidores
 

Quer fazer parte desse projeto? Clique [AQUI](CONTRIBUTING.md) e leia como contribuir.

  

## 📝 Licença

  

Esse projeto está sob licença. Veja o arquivo [LICENÇA](LICENSE.md) para mais detalhes.
