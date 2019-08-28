# Sistemas Distribuídos
Repositório para a matéria de Sistemas Distribuídos

# Descrição do Projeto

A ideia do projeto a ser implementado na disciplina é o Jogo da Forca no qual será possível dois jogadores se enfrentarem.  O jogo termina ou com o acerto da palavra ou com o término de palpites de letras que será 6. O jogo consistirá em uma "melhor de três"

**Ferramentas**:
* A linguagem de programação será em JavaScript usando para o Backend: Node e para o Frontend: ReactJS.
* O banco será NoSQL: MongoDB
* Express será utilizado para criação do servidor

**Componentes**:

- **Clients** (acessando pelo navegador)
- **Servidor**
- **Banco de Dados**

**Lista de testes a serem implementados**:

- **Testes unitários:** a lógica do jogo vai ser validada automaticamente com teste unitários
- **Teste de recuperação de falhas:** validar se o servidor está salvando os dados no banco de dados.
- **Teste de concorrência:** validar o numero de clientes que o servidor consegue suportar, para que o mesmo não tenha comportamentos estranhos.
- **Demonstração de funcionalidades:** Mostrar que as funcionalidades estão implementadas, ou seja, que é realmente possível jogar o jogo sem falhas.
