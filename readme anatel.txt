📚 Comandante de Estudos ANATEL 2025
Introdução
Bem-vindo ao Comandante de Estudos ANATEL 2025, um framework especializado projetado para otimizar sua preparação para o concurso da ANATEL 2025. Adaptado especificamente para candidatos com TDAH (tipo desatento), esta ferramenta utiliza uma abordagem multiagente para dividir a tarefa complexa de preparação para o exame em atividades gerenciáveis e estruturadas. Usando agentes de IA especializados, ele ajuda você a criar materiais de estudo, acompanhar o progresso e manter o foco — tudo isso garantindo acessibilidade e clareza.
Baseado no framework Roo Commander, esta adaptação muda o foco do desenvolvimento de software para a preparação educacional, alinhando-se ao conteúdo programático da ANATEL 2025 e incorporando estratégias amigáveis ao TDAH.
Por que usar o Comandante de Estudos ANATEL 2025?
* 🧠 Expertise Especializada: Agentes de IA lidam com tarefas específicas como resumir conteúdo, criar flashcards ou gerar simulados.
* 🏗️ Fluxo de Trabalho Estruturado: Organiza materiais de estudo e progresso em um sistema claro e rastreável.
* 💾 Gerenciamento de Contexto Aprimorado: Mantém um registro do que você estudou e do que precisa de atenção.
* 🔍 Rastreabilidade: Registra decisões de estudo e tarefas para fácil revisão.
* ⚙️ Consistência: Garante que todos os materiais sigam diretrizes de acessibilidade e formatos padronizados.
* 🚀 Automação: Economiza tempo automatizando tarefas repetitivas como a criação de flashcards.
Conceitos Principais
1. Sistema Multiagente:
   * Funções: Inclui um Coordenador de Estudos (gerenciamento geral) e especialistas como Resumidor de Conteúdo, Criador de Flashcards e Gerador de Simulados.
   * Delegação: O Coordenador de Estudos interpreta seus objetivos e atribui tarefas aos agentes corretos.
2. Artefatos de Projeto Estruturados:
   * Pastas: Usa diretórios como .ruru/summaries/, .ruru/flashcards/ e .ruru/practice_exams/ para armazenar materiais.
   * Formato: Combina metadados TOML com conteúdo Markdown para legibilidade por máquina e clareza humana.
3. Bases de Conhecimento e Regras:
   * Regras: Definem como cada agente cria materiais (ex: resumos concisos, flashcards acessíveis).
   * Bases de Conhecimento (KB): Localizadas em .ruru/modes/[mode-slug]/kb/, fornecem diretrizes detalhadas e exemplos para cada tarefa.
Funcionalidades Chave
* 📚 Coordenação Central: O Coordenador de Estudos supervisiona seu processo de preparação.
* 🚦 Integração de Estudo: Configura seu ambiente de estudo e tarefas iniciais.
* 📋 Gerenciamento de Tarefas: Acompanha metas de estudo e progresso em .ruru/tasks/.
* 📖 Gerenciamento de Contexto: Monitora o que foi coberto e o que vem a seguir.
* 🛠️ Modos Especialistas: Agentes para resumir, criar flashcards, gerar simulados, acompanhar progresso e mais.
* 📝 Registro de Decisões: Registra estratégias de estudo em .ruru/decisions/.
* 🧩 Fluxos de Trabalho Padronizados: Processos reutilizáveis em .ruru/workflows/ para preparação consistente.
Começando
1. Instale o Roo Code: Certifique-se de que a extensão Roo Code está instalada no VS Code.
2. Configure o Workspace: Coloque os arquivos de configuração (incluindo roomodes.txt) na raiz do seu workspace do VS Code.
3. Recarregue o VS Code: Recarregue a janela (Ctrl+Shift+P ou Cmd+Shift+P -> "Developer: Reload Window") para carregar os modos.
Uso Básico
1. Ative o Coordenador de Estudos: Selecione "📚 Study Coordinator" no Roo Code.
2. Declare seu Objetivo: Ex: "Criar resumos para Língua Portuguesa" ou "Gerar um simulado de Matemática."
3. Siga as Orientações: O Coordenador delega tarefas e atualiza você sobre o progresso.
4. Revise os Materiais: Encontre os resultados nas subpastas .ruru/ (ex: .ruru/summaries/).
Exemplo de Fluxo de Trabalho
* Você: "Gerar flashcards para Noções de Direito."
* Coordenador de Estudos: Delega para o Criador de Flashcards.
* Criador de Flashcards: Produz os cartões e os salva em .ruru/flashcards/direito.md.
* Coordenador de Estudos: Notifica você quando estiver pronto.
Funcionalidades Amigáveis ao TDAH
* Potenciador de Foco: Oferece estratégias como Pomodoro e dicas sem distrações.
* Agendador de Pausas: Lembra você de fazer pausas regulares.
* Materiais Estruturados: Todos os resultados usam fontes claras (Arial/Verdana, 12-14pt), espaçamento 1.5 e alto contraste.
* Guia de Estudo Personalizado: Adapta-se aos seus pontos fortes e fracos com base nos resultados dos simulados.
Customização
* Ajuste as Bases de Conhecimento: Modifique .ruru/modes/[mode-slug]/kb/ para ajustar as regras de criação de material.
* Adicione Modos: Defina novos agentes em roomodes.txt para tarefas adicionais.
Comece sua preparação para a ANATEL 2025 com confiança e estrutura!