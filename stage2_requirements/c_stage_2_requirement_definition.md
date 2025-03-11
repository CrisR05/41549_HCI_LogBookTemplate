[Back to main Logbook Page](../hci_logbook.md)

---
# C. Requirement Definition
>	Based on all the gathered context, including an understanding of current practices, competitors, and user feedback and expectations: 
>	- summarize the user characteristics, context, and motivations using Personas
>	- explain your vision for a novel solution that will target user motivations using Scenarios
>	- identify requirements

# Personas

## Persona: [Carolina Mendes] 
### Summary 
| Attribute        | Details                                         |
| ---------------- | ---------------------------------------------   |
| **Photo**        | ![Carolina Mendes\|100](personas/persona1.png)  |
| **Name**         | Carolina Mendes                             |
| **Age**          | 18                                           |
| **Occupation**   | Estudante de Relações Internacionais                          |
| **Location**     | Lisboa, Portugal                              |
| **Goals**        | Construir uma base sólida de conhecimento político para acompanhar as aulas, participar ativamente em debates e preparar-se para uma carreira em Relações Internacionais.           |
| **Pain Points**  | Falta de base política, materiais de estudo complexos, falta de confiança em discussões, fontes de informação pouco confiáveis e tempo limitado.              |
| **Motivation**   | "Quero entender política de forma simples e clara, para não me sentir perdida nas aulas e poder participar nos debates sem medo."               |
| **Full Profile** | [📄 Read More](personas/persona1_template.md) |

---
## Persona: [Persona Name] 
### Summary 
| Attribute        | Details                                       |
| ---------------- | --------------------------------------------- |
| **Photo**        | ![Fernando Almeida](personas/persona2.png)            |
| **Name**         | Fernando Almeida                                |
| **Age**          | 56                               |
| **Occupation**   | Engenheiro Civil                          |
| **Location**     | Braga, Portugal                               |
| **Goals**        | Participar ativamente no processo eleitoral, integrando uma mesa de voto na sua freguesia, e contribuir para a transparência e eficiência do sistema democrático.           |
| **Pain Points**  | Falta de informação clara sobre como se inscrever, burocracia excessiva, falta de familiaridade com ferramentas digitais e tempo limitado.              |
| **Motivation**   | "Quero inscrever-me de maneira fácil e rápida, através de um site ou plataforma online, sem ter que andar de um lado para o outro a perguntar como se faz. Preciso de um processo simples e direto, que respeite o meu tempo e me permita contribuir sem complicações."                |
| **Full Profile** | [📄 Read More](personas/persona2_template.md) |

---





# Scenarios


## Scenario 1: Maria goes on a Museum Tour

[Maria had always loved modern art, but she often found museum visits overwhelming—so many exhibits, so much information, and little guidance on where to start. Today, she was visiting a contemporary art museum that had recently introduced an **interactive guide**.  ]

[As she entered the museum, Maria received a notification on her phone, reminding her to launch the app. She opened it and was greeted with a personalized welcome screen. The system, aware of her general interests in **digital media and abstract art**, suggested a self-guided tour tailored to her preferences.  ]

[Curious, Maria followed the suggested path. As she approached the first painting, the guide vibrated slightly—a prompt that additional content was available. Holding up the guide, she saw an **overlay** appear on the screen, revealing a time-lapse animation of the artist creating the piece. A small **audio clip** played, explaining the artist’s thought process and influences. Maria found this fascinating; it was as if the artwork was coming to life in front of her.  ]

[As she continued her tour, Maria **bookmarked** her favorite pieces, leaving notes about what she found intriguing. The system, recognizing her engagement, suggested another exhibit nearby featuring similar themes. Midway through her visit, she received a pop-up asking if she’d like a **short quiz** on the artworks she had explored, offering an interactive way to reflect on what she had learned.  ]

---


# Requirements





## C.1. Functional requirements

### 1. **Navegação e Estrutura do Menu**
   - Implementar um menu de navegação claro e intuitivo com as seguintes seções:
     - **Sobre (About):** Missão e equipa.
     - **Temas Políticos:** Explicações de conceitos políticos.
     - **Deputados:** Informações sobre deputados, seus papéis e atividades.
     - **Presidente e Primeiro-Ministro:** Perfis e atividades.
     - **Partidos Políticos:** Informações detalhadas sobre partidos.
     - **Constituição:** Acesso à Constituição portuguesa.
     - **História da Política:** Visão histórica da política portuguesa.
     - **Outros Assuntos:** Tópicos políticos adicionais.
     - **Contactar a Assembleia:** Formulário de contacto e informações.
     - **Notícias:** Informações atualizadas e imparciais sobre política.
     - **Como Votar:** Instruções sobre o processo eleitoral.
     - **Área de Discussão:** Fórum ou interação.
     - **Mesa de Voto:** Formulário de inscrição para mesas de voto.

### 2. **Deputados**
   - **FR1: Mapa Interativo de Deputados**
     - Exibir um mapa de Portugal dividido em distritos/regiões.
     - Permitir que os usuários cliquem em um distrito para ver os deputados que representam essa área.
     - Incluir filtros para partidos políticos.
   - **FR2: Perfis dos Deputados**
     - Mostrar perfis detalhados de cada deputado, incluindo:
       - Nome, foto e partido político.
       - Informações de contacto (e-mail, redes sociais, endereço do escritório).
       - Biografia (educação, carreira, histórico político).
       - Funções e responsabilidades atuais (por exemplo, comissões em que atuam).
       - Histórico de votação e propostas legislativas importantes.
       - Linha do tempo da carreira política do deputado, incluindo funções e conquistas passadas.
   - **FR4: Contactar um Deputado**
     - Permitir que os usuários enviem um e-mail através do site.

### 3. **Presidente e Primeiro-Ministro**
   - **FR5: Perfil do Presidente e do Primeiro-Ministro**
     - Incluir uma biografia, foto e histórico político de ambos.
     - Explicar os papéis e poderes do Presidente (por exemplo, poder de veto, nomeação do Primeiro-Ministro, representação externa do Estado).
     - Explicar os papéis e poderes do Primeiro-Ministro (por exemplo, liderança do governo, definição de políticas públicas, coordenação ministerial).
   - **FR6: Atividades do Presidente e do Primeiro-Ministro**
     - Fornecer atualizações sobre as funções oficiais de ambos, incluindo discursos, reuniões, e visitas internacionais.
     - Incluir um calendário de eventos futuros, destacando compromissos públicos e agendas oficiais.

### 4. **Partidos Políticos**
   - **FR8: Lista de Partidos**
     - Exibir todos os partidos políticos registados em Portugal.
     - Incluir um breve resumo da ideologia e posições-chave de cada partido.
   - **FR9: Perfis dos Partidos**
     - Fornecer perfis detalhados para cada partido, incluindo:
       - História e princípios fundadores.
       - Líderes e representantes principais.
       - Deputados atuais e seus distritos (vinculados à seção Deputados).
       - Resultados eleitorais e desempenho ao longo do tempo.
   - **FR10: Comparador de Partidos**
     - Permitir que os usuários comparem partidos com base em questões-chave (por exemplo, economia, meio ambiente, direitos sociais).
     - Usar recursos visuais como gráficos e tabelas para facilitar a compreensão.

### 5. **Constituição**
   - **FR11: Resumo da Constituição**
     - Fornecer um resumo simplificado e amigável para iniciantes dos principais artigos e princípios da Constituição.
     - Usar visuais e exemplos para explicar conceitos complexos.
   - **FR12: Texto Completo da Constituição**
     - Oferecer um PDF para download da Constituição completa.
     - Incluir uma versão pesquisável com links para artigos específicos.

### 6. **História da Política**
   - **FR13: Linha do Tempo da Política**
     - Criar uma linha do tempo interativa dos principais eventos políticos em Portugal (por exemplo, Revolução dos Cravos, adesão à UE).
     - Incluir resumos curtos, imagens e vídeos para cada evento.

### 7. **Outros Assuntos**
   - **FR15: Economia e Política Fiscal**
     - Explicar conceitos e políticas econômicas-chave em termos simples.
     - Incluir uma Calculadora de Impostos para ajudar os usuários a entender como as políticas os afetam.
   - **FR16: Direitos e Deveres dos Cidadãos**
     - Fornecer informações sobre os direitos e responsabilidades dos cidadãos sob a lei portuguesa.
   - **FR17: Política Internacional**
     - Cobrir o papel de Portugal em organizações internacionais (por exemplo, UE, ONU) e questões-chave de política externa.

### 8. **Contactar a Assembleia**
   - **FR18: Formulário de Contacto (Contact Form)**
     - Fornecer um formulário para os usuários enviarem perguntas ou feedback à Assembleia.
     - Incluir opções para perguntas gerais, solicitações de informações ou relatórios de problemas.
   - **FR19: Informações de Contacto (Contact Information)**
     - Exibir o endereço oficial, número de telefone e e-mail da Assembleia.
     - Incluir um mapa mostrando a localização do edifício da Assembleia.

### 9. **Notícias**
   - Fornecer informações atualizadas e imparciais sobre política, eleições e temas relevantes para os cidadãos.
     - Notícias diárias sobre atividades parlamentares, decisões governamentais e eventos políticos.
     - Análises neutras de especialistas sobre temas políticos e económicos.
     - Cobertura de eleições, incluindo resultados, debates e campanhas.
     - Destaques sobre políticas públicas e seu impacto na sociedade.
   - Funcionalidades:
     - Filtros por tema (ex.: economia, educação, saúde).
     - Opção de receber notificações por e-mail ou app sobre notícias importantes.
     - Integração com fontes confiáveis e verificadas para garantir imparcialidade.

### 10. **Como Votar**
   - Instruções para educar os cidadãos sobre o processo eleitoral e facilitar a participação nas eleições.
     - Guia passo a passo sobre como se registar para votar.
     - Informações sobre documentos necessários para votar (ex.: cartão de cidadão).
     - Localização de secções de voto (com mapa interativo).
     - Explicação dos diferentes tipos de eleições (ex.: legislativas, presidenciais, autárquicas).
   - Funcionalidades:
     - Ferramenta de busca por código postal para encontrar o local de voto.
     - Lembretes automáticos sobre datas eleitorais e prazos de registo.

### 11. **Área de Discussão (Fórum ou Interação)**
   - **Criação de Tópicos:** Os usuários devem poder criar tópicos de discussão, escolhendo categorias como "Política", "Eleições", "Economia", etc.
   - **Comentários e Respostas:** Os usuários devem poder comentar em tópicos existentes e responder a outros comentários.
   - **Sistema de Votos:** Os usuários devem poder votar (positivamente ou negativamente) em tópicos e comentários, destacando os mais relevantes.
   - **Notificações:** Os usuários devem receber notificações por e-mail ou no site quando houver novas respostas ou interações nos tópicos que participam.
   - **Perfis de Usuários:** Cada usuário deve ter um perfil público, onde pode ver seu histórico de participação no fórum (tópicos criados, comentários, etc.).
   - **Regras e Diretrizes:** Deve haver uma seção clara com as regras de uso do fórum, para garantir discussões respeitosas e produtivas.

### 12. **Mesa de Voto**
   - **Formulário básico com os seguintes campos:**
     - Nome completo.
     - E-mail.
     - Freguesia (pode ser um dropdown com as freguesias disponíveis).
     - Telefone (opcional, se quiserem contactar por SMS também).
   - **Funcionamento:**
     - A pessoa preenche o formulário e clica em "Enviar".
     - A freguesia recebe automaticamente os dados das pessoas inscritas (por e-mail ou acesso à base de dados).
     - A freguesia entra em contacto diretamente com a pessoa quando necessário.


## C.2. Non-functional requirements


---
[Back to main Logbook Page](hci_logbook.md)