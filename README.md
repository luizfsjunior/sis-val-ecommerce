### sis-val-ecommerce

# Preparação do ambiente de desenvolvimento:

1- Utilize o navegador Chrome

2- Acesse `chrome://extensions/`

3- Ative o modo desenvolvedor no canto superior direito:

![](./src/view/assets/instructions_01.png)

4- Clique em `Load Unpacked` e aponte para pasta a raíz do projeto:

![](./src/view/assets/instructions_02.png)

5-  Copie o `ID`

![](./src/view/assets/instructions_03.png)

6- Troque em todos os arquivos `html` que façam referência a ele:

![](./src/view/assets/instructions_04.png)

7- A extensão poderá ser acessada pela barra de pesquisa do navegador:

![](./src/view/assets/instructions_05.png)


<hr/>

# Casos de Uso a serem implementados:

## Informar uma compra:

1- O Consumidor receberá um formulário;

2- O Consumidor preencherá o formulário detalhando o produto comprado e confirmando que uma compra foi realizada em determinada loja;

3- O Consumidor enviara o formulário ao sistema;

4- O sistema irá validar se a compra foi realmente realizada consultando a loja cadastrada;

4.1- Se válida: O Consumidor receberá uma mensagem de agradecimento pela contribuição.

4.2- Se não válida: O Consumidor receberá uma mensagem de alerta o instruindo a revisar os dados do formulário ou cancelar a operação.

## Compartilhar experiência de compra:

1- O Consumidor faz login na plataforma;

2- O Consumidor localiza a compra realizada e confirmada pelo sistema;

3- O Consumidor clica no botão “Compartilhar Experiência”;

4- O Consumidor preenche o formulário, dá sua nota à sua experiência de compra e faz o envio;

## Criar permalink:

1- O Consumidor faz login na plataforma;

2- O Consumidor vai na opção de criar permalink;

3- O Consumidor será encaminhado à uma tela com o permalink e botões para compartilhar em redes sociais ou copiar para a área de transferência.
