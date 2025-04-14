✅ Avaliação do Módulo 2 - Desenvolvimento Web com Frameworks e HTML/CSS
bom, abaixo estão alguns exemplos de comentarios contiidos no código:
<!-- Cabeçalho do site -->: explica que a seção seguinte é o cabeçalho do site.
<!-- Logotipo da Cafeteria UFMS -->: explica que a imagem seguinte é o logotipo da cafeteria.
<!-- Menu de navegação -->: explica que a seção seguinte é o menu de navegação.
<!-- Seção principal do site -->: explica que a seção seguinte é a principal do site.
<!-- Seção de apresentação -->, <!-- Seção sobre a cafeteria --> e <!-- Seção de contato -->: explicam o propósito de cada seção dentro da seção principal.
<!-- Rodapé do site -->: explica que a seção seguinte é o rodapé do site.
Objetivo
O objetivo desses comentários é fornecer uma visão clara da estrutura do código e ajudar a entender o propósito de cada seção, tornando mais fácil a manutenção e o desenvolvimento do site.

Durante o desenvolvimento do site da Cafeteria UFMS, tomamos decisões cuidadosas em relação ao design, tecnologia e conteúdo. Optamos por um layout responsivo, HTML semântico e CSS responsivo para garantir acessibilidade e flexibilidade. A estrutura de navegação foi projetada para ser simples e intuitiva, com conteúdo relevante e conciso em cada seção. Essas decisões visaram criar um site visualmente atraente, fácil de navegar e acessível em diferentes dispositivos, atendendo às necessidades da cafeteria e de seus clientes.


Exemplo pratico:
<!-- Cabeçalho do site -->
<header>
  <!-- Logotipo da Cafeteria UFMS -->
  <img src="logo.png" alt="Logotipo da Cafeteria UFMS">
  <!-- Menu de navegação -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#sobre">Sobre</a></li>
      <li><a href="#contato">Contato</a></li>
    </ul>
  </nav>
</header>

<!-- Seção principal do site -->
<main>
  <!-- Seção de apresentação -->
  <section id="home">
    <h1>Bem-vindo à Cafeteria UFMS!</h1>
    <p>Aqui você encontra os melhores cafés e lanches da universidade.</p>
  </section>
  
  <!-- Seção sobre a cafeteria -->
  <section id="sobre">
    <h2>Sobre a Cafeteria UFMS</h2>
    <p>Nossa cafeteria foi fundada em 2010 com o objetivo de oferecer uma experiência única aos nossos clientes.</p>
  </section>
  
  <!-- Seção de contato -->
  <section id="contato">
    <h2>Contato</h2>
    <p>Entre em contato conosco para mais informações.</p>
    <form>
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome"><br><br>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email"><br><br>
      <input type="submit" value="Enviar">
    </form>
  </section>
</main>

<!-- Rodapé do site -->
<footer>
  <p>&copy; 2025 Cafeteria UFMS. Todos os direitos reservados.</p>
</footer>
