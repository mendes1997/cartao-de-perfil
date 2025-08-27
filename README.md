TILOS GERAIS PARA A PÁGINA */

/* O objetivo aqui é apenas criar um fundo e centralizar nosso cartão. */

body {

    font-family: 'Helvetica Neue', Arial, sans-serif; /* Uma fonte limpa e segura */

    background-color: #e0e0e0; /* Um cinza claro para o fundo */

    color: #333; /* Cor de texto padrão (cinza escuro) */

 

    /* Centralização do cartão na tela */

    display: flex;

    justify-content: center; /* Centraliza horizontalmente */

    align-items: center;    /* Centraliza verticalmente */

    min-height: 100vh;      /* Garante que o body ocupe 100% da altura da tela */

    margin: 0;             /* Remove qualquer margem padrão do body */

}

 

 

/* 2. ESTILOS DO CARTÃO - O FOCO DO NOSSO ESTUDO! */

.business-card {

    /* ----- DIMENSÕES ----- */

    /* Define uma largura fixa para o nosso cartão. */

    width: 400px;

   

    /* ----- O BOX MODEL NA PRÁTICA ----- */

    /*

     * padding: Espaçamento INTERNO. Cria um respiro entre o conteúdo

     * (texto, etc.) e a borda do cartão.

     */

    padding: 30px;

   

    /*

     * border: A linha que desenha o contorno do nosso cartão.

     * Sintaxe: espessura | estilo | cor

     */

    border: 1px solid #cccccc;

   

    /*

     * margin: Espaçamento EXTERNO. Como o body já está centralizando

     * o cartão com flexbox, a margem não é estritamente necessária aqui,

     * mas é importante saber que ela empurraria outros elementos para longe.

     */

   

    /* ----- OUTROS ESTILOS VISUAIS ----- */

    background-color: #ffffff; /* Fundo branco para o cartão */

    border-radius: 10px;        /* Cantos levemente arredondados */

    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Sombra suave para dar profundidade */

    text-align: center;       /* Centraliza todo o texto dentro do cartão */

}

 

 

/* 3. ESTILOS PARA OS ELEMENTOS DENTRO DO CARTÃO */

.card-name {

    font-size: 2rem; /* 32px - Tamanho grande para o nome */

    color: #2c3e50;   /* Uma cor de destaque (azul escuro) */

    margin-top: 0;    /* Remove a margem padrão de cima do h1 */

    margin-bottom: 5px; /* Pequeno espaçamento abaixo do nome */

}

 

.card-title {

    font-size: 1.1rem; /* 17.6px - Tamanho menor para o título */

    color: #7f8c8d;     /* Cinza mais suave para o título */

    font-weight: 300;   /* Fonte mais leve */

    margin-top: 0;

    margin-bottom: 20px; /* Espaçamento maior antes da linha divisória */

}

 

.card-divider {

    border: none; /* Remove a borda padrão do <hr> */

    height: 1px;  /* Define uma altura para a linha */

    background-color: #dddddd; /* Cor cinza clara para a linha */

    margin: 0 auto 20px; /* Centraliza a linha e dá espaçamento abaixo */

    width: 80%; /* Faz a linha ser um pouco menor que o cartão */

}

 

.card-contact {

    font-size: 1rem; /* Tamanho padrão para o contato */

    color: #34495e; /* Cor um pouco mais escura para o contato */

    margin-bottom: 10px;

}

 

/* Estilo específico para o link de e-mail */

.card-contact a {

    text-decoration: none; /* Remove o sublinhado do link */

    color: #3498db;         /* Cor azul para indicar que é um link clicável */

    transition: color 0.3s; /* Transição suave na cor ao passar o mouse */

}

 

/* Efeito ao passar o mouse sobre o link */

.card-contact a:hover {

    color: #2980b9; /* Escurece a cor do link */

}

# cartao-de-perfil
