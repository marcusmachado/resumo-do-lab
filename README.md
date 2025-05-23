# Resumo - Computação em Nuvem - Azure

## Módulo de Introdução

Definição de Computação em Nuvem: Introdução à computação em nuvem e sua relevância em ambientes de negócios modernos.

Modelos de Nuvem:
- Nuvem Pública: Serviços oferecidos por provedores como Microsoft Azure e AWS, acessíveis a múltiplos clientes.
- Nuvem Privada: Recursos dedicados a uma única organização, gerenciados internamente.
- Nuvem Híbrida: Combinação de nuvens públicas e privadas, permitindo o compartilhamento de recursos e flexibilidade.
- Multinuvem: Utilização de múltiplos serviços de nuvem de diferentes provedores.

Considerações de Custo: Discussão sobre modelos baseados em consumo e como os custos variam por localização e serviço.

Casos de Uso: Compreensão de quando os serviços de nuvem são benéficos, especialmente para startups e organizações com demandas flutuantes.

Criação Rápida de Recursos: Destaque para a agilidade de provisionar recursos na nuvem versus configurações tradicionais on-premise.

Necessidades de Gerenciamento: Ênfase em que pessoal qualificado é essencial para gerenciar recursos de nuvem de forma eficaz.



## Módulo Tipos de Serviço de Nuvem

Este tópico se concentra em explicar os três principais modelos de serviço de nuvem: Infraestrutura como Serviço (IaaS), Plataforma como Serviço (PaaS) e Software como Serviço (SaaS). Ele destaca os diferentes níveis de responsabilidade entre o provedor e o usuário, onde o IaaS oferece o maior controle e responsabilidade, o PaaS abstrai parte disso e o SaaS assume total responsabilidade pela infraestrutura e software. O palestrante enfatiza casos de uso práticos para cada modelo, ajudando os espectadores a entender quando escolher cada serviço com base em suas necessidades e estrutura organizacional, com foco em simplicidade e eficiência.

Introduz o conceito de computação em nuvem, focando em diferentes modelos de serviço de nuvem: IaaS, PaaS e SaaS. Explica o modelo de responsabilidade compartilhada, onde algumas responsabilidades são do provedor de nuvem e outras do usuário.
- O IaaS (Infraestrutura como Serviço) oferece o maior controle para os usuários, permitindo que eles gerenciem máquinas virtuais e configurem recursos como backup, acesso e rede. No IaaS, os usuários estão profundamente envolvidos na configuração, monitoramento e gerenciamento de recursos, tornando-o um modelo prático.
- O PaaS (Plataforma como Serviço) abstrai a infraestrutura subjacente, permitindo que os usuários se concentrem no desenvolvimento de aplicativos sem se preocupar com a manutenção do sistema ou hardware. A transição do IaaS para o PaaS permite que os usuários se concentrem menos em servidores e sistemas operacionais e mais no gerenciamento de bancos de dados e aplicativos.
- O SaaS (Software como Serviço) entrega aplicativos totalmente funcionais hospedados pelo provedor, com os usuários interagindo principalmente com o software sem precisar gerenciar servidores ou configurações de sistema. Com o SaaS, os usuários pagam por uma licença de software específica e experimentam diferentes níveis de recursos, dependendo do nível da licença, como o Microsoft Teams no pacote Microsoft 365. Os modelos SaaS lidam com quase todas as responsabilidades, e os usuários só precisam configurar o acesso do usuário, funções e grupos.

Portanto, enfatiza que o nível de responsabilidade diminui à medida que passamos de IaaS para PaaS para SaaS, sendo o SaaS o que exige o menor envolvimento do usuário na infraestrutura subjacente.



## Módulo Componentes de Arquitetura

O módulo se concentra em aspectos chave como regiões do Azure, zonas de disponibilidade, assinaturas e grupos de recursos, oferecendo uma compreensão mais profunda de como os recursos do Azure são estruturados. Exploramos computação, rede, armazenamento e soluções baseadas na nuvem, discutindo os prós e contras de usar servidores versus armazenamento em nuvem. Além disso, a sessão aborda modelos de identidade e segurança, conformidade e gerenciamento de permissões, enfatizando a responsabilidade compartilhada na segurança da nuvem. Laboratórios práticos também guiarão os alunos na criação de máquinas virtuais e redes, preparando-os para aplicações Azure no mundo real.

O tópico está focado em arquitetura e serviços dentro do Azure, destacando:
- Estruturação para cobrir regiões, zonas de disponibilidade, grupos de recursos e muito mais. Compreensão da arquitetura física do Azure, regiões e zonas de disponibilidade. Introduz o conceito de assinaturas e grupos de recursos para organizar recursos na nuvem.
- Os tópicos sobre computação e rede cobrirão a criação de máquinas virtuais, rede, armazenamento e hospedagem de aplicativos. Explora diferentes estratégias de armazenamento e se um servidor é necessário para certas soluções na nuvem.
- Modelos de identidade e segurança serão discutidos, com foco na responsabilidade compartilhada na nuvem. Cobrirá conformidade, gerenciamento de permissões e outros aspectos de segurança importantes dos ambientes de nuvem.
Além de laboratórios práticos para praticar a criação de recursos como máquinas virtuais e redes, especificamente em torno do compartilhamento de responsabilidade e segurança, conformidade e permissões no contexto do Azure.


## Módulo Computação e Rede

Este módulo se aprofunda focando especificamente nos serviços de computação em nuvem dentro do Microsoft Azure. Aborda tipos de computação, como máquinas virtuais e contêineres, juntamente com a importância da infraestrutura de desktop virtual (VDI). Enfatiza a flexibilidade e a eficiência dos serviços do Azure, como o dimensionamento de recursos, o gerenciamento de máquinas virtuais e o balanceamento de carga para alta disponibilidade. Também destaca o modelo de responsabilidade compartilhada nos serviços de nuvem e as vantagens das soluções de trabalho remoto.

- O Azure oferece uma variedade de serviços de computação além de apenas máquinas virtuais, incluindo instâncias de contêiner, aplicativos e desktops virtuais. O Microsoft Azure permite a criação de máquinas virtuais (VMs) que podem executar Windows ou Linux, com controle total sobre o software do sistema, mas não sobre o hardware.
- As máquinas virtuais do Azure oferecem flexibilidade significativa, permitindo que os usuários instalem, configurem e removam aplicativos, bem como gerenciem as configurações do sistema. O conceito de 'compartilhamento de responsabilidade' no Azure significa que os usuários são responsáveis por gerenciar o software e as configurações, enquanto a Microsoft mantém a infraestrutura física.
- O Azure fornece recursos escaláveis por meio de recursos como escalonamento de VMs e balanceamento de carga, garantindo gerenciamento eficiente de recursos e redundância. Os conjuntos de escala de máquinas virtuais no Azure permitem o escalonamento automático de VMs com base na demanda, melhorando o desempenho e a disponibilidade para aplicativos de grande escala.
- Desktops virtuais, como os fornecidos pelo serviço Azure Virtual Desktop, tornaram-se muito populares durante a pandemia para o trabalho remoto, oferecendo uma alternativa flexível aos computadores físicos. Uma das principais vantagens de usar desktops virtuais é a redução de problemas relacionados ao hardware, pois os usuários podem acessar os recursos de sua empresa remotamente sem precisar de um computador físico.


## Módulo Identidade, Acesso e Segurança

Este módulo foca em tópicos críticos relacionados à identidade, acesso e segurança dentro do ambiente de nuvem Azure, cobrindo serviços de diretório, métodos de autenticação e modelos de segurança. Ele destaca ferramentas como o Microsoft Entra ID e o Entra Domain Services, juntamente com estratégias de autenticação como o logon único e a autenticação multifator. A importância dos modelos de segurança de confiança zero e das estratégias de defesa em profundidade é enfatizada para prevenir violações de segurança. Também explora o Microsoft Defender para Nuvem, uma plataforma híbrida e multi-nuvem, ajudando os usuários a gerenciar e proteger seus ambientes. É uma visão geral abrangente e projetada para oferecer insights práticos sobre segurança na nuvem.

- Segurança é nossa responsabilidade; os provedores nos dão ferramentas, mas nós mesmos devemos implementar a segurança. O tema se concentra em serviços de diretório, métodos de autenticação, modelos de segurança e serviços do Azure AD. Você aprenderá sobre o Microsoft Entra ID, anteriormente conhecido como Azure AD, e como ele se integra ao gerenciamento de identidade e acesso.
- Os principais métodos de autenticação abordados incluem o Logon Único (SSO) e a Autenticação Multifator (MFA). Identidades externas e gerenciamento de acesso de convidados no Azure AD são cruciais para habilitar a colaboração segura. O acesso condicional no Azure AD ajuda a controlar quem e o que pode acessar seus recursos com base em condições específicas.
- O RBAC (Controle de Acesso Baseado em Função) é essencial para gerenciar permissões no Azure, controlando o acesso de usuários e recursos. Confiança Zero é um modelo de segurança central – nunca confie, sempre verifique – reduzindo os riscos de ataques laterais e vazamentos de dados.
- Defesa em Profundidade, ou o 'modelo de cebola', garante segurança em camadas em múltiplos ambientes, como rede, autenticação e aplicação. O Microsoft Defender para Nuvem é uma plataforma nativa da nuvem que oferece visibilidade e segurança em ambientes híbridos e multi-nuvem.







# Resumo - Serviços de Inteligência Artificial - Azure

## Módulo de Introdução

Este curso oferece uma introdução aos conceitos de Inteligência Artificial utilizando o Microsoft Azure. Destinado a profissionais que buscam explorar ferramentas e serviços de IA essenciais, com foco em aprendizado de máquina, processamento de linguagem natural, visão computacional e aplicações de IA. Inclui fundamentos teóricos e insights práticos, com exemplos do mundo real. Ele também enfatiza a importância do uso responsável da IA e da experiência prática com ferramentas da Microsoft, impulsionando o conhecimento de IA para diversas aplicações industriais.

- Aborda os conceitos de Inteligência Artificial (IA) no Microsoft Azure e tem como objetivo preparar indivíduos para o exame de certificação. O conteúdo é totalmente atualizado, cobrindo as mais recentes ferramentas e serviços de IA fornecidos pela Microsoft. Também é  adequado tanto para a preparação para a certificação quanto para aqueles que desejam se manter atualizados com os avanços da IA.
- O objetivo é introduzir a IA em aplicações cotidianas, ajudando os alunos a usar as ferramentas da Microsoft para resolver problemas do mundo real. Explora várias ferramentas e serviços de IA da Microsoft, desde processamento de documentos até aprendizado de máquina e IA generativa, com atividades práticas, quizzes e laboratórios para fortalecer a compreensão.
- Aplica esses conceitos de IA usando os serviços do Microsoft Azure e explora como usá-los para diferentes cenários, como gerenciamento de documentos e análise de dados em larga escala, aprendizado de máquina, visão computacional, processamento de linguagem natural e modelos generativos de IA. Enfatizado  no aprendizado responsável, especialmente ao lidar com dados confidenciais, como vídeos, imagens e documentos pessoais, garantindo o uso ético das tecnologias de IA.

