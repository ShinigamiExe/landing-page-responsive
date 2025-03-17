<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BBM MONTAGENS</title>
    <meta name="description" content="Esta é uma página de exemplo criada em HTML5.">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <link rel="stylesheet" href="estilos.css">
</head>
<body> 
    <!-- Logo -->
    <img src="https://lh3.googleusercontent.com/a-/ALV-UjUMN7lAaTzddk4nHsG3Sc-s96E6EjNN3PrIjesQsWzZLbaGNkQ=w60-h60-p-rp-mo-br100" alt="Logo BBM MONTAGENS" class="logo">

    <!-- Cabeçalho -->
    <header>
        <h1>BBM MONTAGENS</h1>
        <nav>
            <ul>
                <li><a href="#sobre">Sobre</a></li>
                <li><a href="#servicos">Serviços</a></li>
                <li><a href="#contato">Contato</a></li>
                <li><a href="#trabalhe-conosco">Trabalhe conosco</a></li>
            </ul>
        </nav>
    </header>

    <!-- Conteúdo Principal -->
    <main>
        <!-- Seção Sobre -->
        <section id="sobre">
            <h2>Quem somos?</h2>
            <p>A BBM Montagens foi fundada em 2013 por profissionais com experiência de mais de 20 anos no segmento de montagem industrial. Há mais de uma década, a BBM tem atuado nos setores de biodiesel, extração, preparação, tanques, SPC, lecitina e todos os processos da indústria, desde o recebimento da matéria-prima até a montagem da planta, fabricação de tanques e equipamentos, expedição de serviços, montagem, manutenção e startup da unidade, sempre acompanhando as inovações tecnológicas. Com um compromisso com a qualidade e a inovação, a BBM Montagens posiciona-se como uma parceira estratégica para indústrias e construtoras.</p>
        </section>

        <!-- Slideshow -->
        <div class="slideshow-container">
            <div class="slides">
                <div class="slide">
                    <img src="https://scontent.frvd4-1.fna.fbcdn.net/v/t39.30808-6/475174993_1134625235341781_5467705068436685583_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=cc71e4&_nc_ohc=s7u5Gil_ctcQ7kNvgF8WfFM&_nc_oc=Aditl7btk5Y4V4vfJy8x4QPu_jrgMdy2bWp3LmKRmT9RaNaxMZTVG84XUJ7QLZ5SRdg&_nc_zt=23&_nc_ht=scontent.frvd4-1.fna&_nc_gid=9VxvBHPF6dYXI2Dk2NVdpQ&oh=00_AYHGNjbOQzL-h-gIF8G-omeKWemWirPfTX6f15VmDm6Cqg&oe=67DE3E1A" alt="Imagem 1">
                </div>
                <div class="slide">
                    <img src="https://scontent.frvd4-1.fna.fbcdn.net/v/t39.30808-6/464823968_8701621876526553_100763055979748980_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=833d8c&_nc_ohc=fE2AH7R5V0cQ7kNvgFF0xNU&_nc_oc=AdhMizDPUcnDDEGFkjXfpTBiZt5xc0ZrQb0GKBr7e1UTuUhZW2itgaqzPZ__G__ZKa0&_nc_zt=23&_nc_ht=scontent.frvd4-1.fna&_nc_gid=66St56gjHSTV6SJV8MnqYg&oh=00_AYGJMF-F_RonVQIB4sdIpRGQhCjN0Ah-H00Oo7190yGojw&oe=67DE3371" alt="Imagem 2">
                </div>
                <div class="slide">
                    <img src="https://scontent.frvd4-1.fna.fbcdn.net/v/t39.30808-6/464876119_8701597623195645_5385082890086445443_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=833d8c&_nc_ohc=IUiYU10AxBIQ7kNvgGg4Z96&_nc_oc=AdhHnUP1ZHkfIJgLm8YGHgDvxna1h8DjTODZfhEvZono8OUZiGcY1DFyoLopLN2KkmE&_nc_zt=23&_nc_ht=scontent.frvd4-1.fna&_nc_gid=So8djQZecIOr15NEFbfI_Q&oh=00_AYE12-OtxC6z9nGLFjbIs71kSdyzO5kHvsI47PmjRGLzBA&oe=67DE28B4" alt="Imagem 3">
                </div>
                <div class="slide">
                    <img src="https://scontent.frvd4-1.fna.fbcdn.net/v/t39.30808-6/464441194_8678853212136753_6544426063714292743_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=833d8c&_nc_ohc=zP8vf6j_jmYQ7kNvgEfc-ey&_nc_oc=AdjB8o4PandztG-lndGDzkvQ9OLthKn9Jkq-VB1RUC6cRx4ZvZRtEhB_AZg3lhe5ANc&_nc_zt=23&_nc_ht=scontent.frvd4-1.fna&_nc_gid=n2Kh1gXcldkB4REfK83VFA&oh=00_AYEzzRDptI6iT6VLkmhVN9gwJsyFMh76uhhhTJJfyXi6Dw&oe=67DE3A2B" alt="Imagem 4">
                </div>
            </div>
            <button class="prev" onclick="moveSlide(-1)">&#10094;</button>
            <button class="next" onclick="moveSlide(1)">&#10095;</button>
        </div>

        <!-- Seção Serviços -->
        <section id="servicos">
            <h2>Serviços</h2>
            <p>Abaixo você poderá encontrar o tipo de serviço que melhor se enquadra em suas necessidades:</p>
            <div class="container">
                <!-- Card 1 -->
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipPVFueASqIyVtMG-4dUtZCVXfh0dl3GqmPqvuJW=s680-w680-h510" alt="Instalação de máquinas e equipamentos industriais">
                    <div class="info">
                        <h3>Instalação de máquinas e equipamentos industriais</h3>
                        <a href="https://wa.me/551137205112" target="_blank" class="whatsapp-button">Clique aqui</a>
                    </div>
                </div>

                <!-- Card 2 -->
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipPiyqqHK2RmlOSWurkDDp_Rqb4JRKQqeUO3vHfe=s680-w680-h510" alt="Manutenção e reparação de máquinas e equipamentos para as indústrias de alimentos, bebidas e fumo">
                    <div class="info">
                        <h3>Manutenção e reparação de máquinas e equipamentos para as indústrias de alimentos, bebidas e fumo</h3>
                        <a href="https://wa.me/551137205112" target="_blank" class="whatsapp-button">Clique aqui</a>
                    </div>
                </div>

                <!-- Card 3 -->
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipOGWJR9RnIR5msvwBrCrASmWJbVYKmgObLaiveJ=s680-w680-h510" alt="Manutenção e reparação de máquinas e equipamentos de terraplenagem, pavimentação e construção, exceto tratores">
                    <div class="info">
                        <h3>Manutenção e reparação de máquinas e equipamentos de terraplenagem, pavimentação e construção, exceto tratores</h3>
                        <a href="https://wa.me/551137205112" target="_blank" class="whatsapp-button">Clique aqui</a>
                    </div>
                </div>

                <!-- Card 4 -->
                <div class="card">
                    <img src="https://lh3.googleusercontent.com/p/AF1QipPc8VGvs2GdvaKOL6lpHLHiyASlzFEnNRq93aPz=s680-w680-h510" alt="Serviços de operação e fornecimento de equipamentos para transporte e elevação de cargas e pessoas para uso em obras">
                    <div class="info">
                        <h3>Serviços de operação e fornecimento de equipamentos para transporte e elevação de cargas e pessoas para uso em obras</h3>
                        <a href="https://wa.me/551137205112" target="_blank" class="whatsapp-button">Clique aqui</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Seção Contato -->
        <section id="contato">
            <h2>Contato</h2>
            <p>Telefone: (64) 99947-4333</p>
            <p>Email: borgeseborgesmontagens@gmail.com</p>
            <a href="https://www.instagram.com/bbm.montagens?igsh=MWp6OGQxODY0enJybA==" target="_blank" class="instagram-link">
                <i class="fab fa-instagram"></i> Siga-nos no Instagram
            </a>
        </section>

        <!-- Seção Trabalhe Conosco -->
        <section id="trabalhe-conosco">
            <h2>Trabalhe Conosco</h2>
            <form action="/enviar-curriculo" method="post" enctype="multipart/form-data">
                <label for="nome">Nome:</label><br>
                <input type="text" id="nome" name="nome" required><br><br>

                <label for="email">E-mail:</label><br>
                <input type="email" id="email" name="email" required><br><br>

                <label for="telefone">Telefone:</label><br>
                <input type="tel" id="telefone" name="telefone"><br><br>

                <label for="curriculo">Anexar Currículo:</label><br>
                <input type="file" id="curriculo" name="curriculo" accept=".pdf,.doc,.docx" required><br><br>

                <input type="submit" value="Enviar Currículo">
            </form>
        </section>
    </main>

    <!-- Rodapé -->
    <footer>
        <p>&copy; 2025 BBM Montagens. Todos os direitos reservados. CNPJ 35.125.709/0001-06 - R. Rio Verde, 450 - Vila Maria, Rio Verde - GO, 75905-330</p>
        <img src="https://lh3.googleusercontent.com/a-/ALV-UjUMN7lAaTzddk4nHsG3Sc-s96E6EjNN3PrIjesQsWzZLbaGNkQ=w60-h60-p-rp-mo-br100" alt="Logo BBM MONTAGENS" class="footer-logo">  
    </footer>

    <!-- Botão "Voltar ao topo" -->
    <button id="btnTopo" title="Voltar ao topo" aria-label="Voltar ao topo"><i class="fas fa-arrow-up"></i></button>

    <!-- Script JavaScript -->
    <script src="scripts.js"></script>
</body>
</html>
