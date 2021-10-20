# Desafio - Encurtador de URL com API do Bitly

### Contexto
Bitly é um site que gera links curtos e provê uma API para que seja possível gerar os links curtos sem a necessidade de abrir o site.

##### API a ser consumida
- Criar uma conta gratuita em: [bitly.com](https://bitly.com/ "Bitly")
- Confirmar na caixa do email utilizado para criar a conta, clicando no botão "verify email" no email que irá receber de parte do Bitly
- Em seguida, clicar em:
    1. Profile Settings
    2. Generic Access Token
    3. Inserir o Password
    4. Clicar em Generate Token
    5. Copiar o Token num "bloco de notas", por exemplo.

### Estruturação da aplicação
Utilizar uma IDE Java para criar uma aplicação desktop:
- O token NÃO PODE estar no código do programa
- É necessário que haja um campo para o usuário colocar a URL a ser encurtada
- Deve existir um campo onde o usuário coloca o Token
- Ao lado do campo acima mencionado, deve haver um botão **Salvar** de maneira que, ao fechar o programa e reiniciá-lo, o usuário não precise colocar o Token novamente
- Colocar um botão **Generate short link** de maneira que o usuário, ao clicar nele, gere o link curto do Bitly, tenha como *copiar/colar*
- Deve haver também um botão **Copy to clipboard** caso o usuário seja preguiçoso suficiente para selecionar o text e copiar manualmente

#### Opcional
Criar uma página HTML:
- Seguir a mesmíssima lógica descrita para a aplicação desktop
- Salvar o token do usuário em um cookie, ou de alguma outra maneira desde que seja local e o usuário não tenha trabalho extra para isso