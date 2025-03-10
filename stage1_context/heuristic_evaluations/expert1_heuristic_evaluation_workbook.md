<!-- This Heuristic Evaluation Workbook replicates the one proposed by the 
Nielsen Norman Group available at: https://media.nngroup.com/media/articles/attachments/Heuristic_Evaluation_Workbook_-_Nielsen_Norman_Group.pdf
-->

**Evaluator**: Cristiana Rebelo
**Date**: [DD-MM-AAAA]
**Product**: [Site da Assembleia]

Severity Scale adopted: [[severity_scale_heuristic_evaluation]]
Summary of each usability heuristic: [here](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1-compressed.pdf)

# 1 Visibility of System Status
>	The design should always keep users informed about what is going on, through appropriate feedback within a reasonable amount of time. 
>	- Does the design clearly communicate its state?
>	- Is feedback presented quickly after user actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Ao pesquisar por "deputados", por exemplo,  e pressionar Enter, não ocorre nenhuma ação.  | 4            | Implementar feedback imediato ao pressionar Enter, como uma mensagem de "Carregando..." ou redirecionamento para a página de resultados. Isso informa ao usuário que a ação foi reconhecida pelo sistema.                        |
| Falta de feedback visual durante o carregamento das páginas.  | 3                       |Adicionar uma "progress bar" ou indicador de carregamento para informar ao usuário que a página está sendo carregada. Isso melhora a percepção do status do sistema e a experiência do usuário.                 |

# 2 Match Between System and The Real World
>	The design should speak the users' language. Use words, phrases, and concepts familiar to the user, rather than internal jargon. Follow real-world conventions, making information appear in a natural and logical order. 
>	- Will user be familiar with the terminology used in the design? 
>	- Do the design’s controls follow real-world conventions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|O site não utiliza ícones para representar funções comuns (como envio de e-mail). | 2            | Adicionar ícones intuitivos e amplamente reconhecidos (como um envelope para e-mail) para funções comuns, seguindo convenções do mundo real. Isso torna a interface mais familiar e fácil de entender               |
|Dificuldade em encontrar informações importantes, causando desorientação. | 3            | Organizar o conteúdo de forma mais intuitiva, utilizando menus claros, breadcrumbs (migalhas de pão) e uma barra de pesquisa eficiente. Isso ajuda os usuários a se localizarem e encontrarem o que precisam.       |

# 3 User Control and Freedom
>	Users often perform actions by mistake. They need a clearly marked "emergency exit" to leave the unwanted action without having to go through an extended process. 
>	- Does the design allow users to go back a step in the process? 
>	- Are exit links easily discoverable? 
>	- Can users easily cancel an action? 
>	- Is Undo and Redo supported?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|  Caso um e-mail inválido seja enviado, as informações preenchidas são mantidas, mas não há opção de voltar à página anterior. | 1            | Adicionar um botão "Voltar" ou "Cancelar" claramente visível, permitindo que o usuário retorne à página anterior sem perder as informações preenchidas.                              |

# 4 Consistency and Standards
>	Users should not have to wonder whether different words, situations, or actions mean the same thing. Follow platform and industry conventions. 
>	- Does the design follow industry conventions? 
>	- Are visual treatments used consistently throughout the design?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| A barra de navegação superior não é facilmente visível.                   | 3            | Melhorar a visibilidade da barra de navegação, posicionando-a de forma destacada                                                                   |
| Páginas com designs diferentes.   | 4            |Padronizar o design das páginas, garantindo consistência visual e funcional em todo o site. Isso inclui cores, fontes, layouts e comportamentos de elementos.                                                      |
# 5 Error Prevention
>	Good error messages are important, but the best designs carefully prevent problems from occurring in the first place. Either eliminate error-prone conditions, or check for them and present users with a confirmation option before they commit to the action. 
>	- Does the design prevent slips by using helpful constraints? 
>	- Does the design warn users before they perform risky actions?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O sistema permite que e-mails inexistentes sejam enviados sem verificação. | 4           |Implementar uma verificação automática de e-mails válidos antes de permitir o envio. Isso evita erros e garante que os usuários não enviem mensagens para endereços inexistentes.                 |
| Não há um botão "tem a certeza do envio deste mail", manda sem perguntar   | 4            | Meter um botão antes do envio do mail. Isso previne erros acidentais e dá ao usuário a chance de cancelar a ação.                   |
# 6 Recognition Rather than Recall
>	Minimize the user's memory load by making elements, actions, and options visible. The user should not have to remember information from one part of the interface to another. Information required to use the design (e.g. field labels or menu items) should be visible or easily retrievable when needed. 
>	- Does the design keep important information visible, so that users do not have to memorize it? 
>	- Does the design offer help in-context?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Pesquisar "contactos" não leva diretamente à página correspondente. | 3            | Melhorar a funcionalidade de pesquisa para direcionar os usuários diretamente às páginas relevantes (ex: "contactos" deve levar à página de contatos).                                                                |

# 7 Flexibility and Efficiency of Use
>	Shortcuts — hidden from novice users — may speed up the interaction for the expert user such that the design can cater to both inexperienced and experienced users. Allow users to tailor frequent actions. 
>	- Does the design provide accelerators like keyboard shortcuts and touch gestures? 
>	- Is content and funtionality personalized or customized for individual users?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| O site não possui atalhos ou métodos rápidos para acessar informações. | 2           | Adicionar atalhos de teclado ou links rápidos para páginas frequentemente acessadas (ex: "Deputados", "Agenda", "Contactos").                                                                                  |
# 8 Aesthetic and Minimalist Design
>	Interfaces should not contain information that is irrelevant or rarely needed. Every extra unit of information in an interface competes with the relevant units of information and diminishes their relative visibility. 
>	- Is the visual design and content focused on the essentials? 
>	- Have all distracting, unnescessary elements been removed?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Páginas densas, como "Serviços da Assembleia da República". | 3            |Simplificar o layout, utilizando técnicas como flashcards, listas com espaçamento adequado e hierarquia visual clara.                                                                                               |
# 9 Help Users Recognize, Diagnose, and Recover from Errors
>	Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution. 
>	- Does the design use traditional error message visuals, like bold, red text? 
>	- Does the design offer a solution that solves the error immediately?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
| Mensagens de erro pouco informativas, especialmente no envio de e-mails | 3            | Melhorar as mensagens de erro, utilizando linguagem clara e sugestões construtivas (ex: "O e-mail inserido é inválido. Por favor, verifique o endereço e tente novamente.")               |

# 10 Help and Documentation
>	It’s best if the system doesn’t need any additional explanation. However, it may be necessary to provide documentation to help users understand how to complete their tasks. 
>	- Is help documentation easy to search? 
>	- Is help provided in context right at the moment when the user requires it?

| **Issue**       | **Severity** | Recommendation |
| --------------- | ------------ | -------------- |
|  Falta de botão de ajuda ou seção de FAQ.    | 2            | Adicionar uma seção de FAQ ou um botão de ajuda contextual, especialmente para funcionalidades complexas                                |
