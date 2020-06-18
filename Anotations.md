## First Challenge of Fase 02 - Launchbase

 Sobre o desafio
Criar um arquivo html que contenha um favicon e um header com 3 links: Comunidade, Email e Telefone.

- Favicon
O favicon é o ícone que aparece na aba do navegador. O arquivo está disponível com o nome favicon.ico. Para utilizá-lo é necessário importá-lo com a tag link no html. ser dada a dica de utilizar a tag link na head do html.

<link rel="icon" href="favicon.ico" type="image/x-icon" />

- Links

Comunidade: Link que deve apontar para o convite da comunidade aberta da rocketseat (https://discordapp.com/invite/gCRAFhc)

Email: Link que deve chamar o comando de enviar email para o destinatário oi@rocketseat.com.br. Dica: utilize o comando mailto dentro do href;

Telefone: Link que deve chamar o comando de realizar uma ligação para o número +5547992078767. Dica: utilize o comando tel dentro do href;

- Estilização

Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

- Deve ser aplicado um background
- Deve ser utilizada a fonte Roboto
- O header precisa ocupar todo o espaço lateral e superior (body sem margin)
- O header precisa ter um espaçamento interno de 30px em todas as direções
- Os links devem ter um espaçamento de 30px entre si


## Favicon

    <link rel="apple-touch-icon" sizes="57x57" href="/apple-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-icon-180x180.png">
    <link rel="icon" type="image/png" sizes="192x192"  href="/android-icon-192x192.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="96x96" href="/favicon-96x96.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="manifest" href="/manifest.json">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
    <meta name="theme-color" content="#ffffff"



### Desafio 02 ####

Launchbase
Desafio 2-2: Página de descrição
“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”
Made by Rocketseat License

Sobre o desafio   |    Entrega   |    Licença

🚀 Sobre o desafio
A partir do arquivo do desafio 2-1, adicionar um novo link no header chamado Sobre. Essa página deverá mostrar informações referentes a Rocketseat.

Informações da página
Uma imagem da logo da empresa
O nome da empresa
Uma breve descrição da empresa
Uma lista com as principais tecnologias utilizadas. Dica: utilize a tag ul para lista e li para o item da lista.
Links para as redes sociais da empresa (Github, Instagram e Facebook)
Estilização
Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

A imagem deve ter uma borda e um formato circular.
Deve ser utilizada a fonte Roboto
O nome da empresa e a imagem devem ser destacar do restante
Os links das redes sociais devem ter alguma alteração visual quando o cursor do mouse passar por cima



### Desafio 03 ###

Launchbase
Desafio 2-3: Página de cursos e iframe
“Você nunca sai perdendo quando ganha conhecimento!”
Made by Rocketseat License

Sobre o desafio   |    Entrega   |    Licença

🚀 Sobre o desafio
A partir do arquivo do desafio 2.2, adicionar no header um link chamado Conteúdos. Essa página deve conter um grid onde devem ser mostrados os 3 principais cursos da Rocketseat: Starter, Launchbase e GoStack. Ao clicar em um dos cursos, deve ser aberta uma modal onde um iframe irá carregar as informações do curso selecionado.

# Informações da página

-[x] Título da página
-[x] Grid com 3 colunas e 1 linha onde serão apresentados os cards dos cursos
  

# Informações do card

- [x] Logo do curso (Starter, Launchbase e GoStack)
- [x] Título do curso
- [x] Quantidade de módulos dos cursos
- [x] Informação se o curso é gratuito ou pago
 
# Modal

O modal deve conter um iframe que busca a página do curso (dica: basta adicionar starter, launchbase ou gostack ao final de https://rocketseat.com.br/). Além do botão de fechar o modal, é preciso implementar a funcionalidade de maximizar o modal (dica: utilize a mesma lógica implementada para fechar o modalOverlay, mas trabalhe com a classe modal e utilize o método contains do classList para verificar se o elemento está ou não com a classe maximize).

# Estilização

Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

- [x] Deve ser utilizado o grid para organizar os cursos
- [x] O modal nunca deve abrir maximizado

# 📆 Entrega
Esse desafio não precisa ser entregue e não receberá correção. Após concluí-lo, adicionar esse código ao seu Github é uma boa forma de demonstrar seus conhecimentos para oportunidades futuras.

# 📝 Licença
Esse projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

# Feito com 💜 by Rocketseat 👋 Entre na nossa comunidade!