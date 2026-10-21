# Rede AJAA - Plataforma Web de Doações e Solidariedade

A Rede AJAA é um projeto integrador focado no desenvolvimento de um sistema de doações solidárias, permitindo que pessoas físicas e instituições privadas se cadastrem para realizar doações a abrigos, igrejas, hospitais e outras organizações. A plataforma inclui recursos como mapa para visualização de ONGs próximas, um dashboard com sistema de selos para doações, acúmulo de pontos e uma área dedicada a campanhas emergenciais.

O projeto concluiu sua fase de UX/UI Design, contemplando a criação de histórias de usuários, personas, tipografia e wireframes de baixa fidelidade. O próximo passo é a implementação do front-end utilizando HTML, CSS e JavaScript.

📁 **[Acesse a pasta no Google Drive com a documentação completa aqui](https://drive.google.com/drive/folders/1oRopO0ncEa8BTYBUqWsqi8qEVGW3Tktm?usp=sharing)**

---

## 👥 Perfis de Usuário (Personas)

O ecossistema da Rede AJAA foi projetado para atender três personas principais, garantindo que a interface se adapte às necessidades de cada perfil no momento do login:

*   **Pessoa Física (Luana Álvarez):** Doadora que busca instituições próximas utilizando seu CEP ou geolocalização, filtrando as necessidades das ONGs pelo tipo de item que tem disponível em casa, como roupas, alimentos, cobertores e produtos de higiene.
*   **Empresa Doadora (Boa Vista Confecções):** Indústria ou comércio que utiliza a plataforma para registrar doações em lote de itens volumosos ou excedentes de produção, combinando a logística de retirada/entrega e acompanhando relatórios e comprovantes para prestação de contas e responsabilidade social.
*   **Instituição Solicitante (Abrigo Esperança):** Organização social sem fins lucrativos que passa por uma verificação documental (CNPJ e estatuto) para receber o selo de "instituição verificada". A instituição gerencia seu painel para publicar necessidades, lançar campanhas emergenciais, aceitar intenções de doação e emitir recibos para empresas parceiras.

---

## 🛠️ Principais Funcionalidades Projetadas

*   **Login Contextual:** A tela de entrada permite que o usuário escolha seu perfil ("Quero doar", "Sou empresa" ou "Sou instituição"), adaptando as funções do sistema à sua escolha.
*   **Busca e Filtros Inteligentes:** Mapeamento de instituições próximas ao usuário, destacando a distância, a categoria dos itens necessários e selos de verificação, reduzindo o esforço de memorização e navegação.
*   **Gestão de Campanhas Emergenciais:** Espaço dedicado para situações de calamidade (ex: enchentes), com barras de progresso informando metas de itens arrecadados e contagem regressiva de dias.
*   **Intenção de Doação e Logística:** Doadores podem sinalizar exatamente o que vão doar e quando. Empresas podem especificar volumes maiores (ex: caixas grandes) e solicitar que a instituição retire os itens na sede.
*   **Painel Administrativo da ONG:** Interface para a instituição marcar itens como "já supridos", reabrir necessidades, confirmar o recebimento físico das doações e gerar PDFs de comprovantes corporativos com um clique.

---

## 🖼️ Wireframes de Baixa Fidelidade

Abaixo estão as prévias da estrutura visual e da arquitetura de informação planejada para a plataforma:

### Tela de Login e Escolha de Perfil
![Wireframe - Login e Cadastro](wiframes-images/Tela%2001-%20Entrar.png)
> A interface destaca as opções de perfis com ícones claros ("Quero doar", "Sou empresa", "Sou instituição") para direcionar a experiência do usuário.

### Encontrar Instituições (Visão do Doador)
![Wireframe - Encontrar Instituições](wiframes-images/Tela%2002-Encontrar%20instituições.png)
> Lista minimalista de ONGs com informações essenciais: nome, selo de verificação, distância do usuário e lista de necessidades atuais filtradas por categoria.

### Campanhas Emergenciais
![Wireframe - Campanhas Emergenciais](wiframes-images/Tela%207%20-%20Campanhas%20de%20Emergência.png)
> Cards de campanhas destacando a urgência através de etiquetas vermelhas, metas de arrecadação em barra de progresso e botões diretos de ação.

### Painel da Instituição - Doações Recebidas
![Wireframe - Doações Recebidas](wiframes-images/TELA%2012.png)
> Dashboard com abas para gerenciar doações pendentes, confirmadas e recebidas, além da funcionalidade de gerar comprovantes em PDF para as empresas doadoras.


### Para acessar as demais páginas do Wiframe, clique no link do Google Drive que contam com a documentação completa e telas do projeto
---

## 🚀 Próximos Passos (Desenvolvimento)

Com a arquitetura de informação e a experiência do usuário (UX) consolidadas, o projeto avançará para as seguintes etapas de desenvolvimento:
1.  Estruturação semântica do layout utilizando **HTML5**.
2.  Estilização da interface, garantindo responsividade e aplicação da identidade visual desenvolvida (Cores, Tipografia) utilizando **CSS3**.
3.  Implementação de interatividade, validação de formulários (ex: máscara automática de CNPJ) e navegação entre abas utilizando **JavaScript**.