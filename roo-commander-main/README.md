# 📚 Comandante de Estudos ANATEL 2025

O Comandante de Estudos ANATEL 2025 é um framework especializado, adaptado do Roo Commander, projetado para otimizar sua preparação para o concurso da ANATEL 2025. Focado em candidatos com TDAH (tipo desatento), ele utiliza uma abordagem **multiagente** para transformar a complexa tarefa de estudo em atividades gerenciáveis e estruturadas. Com agentes de IA especializados, ele auxilia na criação de materiais de estudo, acompanhamento do progresso e manutenção do foco, garantindo acessibilidade e clareza.

---

**🎯 Foco:** Preparação para o concurso ANATEL 2025, com adaptações para TDAH.

---

## O que é o Comandante de Estudos ANATEL 2025?

Baseado no robusto framework Roo Commander, esta adaptação direciona o foco do desenvolvimento de software para a **preparação educacional**. Ele se alinha ao conteúdo programático da ANATEL 2025 e incorpora estratégias amigáveis ao TDAH, abordando os desafios do estudo complexo através de:

*   **Agentes Especializados:** Delegação de tarefas de estudo a agentes de IA com expertise específica (ex: Resumidor de Conteúdo, Criador de Flashcards, Gerador de Simulados).
*   **Fluxo de Trabalho Estruturado:** Organização de materiais de estudo e progresso em um sistema claro e rastreável.
*   **Gerenciamento de Contexto:** Manutenção de um registro do que foi estudado e do que precisa de atenção.
*   **Artefatos Estruturados:** Utilização de formatos padronizados (TOML+Markdown) e um diário de estudo (`.ruru/tasks/`, `.ruru/decisions/`, etc.) para manter o estado e a história do estudo.
*   **Consistência:** Garantia de que todos os materiais sigam diretrizes de acessibilidade e formatos padronizados.

O objetivo é trazer estrutura, consistência, rastreabilidade e o poder de habilidades de IA especializadas para o seu processo de preparação para concursos.

## Por que usar o Comandante de Estudos ANATEL 2025?

*   **🧠 Expertise Especializada:** Agentes de IA lidam com tarefas específicas como resumir conteúdo, criar flashcards ou gerar simulados.
*   **🏗️ Fluxo de Trabalho Estruturado:** Organiza materiais de estudo e progresso em um sistema claro e rastreável.
*   **💾 Gerenciamento de Contexto Aprimorado:** Mantém um registro do que você estudou e do que precisa de atenção.
*   **🔍 Rastreabilidade:** Registra decisões de estudo e tarefas para fácil revisão.
*   **⚙️ Consistência:** Garante que todos os materiais sigam diretrizes de acessibilidade e formatos padronizados.
*   **🚀 Automação:** Economiza tempo automatizando tarefas repetitivas como a criação de flashcards.
*   **🧘 Adaptação para TDAH:** Incorpora funcionalidades e diretrizes para auxiliar no foco, agendamento de pausas e acessibilidade dos materiais.

## Conceitos Principais

Compreender estes conceitos é fundamental para usar o Comandante de Estudos ANATEL 2025:

1.  **Sistema Multiagente:**
    *   **Funções:** Inclui um Coordenador de Estudos (gerenciamento geral) e especialistas como Resumidor de Conteúdo, Criador de Flashcards e Gerador de Simulados.
    *   **Delegação:** O Coordenador de Estudos interpreta seus objetivos e atribui tarefas aos agentes corretos usando a ferramenta `new_task`.
    *   **(Veja `.ruru/modes/study-coordinator/kb/kb-available-modes-summary.md` para um resumo dos modos disponíveis).**

2.  **Artefatos de Estudo Estruturados (TOML+Markdown):**
    *   **Pastas Padrão:** Usa diretórios ocultos como `.ruru/summaries`, `.ruru/flashcards`, `.ruru/practice_exams`, `.ruru/mind_maps`, `.ruru/infographics`, `.ruru/checklists`, `.ruru/study_guide`, `.ruru/tasks`, `.ruru/decisions`, `.ruru/workflows` para armazenar materiais e registros.
    *   **Formato TOML+MD:** Combina metadados TOML (para status, IDs, tags, etc.) com conteúdo Markdown legível por humanos. Garante consistência e facilita o processamento automatizado.

3.  **Bases de Conhecimento (KB) e Regras:**
    *   **Regras:** Definem a lógica operacional e procedimentos para cada agente (ex: como formatar resumos, quais campos incluir em flashcards).
    *   **Bases de Conhecimento (`.ruru/modes/<slug>/kb/`):** Contêm informações de referência detalhadas, procedimentos complexos, modelos e exemplos específicos para cada modo. São consultadas sob demanda para fornecer orientação detalhada.

## Funcionalidades Chave

*   **📚 Coordenação Central:** O Coordenador de Estudos supervisiona seu processo de preparação.
*   **🚦 Integração de Estudo:** Configura seu ambiente de estudo e tarefas iniciais.
*   **📋 Gerenciamento de Tarefas:** Acompanha metas de estudo e progresso em `.ruru/tasks/`.
*   **📖 Gerenciamento de Contexto:** Monitora o que foi coberto e o que vem a seguir.
*   **🛠️ Modos Especialistas:** Agentes para resumir, criar flashcards, gerar simulados, acompanhar progresso e mais.
*   **📝 Registro de Decisões:** Registra estratégias de estudo em `.ruru/decisions/`.
*   **🧩 Fluxos de Trabalho Padronizados:** Processos reutilizáveis em `.ruru/workflows/` para preparação consistente.
*   **🧠 Funcionalidades Amigáveis ao TDAH:** Inclui Potenciador de Foco, Agendador de Pausas e diretrizes para Materiais Estruturados Acessíveis.

## Começando (Instalação)

**Pré-requisito:** Você precisa da extensão [Roo Code](https://marketplace.visualstudio.com/items?itemName=RooCode.roo-code) para VS Code instalada.

O método de instalação recomendado utiliza a estrutura de arquivos já refatorada:

1.  **Clone ou Baixe:** Obtenha os arquivos deste repositório/projeto.
2.  **Configure o Workspace:** Abra a pasta raiz deste projeto (`/home/eu/Documentos/anatel/roo-commander-main`) no VS Code.
3.  **Recarregue o VS Code:** Recarregue a janela (`Ctrl+Shift+P` ou `Cmd+Shift+P` -> "Developer: Reload Window") para garantir que o Roo Code reconheça as novas configurações de modo no arquivo `.roomodes`.

Esta configuração já inclui as pastas ocultas necessárias (`.ruru/modes`, `.roo`, `.ruru/templates`, etc.) e o arquivo `.roomodes` configurado.

## Uso Básico

1.  **Ative o Coordenador de Estudos:** Selecione o modo "📚 Coordenador de Estudos" na interface de chat do Roo Code.
2.  **Declare seu Objetivo:** Diga ao Coordenador o que você deseja estudar ou criar (Ex: "Criar resumos para Língua Portuguesa", "Gerar um simulado de Matemática", "Criar flashcards sobre Direito Administrativo").
3.  **Interaja:** Siga as orientações do Coordenador. Ele poderá:
    *   Fazer perguntas para esclarecer seu objetivo.
    *   Propor um plano de estudo ou fluxo de trabalho.
    *   Delegar tarefas para os agentes especialistas (usando `<new_task>`).
    *   Pedir sua aprovação ou feedback sobre as etapas ou resultados.
4.  **Revise:** Verifique os arquivos criados ou modificados pelos agentes, especialmente nas subpastas dentro de `.ruru/`, para acompanhar o progresso e revisar os materiais de estudo.

## Contribuições

Contribuições são bem-vindas! Se você tiver ideias para novos agentes especialistas, melhorias nas KBs, ou adaptações para outras áreas de estudo, sinta-se à vontade para propor.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](./LICENSE) para detalhes.

---

Prepare-se de forma inteligente e estruturada para a ANATEL 2025!
