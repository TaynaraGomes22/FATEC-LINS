# Documentação do Projeto – ADS 1º Semestre
Este arquivo contém as informações sobre o projeto desenvolvido no primeiro semestre do curso de Análise e Desenvolvimento de Sistemas da FATEC Lins.EcoFoco+ – Plataforma de Prevenção e Controle da Dengue 

O EcoFoco+ é um projeto desenvolvido com o objetivo de combater o mosquito Aedes aegypti e suas doenças associadas, como a dengue, zika e chikungunya, por meio da conscientização, denúncias da população e atuação de agentes e gestores públicos. 

 Funcionalidades 

 Acesso por Perfil 

Cidadão: pode acessar o site, visualizar dicas de prevenção e enviar denúncias de possíveis focos de dengue com texto e mídia (imagem ou vídeo). 

Agente: realiza login para registrar visitas domiciliares com formulário detalhado (endereço, focos, moradores, recusa, observações). 

Gestor: (em desenvolvimento) acessa relatórios e acompanha o desempenho das ações dos agentes. 

 Páginas 

index.html: Página principal com: 

Carrossel de dicas ilustradas 

Formulário de denúncia pública 

Informações educativas sobre a dengue 

Mapa de calor (Google Maps embed) 

Frase de impacto e descrição do projeto 

Modo escuro e responsivo 

Rodapé com menu rápido 

main-login.html: Tela de login para perfis de agente e gestor, com redirecionamento para suas respectivas páginas. 

main-cadastro.html: Tela de cadastro para agentes e gestores, com validação e redirecionamento conforme o perfil selecionado. 

agente.html: Página do Agente com: 

Registro de visitas (formulário completo) 

Mapa de visitas com Google Maps embed 

Simulação de relatório diário automático (para futura integração com gestor) 

gestor.html: Página do Gestor (em desenvolvimento) 

 

Estrutura do Projeto 

├── index.html                ← Página principal do site (Cidadão) 

├── main-login.html          ← Tela de login para Agente e Gestor 

├── main-cadastro.html       ← Tela de cadastro de Agente e Gestor 

├── agente.html              ← Área restrita para o Agente de Saúde 

├── gestor.html              ← Área restrita para o Gestor (ainda em construção) 

├── README.md                ← Documentação do projeto (esse arquivo) 

├── topo1.png                ← Logo do projeto (utilizado no topo das telas) 

├── carrosel1.jpg            ← Imagem de dica no carrossel (ex: "Fale com os vizinhos") 

├── carrosel2.jpg            ← Imagem de dica no carrossel (ex: "Tampe caixas d'água") 

├── carrosel3.jpg            ← Imagem de dica no carrossel (ex: "Calhas limpas") 

├── carrosel4.jpg            ← Imagem de dica no carrossel (ex: "Eliminar água parada")

