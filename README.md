
## 🛠️ Bugs Funcionais

**[1º BUG] - Botão de compartilhamento no "X" não está funcionando corretamente**

**Issue Type:** Funcional \
**Prioridade:** Média \
**Frequência:** Sempre \
**Environment:** Todos os navegadores

**Reprodução do Bug:**
- Abra https://academybugs.com
-  Ache a aba "Find Bugs" na barra de navegação
- Clique em um produto
- Na página do produto, clique no ícone do X

**Resultado esperado:** O ícone de compartilhamento do X, deveria redirecionar o usuário para o X 

**Resultado encotrado:** O ícone de compartilhamento do X está redirecionando para uma página quebrada

![Primeiro Bug Video](gifs/bug-1.gif)




**[2º BUG] Câmbio de moedas não está funcionando** 

**Issue Type:** Funcional \
**Prioridade:** Alta \
**Frequência:** Sempre com todas as moedas \
**Environment:** Todos os navegadores

**Reprodução do Bug:**
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Clique em um produto
- Clique no menu dropdown de "Select a Currency"
- Troque a moeda

**Resultado esperado:** O usuário pode trocar de moeda normalmente quando clicar na aba de "Select a currency"

**Resultado encontrado:** A moeda não é alterada quando clicado em "Select a currency"

![Segundo Bug Video](gifs/bug-2.gif)


**[3º BUG] - Manufacturer 404 error** \
**Issue Type:** Funcional \
**Prioridade:** Média \
**Frequência:** Sempre \
**Environment:** Todo os navegadores

**Reprodução do Bug:**
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Clique no link do "Manufacturer" em baixo dqa quantidade

**Resultado esperado:** Ao clicar no link, o usuário deveria ser levado para a página do fabricante

**Resultado encontrado:** Ao clicar no link, abre uma página quebrada

![Terceiro Bug Video](gifs/bug-3.gif)


**[4º BUG] - Não é possível colocar mais de 3 produtos iguais no carrinho**

**Issue Type:** Funcional \
**Prioridade:** Alta \
**Frequência:** Sempre \
**Environment:** Todos os navegadores

Reprodução do Bug:
- Abra https://academybugs.com 
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Adicione um produto no carrinho
- No carrinho, adicione mais de 3 produtos iguais clicando no "+" e depois em "update"

**Resultado esperado:** A quantidade de produtos pode ser maior do que 2

**Resultado encontrado:** Quando clicado em "update" a quantidade do produto volta para 2

![Quarto Bug Video](gifs/bug-4.gif)

**[ 5º BUG] - Preço maior no valor total da compra** \
**Issue Type:** Funcional \
**Prioridade:** Alta \
**Frequência:** Sempre \
**Environment:** Todos os navegadores

**Reprodução do Bug:**
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Adicione ao carrinho
- Vá até a página do carrinho
- Em "Cart Totals" é encontrado o bug


**Resultado esperado:** O valor total do pedido deve ser igual ao valor dos produtos selecionados pelo o usuário

**Resultado encontrado:** o valor total é $100 maior do que o valor do carrinho

![Quarto Bug Video](gifs/bug-5.gif)

## 🖥️ Bugs Visuais


**[6º BUG] - Imagem da "Dark Grey Jeans"** \
Issue Type: Visual \
Prioridade: Média  \
Frequência: Sempre\
Environment: Todos os navegadores

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Clique no produto "Dark Grey Jeans"

**Resultado esperado:** A imagem deveria preencher todo o card como em todos os outros produtos da loja.

**Resultado encontrado:** A imagem não está preenchendo totalmente o card.

![Quarto Bug Video](gifs/bug-6.gif)

**[7º BUG] - Botão "Sign In" no local errado** \
Issue Type: Visual \
Prioridade: Baixa \
Frequência: Sempre \
Environment: Todos os navegadores

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Desça até o final da página
- Localize o botão "Sign In" no canto inferior direito

**Resultado esperado:** Campo de Login com respiro na página, respeitando o espaçamento predefinido

**Resultado encontrado:** O botão "Sign In" está invadindo o footer da página  

![Quarto Bug Video](gifs/bug-7.gif)

## ❌ Bugs de Performance

**[8º BUG] - Botões "View" não estão funcionando**

Issue Type: Crash \
Prioridade: Alta \
Frequência: Sempre \
Environment: Todos os navegadores

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Clique no botão de mostrar 10 produtos ou no botão de 50 produtos


**Resultado esperado:** O número de produtos mostrados deveria ser de acordo com a quantidade selecionada no botão

**Resultado encontrado:** A página trava de acordo quando clica no número de resultado 

![Oitavo Bug Video](gifs/bug-8.gif)

**[ 9º BUG] - Botão de comentário não está funcionando**
Issue Type: Crash \
Prioridade: Média \
Frequência: Sempre \
Environment: Todos os navegadores 

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Desçaa até o campo de comentários
- Escreva um comentário e clique no botão "Post comment"


**Resultado esperado:** Quando clicado em "Post comment", o usuário deveria conseguir postar seu comentário

**Resultado encontrado:** Quando clicado em "Post comment" nada acontece

![Nono Bug Video](gifs/bug-9.gif)

## 📝 Bugs de Conteúdo

**[10º BUG] - Descrição em Lorem Ipsum** \
Issue Type: Conteúdo \
Prioridade: Alta \
Frequência: Sempre \
Environment: Todos os navegadores

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Clique em um produto
- Leia a descrição do produto

**Resultado esperado:** Descrição com informações condizentes com o produto.

**Resultado encontrado:** Texto de preenchimento Lorem Ipsum 

![Decimo Bug Video](gifs/bug-10.gif)

**[11º BUG] - Typo nas cores dos produtos** \
Issue Type: Conteúdo \
Prioridade: Baixo \
Frequência: Sempre \
Environment: Todos os produtos

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto com várias opções de cores ("Professional Suit", por exemplo)
- Escolha as cores amarela e laranja

**Resultado esperado:** A cor "yellow" e "orange" deveriam estar escritas corretamente

**Resultado encontrado:** "Yellow" está como "Yelow" e "Orange" está como "Orang"

![Decimo primeiro Bug Video](gifs/bug-11.gif)

**[12º BUG] - Caracteries estranhos ao lado do produto** \
Issue Type: Conteúdo \
Prioridade: Baixa \
Frequência: Sempre \
Environment: Todos os navegadores 

Reprodução do Bug:
- Abra https://academybugs.com
- Ache a aba "Find Bugs" na barra de navegação
- Selecione um produto
- Adicione o produto ao carrinho
- Desça a página até a parte de "Shopping Cart" localizada no canto inferior direito
- Passe o mouse sobre o segundo texto chamado "Shopping Cart"
- Verifique os caracteries estranhos após o nome do produto que está no carrinho

**Resultado esperado:** Caracteries apenas do nome do produto

**Resultado encontrado:** Caracteries estranhos ao lado do nome do produto

![Decimo terceiro Bug Video](gifs/bug-12.gif)
