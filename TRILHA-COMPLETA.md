# Trilha Red Team — do iniciante ao avançado

Esta trilha não promete transformar alguém em especialista em poucos meses. O avanço depende de fundamentos, prática consistente, documentação e experiência em ambientes autorizados.

Os prazos são apenas referências. Avance quando conseguir demonstrar as competências do nível, não quando o calendário terminar.

## Nível 0 — Iniciante absoluto

### Objetivo

Usar o computador, a internet e contas digitais com autonomia e segurança.

### Competências

- arquivos, pastas, extensões e compactação;
- instalação e remoção de programas;
- navegador, downloads e identificação de links;
- contas, senhas fortes e autenticação em dois fatores;
- noções de hardware, software, sistema operacional e nuvem;
- pesquisa e leitura de mensagens de erro.

### Projeto de conclusão

Organize uma pasta de estudos, crie um documento, compacte os arquivos, calcule um hash e escreva o que cada etapa realizou.

### Critério de avanço

Conseguir instalar uma ferramenta confiável com orientação, localizar arquivos e explicar os cuidados tomados.

## Nível 1 — Fundamentos técnicos

### Objetivo

Compreender computadores, sistemas, redes, programação e web antes de iniciar avaliações ofensivas.

### Competências

- Linux e Windows: usuários, processos, serviços, permissões e logs;
- TCP/IP, DNS, HTTP, TLS, roteamento, NAT, portas e protocolos;
- terminal, PowerShell e shell Linux;
- Python, lógica, arquivos, JSON, APIs e tratamento de erros;
- Git, commits, branches e documentação Markdown;
- virtualização, snapshots e redes isoladas.

### Caminho sugerido

Complete a [Trilha detalhada de 16 semanas](TRILHA-16-SEMANAS.md).

### Projeto de conclusão

Monte duas VMs isoladas, documente a rede, colete apenas o próprio tráfego e crie uma automação de inventário.

### Critério de avanço

Explicar uma conexão HTTP do DNS ao TLS, administrar uma VM pelo terminal e escrever um script pequeno sem copiar blocos desconhecidos.

## Nível 2 — Operador Red Team júnior

### Objetivo

Executar avaliações guiadas em laboratórios, respeitando escopo e produzindo relatórios claros.

### Competências

- autorização, regras de engajamento e critérios de parada;
- reconhecimento passivo e ativo dentro do escopo;
- enumeração de serviços e validação manual;
- testes web: autenticação, autorização, sessões, entrada e lógica;
- classificação entre observação, candidato e finding;
- evidência, impacto, reprodução, detecção e mitigação;
- noções de MITRE ATT&CK e cadeia de ataque;
- remoção de artefatos e encerramento do exercício.

### Laboratórios

- PortSwigger Web Security Academy;
- OWASP Juice Shop local;
- OverTheWire Bandit e Natas;
- rede virtual própria com serviços intencionalmente configurados para estudo.

### Projeto de conclusão

Realize uma avaliação completa de uma aplicação vulnerável autorizada e entregue resumo executivo, escopo, metodologia, findings, evidências sanitizadas e recomendações.

### Critério de avanço

Reproduzir resultados, justificar severidade, reconhecer falsos positivos e explicar quais logs cada ação gerou.

## Nível 3 — Operador intermediário

### Objetivo

Compreender ambientes corporativos e conduzir exercícios controlados com múltiplas etapas.

### Competências

- Active Directory, Kerberos, NTLM, LDAP, SMB, GPO e relações de confiança;
- identidade, privilégios, delegações e caminhos de ataque;
- segmentação, túneis e pivotamento exclusivamente em laboratório;
- segurança de APIs, containers, cloud e infraestrutura como código;
- automação de coleta e normalização de evidências;
- análise de telemetria de endpoint, identidade e rede;
- modelagem de ameaças e seleção de técnicas ATT&CK;
- comunicação operacional e relatórios para públicos técnicos e executivos.

### Laboratório

Monte um domínio local isolado com controlador, cliente e servidor. Use contas e dados fictícios. Colete logs e snapshots antes de cada exercício.

### Projeto de conclusão

Planeje uma simulação com objetivo definido, execute um caminho de ataque controlado, documente decisões, correlacione técnicas ATT&CK e proponha detecções e correções.

### Critério de avanço

Conduzir o exercício sem sair do escopo, adaptar o plano diante de evidências, preservar estabilidade e produzir uma narrativa técnica reproduzível.

## Nível 4 — Red Team avançado

### Objetivo

Planejar adversary emulation, desenvolver capacidades próprias com segurança e liderar exercícios colaborativos.

### Competências

- inteligência de ameaças aplicada à emulação;
- elaboração de planos de operações e regras de engajamento complexas;
- seleção, adaptação e encadeamento de técnicas ATT&CK;
- OPSEC, gestão de infraestrutura de laboratório e controle de artefatos;
- desenvolvimento seguro de tooling e testes automatizados;
- fundamentos de engenharia reversa, debugging, assembly e fuzzing;
- pesquisa de vulnerabilidades em software próprio ou autorizado;
- desenho de emulações que produzam aprendizado defensivo mensurável;
- liderança, comunicação de risco e coordenação com Blue Team;
- revisão pós-exercício e melhoria contínua.

### Projetos avançados seguros

- framework de simulação benigna que reproduza telemetria ATT&CK sem exploração real;
- laboratório de identidade com detecções e validação automatizada;
- ferramenta de sanitização e cadeia de custódia de evidências;
- emulador de superfície de ataque com ativos totalmente fictícios;
- pesquisa de uma falha em software criado para laboratório, com correção e testes;
- plano completo de adversary emulation baseado em uma ameaça documentada.

### Critério de maturidade

Ser capaz de explicar por que uma técnica foi escolhida, quais riscos operacionais existem, como reduzir impacto, que telemetria será produzida e como o exercício melhora a defesa.

## Especializações após a base

### Adversary emulation

Foco em inteligência de ameaças, ATT&CK, planejamento e reprodução segura de comportamentos.

### Web e APIs

Foco em lógica de negócio, autorização, protocolos, código e arquiteturas modernas.

### Identidade e Active Directory

Foco em autenticação, relações de confiança, privilégios e ambientes híbridos.

### Cloud Red Team

Foco em IAM, identidade federada, armazenamento, workloads, containers, logs e controles nativos.

### Pesquisa de vulnerabilidades

Foco em sistemas, linguagens de baixo nível, debugging, fuzzing, análise de causa raiz e divulgação coordenada.

### Desenvolvimento de tooling

Foco em engenharia de software, testes, segurança, portabilidade, documentação e uso controlado.

## Regra permanente

Nível técnico nunca substitui autorização. Quanto mais avançada a capacidade, maior deve ser o cuidado com escopo, impacto, dados, comunicação e responsabilidade.
