Portfolio Pessoal
Este é o meu portfólio pessoal, criado com HTML e CSS para apresentar minhas habilidades e experiências como estudante de engenharia de software com foco em desenvolvimento backend.

Tecnologias Utilizadas
HTML5: Estrutura da página e conteúdo.
CSS: Estilização e layout.
Como visualizar
Clone este repositório: git clone https://github.com/doranybraga/seu-portfolio.git
Abra o arquivo index.html em seu navegador.
Estrutura do Projeto
index.html: Contém o conteúdo principal da página, incluindo informações sobre mim, minhas habilidades e experiências, e links para meu LinkedIn e GitHub.
style.css: Define os estilos visuais da página, como cores, fontes, layout e responsividade.

Documentação do Código: Portfolio Pessoal
index.html

Este arquivo representa a estrutura principal da página web do portfólio, utilizando HTML (Hyper Text Markup Language) para definir os elementos e conteúdos que serão exibidos.

Conceitos:

HTML: Linguagem de marcação que define a estrutura de uma página web.
Elementos HTML: Tags que representam diferentes partes do conteúdo, como cabeçalho (<header>), corpo principal (<main>), rodapé (<footer>), parágrafos (<p>), títulos (<h1>, <h3>), imagens (<img>), links (<a>), entre outros.
Atributos: Propriedades adicionais dos elementos, como lang (idioma da página), charset (codificação de caracteres), name, content, class (para aplicar estilos CSS), href (destino do link), src (caminho da imagem), alt (texto alternativo para a imagem) e height (altura da imagem).
Tecnologias:

HTML5: Versão mais recente do HTML, com novos elementos e recursos.
CSS: Cascading Style Sheets, usada para estilizar a aparência da página (cores, fontes, layout, etc.). O arquivo style.css é referenciado no index.html através da tag <link>.
Conteúdo:

Cabeçalho (<header>): Seção vazia no momento, possivelmente para adicionar um menu de navegação ou logotipo no futuro.
Corpo principal (<main>):
Seção de apresentação (<section class="apresentacao">): Contém o conteúdo principal da página.
Título (<h1>): "Olá, meu nome é DORANY".
Subtítulo (<h3>): "Sou estudante de engenharia de software focada em desenvolvimento backend."
Parágrafo (<p>): Descreve as habilidades e experiências da pessoa, incluindo tecnologias como Java, Spring Boot, Microserviços, HTML, CSS, JavaScript, SQL, além de gestão de projetos, design de marcas e experiência do cliente.
Botões (<div class="apresentacao__botoes">): Links para o LinkedIn e GitHub.
Imagem (<img>): Foto de perfil.
Rodapé (<footer>): Seção vazia, possivelmente para adicionar informações de contato ou copyright no futuro.
style.css

Este arquivo contém as regras de estilo CSS que definem a aparência visual da página.

Conceitos:

CSS: Linguagem de estilo usada para controlar a apresentação de elementos HTML.
Seletores: Usados para identificar os elementos HTML que serão estilizados (ex: body, .nome, .texto-destaque, .curso-enfase, .apresentacao, etc.).
Propriedades e valores: Definem as características visuais dos elementos, como height, box-sizing, background-color, color, margin, display, align-items, justify-content, padding, gap, width, font-family, font-weight, font-style, font-size, text-align, border-radius, text-decoration.
Importação de fontes: A regra @import importa a fonte "Poppins" do Google Fonts para ser usada na página.
Estilos:

Corpo (body): Define altura total da tela, tipo de caixa, cor de fundo preta e cor do texto cinza claro.
Classes: Estilos específicos para elementos com classes como .nome (cor vermelha), .texto-destaque (cor rosa), .curso-enfase (cor cinza claro), .apresentacao (margens, flexbox, alinhamento, espaçamento), .apresentacao__conteudo (largura, altura, família da fonte), .apresentacao__titulo (tamanho da fonte, família da fonte, peso da fonte), .apresentacao__tecnologias (tamanho da fonte, família da fonte, peso da fonte), .apresentacao__botoes (flexbox, justificação), .apresentacao__botoes__link (cor de fundo, cor do texto, largura, alinhamento de texto, bordas arredondadas, família da fonte, tamanho da fonte, padding, remoção de sublinhado), .apresentacao_foto (padding).
