# Trilha Red Team de 16 semanas

Este é um roteiro de autoestudo, não uma obrigação. Não há notas, frequência ou prazo. Reduza ou aumente o ritmo, repita exercícios e use apenas as partes que forem úteis no seu momento.

## Como estudar

Divida cada etapa em três sessões:

1. **Aprender:** leia, assista às aulas e anote termos desconhecidos.
2. **Praticar:** digite os comandos, registre resultados e investigue erros.
3. **Revisar:** repita sem copiar e explique o conceito com suas palavras.

Quando ficar travado, volte um tópico e procure uma explicação mais simples. Compreender é mais importante que terminar rapidamente.

## Etapa Zero

Use esta etapa se o computador ainda for um ambiente novo para você.

Aprenda a:

- ligar, reiniciar e desligar corretamente;
- usar teclado, mouse, copiar, colar, desfazer e capturar a tela;
- navegar por abas e baixar arquivos com segurança;
- criar pastas e localizar Downloads, Documentos e Área de Trabalho;
- reconhecer extensões como PDF, TXT, ZIP, imagens e executáveis;
- instalar e remover um programa com orientação;
- usar e-mail, senhas fortes e autenticação em dois fatores;
- diferenciar conta, login, link, site, aplicativo, arquivo e nuvem.

Prática sugerida: crie uma pasta, baixe um arquivo de fonte confiável, localize-o, compacte-o em ZIP e descompacte-o novamente.

## Módulo 1 — Computadores e sistemas

### Semana 1 — Organização de computadores

Estude hardware, software, firmware, sistema operacional, CPU, memória, armazenamento, periféricos, bits, bytes, binário e hexadecimal.

Entrega opcional: diagrama dos componentes de um computador e glossário com 15 termos.

### Semana 2 — Windows e Linux

Estude usuários, grupos, processos, serviços, permissões e diferenças básicas entre os sistemas.

Prática: crie uma VM Linux, navegue pelo sistema, localize processos e compare usuário comum com administrador.

### Semana 3 — Arquivos e terminal

Estude caminhos absolutos e relativos, extensões, compactação, variáveis de ambiente, terminal, PowerShell e shell Linux.

Prática: crie, copie, mova, renomeie, compacte e localize arquivos. Calcule o hash de dois arquivos e compare os resultados.

## Módulo 2 — Redes e TCP/IP

### Semana 4 — Como redes funcionam

Estude LAN, WAN, internet, cliente, servidor, switch, roteador, firewall e modelos OSI e TCP/IP.

Entrega opcional: diagrama de uma rede fictícia e explicação do caminho entre cliente e servidor.

### Semana 5 — Endereçamento

Estude IPv4, introdução ao IPv6, IP público e privado, máscara, gateway, DHCP, NAT, MAC, ARP e sub-redes simples.

Prática: consulte os dados de rede do laboratório e resolva exercícios de `/24`, `/25` e `/26`.

### Semana 6 — TCP, UDP e portas

Estude handshake, confirmação, encerramento, UDP, portas, sockets, ICMP e estado de conexão.

Prática: observe conexões do próprio computador e relacione serviços conhecidos às portas mais comuns.

### Semana 7 — Protocolos de aplicação

Estude DNS, HTTP, HTTPS, SSH, SFTP, SMTP, IMAP, DHCP, NTP, TLS e certificados.

Prática: realize uma consulta DNS, inspecione cabeçalhos HTTP de um laboratório e visualize os dados de um certificado.

### Semana 8 — Diagnóstico e tráfego

Estude pacotes, quadros, cabeçalhos, payload, latência, perda, resolução de nomes e uso introdutório do Wireshark.

Prática: capture somente seu próprio tráfego e identifique origem, destino, portas e protocolos.

## Módulo 3 — Programação e automação

### Semana 9 — Lógica

Estude algoritmos, variáveis, tipos, operadores, condições, repetição, funções, listas, dicionários e tratamento de erros.

Prática: escreva pseudocódigo para validar uma senha e organizar uma lista de endereços IP.

### Semana 10 — Python

Estude strings, números, coleções, funções, módulos, arquivos e depuração.

Prática: crie um relatório do sistema e leia um log de exemplo para contar ocorrências.

### Semana 11 — Shell e Git

Estude pipes, redirecionamento, filtros, variáveis, repositórios, commits, histórico e Markdown.

Entrega opcional: repositório com README e uma automação de inventário do próprio computador.

## Módulo 4 — Red Team e segurança ofensiva

### Semana 12 — Ética, escopo e metodologia

Estude autorização, escopo, regras de engajamento, critérios de parada, confidencialidade, integridade, disponibilidade, ativo, ameaça, vulnerabilidade, risco, controle e impacto.

Prática: escreva um plano de avaliação para uma empresa fictícia, incluindo ativos permitidos, técnicas proibidas, janela, contatos e tratamento de evidências.

### Semana 13 — Windows, identidade e Active Directory

Estude domínios, usuários, grupos, políticas, autenticação, autorização, menor privilégio, Kerberos, NTLM, LDAP, SMB e logs de segurança.

Prática: monte um cenário local simples, documente relações de confiança e explique riscos de permissões excessivas sem atacar infraestrutura externa.

### Semana 14 — Reconhecimento e superfície de ataque

Estude reconhecimento passivo, DNS, certificados, tecnologias, exposição de serviços, validação de escopo e diferença entre observação, candidato e vulnerabilidade confirmada.

Prática: analise apenas um domínio próprio ou laboratório, produza inventário de ativos e registre limitações e falsos positivos.

### Semana 15 — Testes web e validação

Estude metodologia web, cookies, sessões, autenticação, controle de acesso, validação de entrada, injeção, XSS, SSRF, lógica de negócio, CVE, CWE e divulgação responsável.

Prática: use uma aplicação deliberadamente vulnerável, confirme uma falha guiada e escreva evidência, impacto, reprodução, detecção e correção.

### Semana 16 — Exercício Red Team controlado

Planeje e execute uma simulação pequena no próprio laboratório. Documente:

- objetivo e regras de engajamento;
- cenário e técnica ATT&CK selecionada;
- hipótese e caminho de ataque esperado;
- ações executadas e evidências;
- impacto demonstrado sem causar dano;
- telemetria e oportunidades de detecção;
- limpeza do ambiente;
- riscos, correções e resumo executivo.

## Ao concluir

Você deve conseguir explicar como computadores, identidades, redes e protocolos se conectam; definir um escopo; montar um laboratório seguro; realizar reconhecimento autorizado; validar uma hipótese sem ultrapassar limites; e produzir um relatório ofensivo ético e reproduzível.
