1. **Definições:**
    a) É como uma pasta para o seu projeto. Ele contém todos os arquivos e guarda o histórico de mudanças.
    b) É como um ponto de salvamento no jogo. Você salva as mudanças que fez nos arquivos para poder voltar a elas depois se precisar.
    c) É como uma cópia do seu projeto onde você pode experimentar e fazer mudanças sem afetar o projeto principal.
    d) É quando você junta as mudanças de uma branch de volta para a branch principal.
    e) É quando você faz uma cópia completa de um repositório de algum lugar (como o GitHub) para o seu computador.
2. Um repositório local está no seu computador, e você pode trabalhar nele mesmo sem internet. Um repositório remoto está na internet, num serviço como o GitHub, onde outras pessoas podem ver e contribuir para o seu projeto.
3. Você abre o terminal, vai até a pasta onde quer criar o repositório e digita:
    ```bash
    git init
    ```
4. a) Verificar o status:
    ```bash
    git status
    ```
    b) Adicionar arquivos:
    ```bash
    git add avaliação
    ```
    c) Fazer commit:
    ```bash
    git commit -m "Adiciona arquivo index.html"
    ```
    d) Enviar para o repositório remoto:
    ```bash
    git push
    ```
5. É um arquivo onde você lista coisas que não quer enviar para o repositório, como senhas ou arquivos temporários. Exemplo:
    ```plaintext
    *.log
    node_modules/
    ```
6. Ajuda a organizar melhor as mudanças e permite que várias pessoas trabalhem em coisas diferentes ao mesmo tempo sem confusão.
7. Criar e mudar para uma nova branch:
    ```bash
    git branch desenvolvimento
    git checkout desenvolvimento
    ```
8. Primeiro, você muda para a branch main:
    ```bash
    git checkout main
    ```
    Depois, você faz o merge:
    ```bash
    git merge desenvolvimento
    ```
    Se tiver conflitos, você resolve manualmente nos arquivos e depois faz um commit das mudanças.
9. GitHub é um serviço na internet onde você pode colocar seus repositórios Git para compartilhar com outras pessoas e colaborar em projetos. Ele tem funcionalidades como tracking de issues, wikis para documentação, e a possibilidade de fazer forks de projetos.
10. Pull requests são pedidos que você faz para que as mudanças que você fez numa branch sejam colocadas na branch principal de um projeto. É uma forma de discutir mudanças antes de elas serem integradas.