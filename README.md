```bash
 ________  ______   ______                                                                       
|        \|      \ /      \                                                                      
 \$$$$$$$$ \$$$$$$|  $$$$$$\                                                                     
   | $$     | $$  | $$___\$$                                                                     
   | $$     | $$   \$$    \                                                                      
   | $$     | $$   _\$$$$$$\                                                                     
   | $$    _| $$_ |  \__| $$                                                                     
   | $$   |   $$ \ \$$    $$                                                                     
    \$$    \$$$$$$  \$$$$$$                                                                      
                                                                                                 
                                                                                                 
                                                                                                 
  ______               __                                         __      __                     
 /      \             |  \                                       |  \    |  \                    
|  $$$$$$\ __    __  _| $$_     ______   ______ ____    ______  _| $$_    \$$  ______   _______  
| $$__| $$|  \  |  \|   $$ \   /      \ |      \    \  |      \|   $$ \  |  \ /      \ |       \ 
| $$    $$| $$  | $$ \$$$$$$  |  $$$$$$\| $$$$$$\$$$$\  \$$$$$$\\$$$$$$  | $$|  $$$$$$\| $$$$$$$\
| $$$$$$$$| $$  | $$  | $$ __ | $$  | $$| $$ | $$ | $$ /      $$ | $$ __ | $$| $$  | $$| $$  | $$
| $$  | $$| $$__/ $$  | $$|  \| $$__/ $$| $$ | $$ | $$|  $$$$$$$ | $$|  \| $$| $$__/ $$| $$  | $$
| $$  | $$ \$$    $$   \$$  $$ \$$    $$| $$ | $$ | $$ \$$    $$  \$$  $$| $$ \$$    $$| $$  | $$
 \$$   \$$  \$$$$$$     \$$$$   \$$$$$$  \$$  \$$  \$$  \$$$$$$$   \$$$$  \$$  \$$$$$$  \$$   \$$
                                                                                                 
                                                                                                 
```                                                                                                 
---
# Desafio ????
Crie um pipeline de integra????o cont??nua utilizando tecnologias como Azure DevOps, TravisCI, Github Actions ou algum outro de sua prefer??ncia. O seu pipeline deve:
- Provisionar uma estrutura com IaC utilizando [Terraform](https://www.terraform.io/) ou outra ferramenta, podendo utilizar um provedor de nuvem p??blica ou ser executado localmente.
  - 2 hosts Windows
  - 2 hosts Linux
- Utilizar [Ansible](https://docs.ansible.com/) ou outra ferramenta para configurar:
  - Nos hosts Linux, provisionar um Apache ou um NGINX com um Hello World.
  - Nos hosts Windows: Instale o MSI do Apache, e provisione o mesmo Hello World utilizado no Linux.
  <small>dica: Crie um arquivo ???index.html??? no reposit??rio, e copie ele para os diret??rios necess??rios.</small>
- Desenvolver uma API, na linguagem deseja, que retorne uma mensagem de "Hello World!" tanto em uma requisi????o GET como POST.

**IMPORTANTE**: Inclua no README do projeto melhorias que seriam necess??rias caso voc?? tivesse mais tempo para entregar e desafios encontrados durante a execu????o.

---
# Documenta????o ????
- [ ] O c??digo foi entregue com um arquivo de README claro de como se guiar?
- [ ] O c??digo possui coment??rios pertinentes?
- [ ] O c??digo est?? em algum controle de vers??o?
- [ ] Os commits s??o pequenos e consistentes?
- [ ] As mensagens de commit s??o claras?

---
# Observa????es ????
- Voc?? pode utilizar VMs ou K8s, tendo prefer??ncia para utiliza????o de K8s.
- **Novamente**: N??o se preocupe com linguagem de programa????o, pode utilizar a que se sentir mais confort??vel. 
- N??o se preocupe com ferramentas de IaC, pode utilizar tamb??m a que se sentir mais confort??vel.

---
???? O prazo para realiza????o ?? de 1 semana, podendo realizar o ??ltimo commit no reposit??rio at?? dia que recebeu o teste (+7 Dias). ????
