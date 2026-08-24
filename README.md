<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/logo-light.png">
  <img src="assets/logo-light.png" alt="00infosec" width="200">
</picture>

# GUIA RED TEAM PARA ESTUDANTES

### Fundamentos · Segurança Ofensiva · OPSEC · Laboratório · Relatórios

Um caminho aberto e responsável para começar em Red Team e segurança ofensiva autorizada.

[![Licença](https://img.shields.io/badge/licença-CC%20BY%204.0-111111?style=flat-square)](LICENSE)
[![Contribuições](https://img.shields.io/badge/contribuições-bem--vindas-111111?style=flat-square)](CONTRIBUTING.md)

[Comece aqui](#comece-aqui) · [Fundamentos](#fundamentos) · [Laboratório](#laboratório-seguro) · [Trilhas](#escolha-uma-trilha) · [Portfólio](PROJETOS.md) · [Plano de 16 semanas](TRILHA-16-SEMANAS.md)

</div>

---

## Antes de tudo

Segurança da informação não começa com ferramentas. Começa com fundamentos, curiosidade, documentação e responsabilidade.

Este guia é para quem está iniciando e quer construir uma base real para Red Team, pentest e simulação de adversários. Você não precisa dominar tudo de uma vez. Aprenda um conceito, pratique em ambiente controlado, registre evidências, explique impacto e avance.

> Teste somente sistemas próprios, laboratórios preparados para estudo ou ambientes para os quais você possui autorização explícita.

## Comece aqui

Se você está completamente no início, siga esta ordem:

1. Aprenda redes, Linux, Windows e fundamentos da web.
2. Monte um laboratório isolado.
3. Aprenda a metodologia de uma avaliação ofensiva.
4. Pratique em plataformas autorizadas.
5. Escreva relatórios sobre o que aprendeu.
6. Publique projetos próprios, sem dados sensíveis ou material de terceiros.

Não comece comprando certificações ou executando ferramentas contra endereços aleatórios. Primeiro construa uma base que permita entender o resultado das ferramentas.

### Etapa Zero

Se arquivos, extensões, instalação de programas, navegador, e-mail ou autenticação em dois fatores ainda forem assuntos novos, comece pela [Etapa Zero da trilha](TRILHA-16-SEMANAS.md#etapa-zero). Não existe obrigação de terminar rápido: o guia pode ser usado no seu ritmo e todas as práticas são opcionais.

## Fundamentos

| Área | O que aprender | Evidência prática |
|---|---|---|
| **Redes** | TCP/IP, DNS, HTTP, TLS, portas, roteamento e NAT | Capturar e explicar uma conexão em laboratório |
| **Linux** | terminal, permissões, processos, serviços, logs e SSH | Administrar uma VM sem interface gráfica |
| **Windows** | usuários, serviços, registro, eventos e PowerShell | Localizar eventos e explicar sua origem |
| **Programação** | Python, estruturas de dados, arquivos, APIs e testes | Criar uma automação pequena e documentada |
| **Web** | navegador, cookies, sessões, APIs, autenticação e banco de dados | Explicar uma requisição HTTP completa |
| **Git** | commits, branches, pull requests e revisão | Manter seus projetos com histórico limpo |
| **Inglês técnico** | leitura de documentação, erros e advisories | Resumir uma documentação oficial em português |

## Laboratório seguro

Uma configuração inicial simples:

- computador com virtualização habilitada;
- uma VM Linux para estudo;
- uma VM Windows de avaliação, se possível;
- rede virtual isolada para exercícios locais;
- snapshots antes de mudanças importantes;
- aplicações intencionalmente vulneráveis executadas apenas no laboratório;
- anotações sem credenciais, dados pessoais ou informações de terceiros.

Mantenha o laboratório separado da rede de produção. Nunca reutilize senhas reais e não exponha aplicações vulneráveis diretamente à internet.

## Formação Red Team

### Metodologia ofensiva

Estude definição de escopo, regras de engajamento, reconhecimento, enumeração, validação, exploração controlada, pós-exploração em laboratório, limpeza e elaboração de relatórios. O objetivo não é “rodar ferramentas”, mas construir hipóteses, reunir evidências e explicar impacto.

### Infraestrutura e identidade

Aprenda Linux, Windows, Active Directory, autenticação, Kerberos, SMB, LDAP, serviços, permissões e segmentação. Um operador ofensivo precisa entender como ambientes corporativos funcionam antes de avaliá-los.

### Web e APIs

Estude HTTP, sessões, autenticação, autorização, lógica de negócio, APIs, validação de entrada e revisão de código. Pratique apenas em aplicações deliberadamente vulneráveis ou ambientes autorizados.

### OPSEC e simulação de adversários

Aprenda planejamento, redução de exposição desnecessária, controle de artefatos, comunicação durante o exercício, critérios de parada e preservação de evidências. OPSEC não elimina a necessidade de autorização e rastreabilidade.

### Detecção como competência de apoio

Estude logs, telemetria, Windows Event Logs, Sysmon e tráfego de rede para compreender quais sinais suas ações produzem. Um bom exercício termina com recomendações que ajudem a defesa a detectar e responder.

## Plataformas e fontes oficiais

| Recurso | Melhor uso |
|---|---|
| [PortSwigger Web Security Academy](https://portswigger.net/web-security) | Teoria e laboratórios guiados de segurança web |
| [OverTheWire](https://overthewire.org/wargames/) | Linux, terminal e fundamentos por meio de wargames |
| [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) | Aplicação intencionalmente vulnerável para laboratório local |
| [Cisco Skills for All](https://skillsforall.com/) | Hardware, sistemas operacionais, redes, Python e introdução à cibersegurança |
| [Curso em Vídeo](https://www.cursoemvideo.com/trilhas/) | Base de informática, infraestrutura, algoritmos, Python, Git e Linux em português |
| [TryHackMe — Pre Security](https://tryhackme.com/beginner-path) | Laboratórios guiados depois dos fundamentos de TI |
| [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/) | Metodologia de testes e referência técnica |
| [MITRE ATT&CK](https://attack.mitre.org/) | Planejamento e compreensão de técnicas adversárias |
| [MITRE D3FEND](https://d3fend.mitre.org/) | Contramedidas e vocabulário defensivo |
| [CISA KEV](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) | Vulnerabilidades conhecidas por exploração real |

Plataformas mudam. Prefira sempre a documentação oficial e confirme os termos de uso antes de praticar.

## Como estudar de verdade

Use um ciclo simples:

```text
CONCEITO → LABORATÓRIO → EVIDÊNCIA → EXPLICAÇÃO → REVISÃO
```

Para cada exercício, responda:

- Qual era o objetivo?
- Qual conceito estava sendo testado?
- O que foi observado?
- Como a evidência confirma a conclusão?
- Qual seria o impacto em um ambiente real?
- Como detectar ou mitigar?
- O que ainda não ficou claro?

## Portfólio

Um bom portfólio de Red Team mostra metodologia e raciocínio, não apenas capturas de tela. Inclua:

- objetivo e escopo;
- arquitetura do laboratório;
- metodologia;
- evidências sanitizadas;
- limitações;
- mitigação;
- referências;
- aprendizados e próximos passos.

Veja sugestões em [Projetos para portfólio](PROJETOS.md).

## Certificações

Certificações podem ajudar a organizar estudos ou atravessar filtros de recrutamento, mas não substituem fundamentos e projetos. Antes de pagar por uma prova, verifique:

- se ela aparece nas vagas que você busca;
- se o conteúdo combina com sua trilha;
- se você consegue demonstrar as mesmas habilidades em projetos;
- custo total, renovação e validade;
- experiência recente de candidatos e documentação oficial.

## O que evitar

- atacar, enumerar ou testar sistemas sem autorização;
- copiar write-ups sem compreender;
- publicar credenciais, tokens ou dados pessoais;
- executar scripts desconhecidos fora de uma VM;
- confundir resultado automatizado com vulnerabilidade confirmada;
- colecionar cursos sem construir projetos;
- apresentar laboratórios como experiência profissional real.

## Próximos passos

- Siga a [Trilha Red Team de 16 semanas](TRILHA-16-SEMANAS.md).
- Use o [Modelo de diário de estudos](DIARIO-DE-ESTUDOS.md).
- Escolha um dos [Projetos para portfólio](PROJETOS.md).
- Registre seu progresso semanalmente.
- Compartilhe correções e melhorias pelo [Guia de contribuição](CONTRIBUTING.md).

## Licença

O conteúdo educacional é disponibilizado sob a licença [Creative Commons Attribution 4.0](LICENSE).

---

<div align="center">
  <sub>Aprenda com método. Pratique com autorização. Compartilhe com responsabilidade.</sub><br>
  <strong>00infosec</strong>
</div>
