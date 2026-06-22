# -Projeto_Agrinho_3B
Projeto 2026 dos estudantes da turma do 3B do Colégio Padre José de Anchieta, desenvolvido pelos estudantes em equipe. # 💧 Gota Invisível | Consumo & Redução da Água Virtual

Uma landing page minimalista e de impacto desenvolvida para explorar o conceito de Água Virtual e da Pegada Hídrica oculta em nossos hábitos de consumo. O projeto equilibra um design editorial refinado com uma suíte nativa de ferramentas voltadas para a acessibilidade digital e inclusão.

---
🎯 Objetivo do Projeto

Conscientizar o público em geral sobre o volume invisível de água consumido na cadeia de suprimentos global (alimentos, vestuário, tecnologia). O site funciona como uma ferramenta educacional interativa, garantindo que usuários com diferentes capacidades visuais ou motoras consumam o conteúdo de forma fluida e autônoma.

---
🛠️ Recursos Técnicos
### ♿ Hub de Acessibilidade (Custom JS)
Um painel fixo e expansível gerencia a experiência do usuário de forma 100% dinâmica através de JavaScript Vanilla:
Controle de Fonte Real-time: Ajuste de escala proporcional (de 0.75rem a 1.5rem) via injeção de variáveis CSS Custom Properties (--text-base-scale), sem quebrar o layout adaptável.
Dark Mode & Alto Contraste: Chaveamento da classe .dark no elemento raiz da árvore DOM, invertendo paletas de cores do Tailwind e aplicando filtros para maior conforto visual e acessibilidade para pessoas com baixa visão.
Text-to-Speech (Leitura de Voz Integrada): Uso nativo da Web Speech API (SpeechSynthesisUtterance). O script faz a raspagem semântica sequencial de títulos, parágrafos e tabelas de dados, narrando o conteúdo de maneira fluida e pausada em português brasileiro, eliminando barreiras para pessoas cegas ou com dislexia

### 🎨 UI/UX & Design Editorial
Design Responsivo Avançado: Estruturação fluida construída sobre o motor do Tailwind CSS, garantindo adaptabilidade perfeita desde smartphones pequenos a displays ultrawide.
Scroll Animations nativas: Efeito suave de subida e revelação dos blocos estruturais ativado dinamicamente conforme a rolagem do usuário via Intersection Observer API, poupando performance por não utilizar bibliotecas externas de animação pesadas.
Tipografia Editorial: Contraste sofisticado entre a fonte serifada clássica (Playfair Display) aplicada em títulos/destaques e a fonte sans-serif limpa (Inter) para o corpo do texto, priorizando máxima legibilidade.

###🚀 Tecnologias Utilizadas
Estrutura: HTML5 Semântico (<header>, <section>, <nav>, <table>, etc.).
Estilização: Tailwind CSS v3 (Via CDN integrado com configurações extendidas de cores customizadas).
Tipografia: Google Fonts API.
Interatividade & Lógica: JavaScript Vanilla assíncrono (ES6+).
Mídia: Banco de Imagens Unsplash (Otimizado via URLs parametrizadas com textos alternativos alt detalhados para leitores de tela).


### 📁 Estrutura de Arquivos
| Pasta/Arquivo | Descrição |
|---------------|----------------------------------------------------|
| `index.html` | Código-fonte principal unificado (Estrutura estrutural, folhas de estilo locais e regras de lógica JavaScript). |
| `README.md` | Documentação técnica descritiva e guia estrutural do projeto.
