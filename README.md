<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.png">
  <source media="(prefers-color-scheme: light)" srcset="assets/logo-light.png">
  <img src="assets/logo-light.png" alt="00infosec" width="200">
</picture>

# GUIA PARA ESTUDANTES DE INFOSEC

### Fundamentos · Laboratório · Prática · Portfólio · Carreira

Um caminho aberto e responsável para começar em segurança da informação.

[![Licença](https://img.shields.io/badge/licença-CC%20BY%204.0-111111?style=flat-square)](LICENSE)
[![Contribuições](https://img.shields.io/badge/contribuições-bem--vindas-111111?style=flat-square)](CONTRIBUTING.md)

[Comece aqui](#comece-aqui) · [Fundamentos](#fundamentos) · [Laboratório](#laboratório-seguro) · [Trilhas](#escolha-uma-trilha) · [Portfólio](PROJETOS.md) · [Plano de 16 semanas](TRILHA-16-SEMANAS.md)

</div>

---

## Antes de tudo

Segurança da informação não começa com ferramentas. Começa com fundamentos, curiosidade, documentação e responsabilidade.

Este guia é para quem está iniciando e quer aprender com prática realista, sem depender de uma coleção infinita de cursos. Você não precisa dominar tudo de uma vez. Aprenda um conceito, pratique em ambiente controlado, registre o que entendeu e avance.

> Teste somente sistemas próprios, laboratórios preparados para estudo ou ambientes para os quais você possui autorização explícita.

## Comece aqui

Se você está completamente no início, siga esta ordem:

1. Aprenda redes, Linux, Windows e fundamentos da web.
2. Monte um laboratório isolado.
3. Escolha uma trilha inicial.
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

## Escolha uma trilha

### Segurança ofensiva

Estude redes, HTTP, enumeração, vulnerabilidades web, metodologia de testes e elaboração de relatórios. O objetivo não é “rodar ferramentas”, mas compreender hipóteses, evidências, impacto e mitigação.

### Blue Team e detecção

Estude logs, telemetria, Windows Event Logs, Sysmon, redes, SIEM, resposta a incidentes e criação de regras. Pratique explicando quais sinais uma atividade gera e como investigá-los.

### Application Security

Estude desenvolvimento seguro, autenticação, autorização, modelagem de ameaças, revisão de código, dependências e segurança de APIs. Aprender a programar é parte central desta trilha.

### Cloud Security

Construa primeiro uma base de redes, Linux, identidade e controle de acesso. Depois avance para IAM, armazenamento, logs, segredos, containers, infraestrutura como código e postura de segurança.

### Pesquisa de vulnerabilidades

Estude sistemas operacionais, C/C++, debugging, assembly, formatos de arquivo e técnicas de fuzzing. Esta é uma trilha de longo prazo; fundamentos fortes importam mais que velocidade.

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
| [MITRE ATT&CK](https://attack.mitre.org/) | Técnicas e comportamento de adversários |
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

Um bom portfólio mostra raciocínio, não apenas capturas de tela. Inclua:

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

- atacar sistemas sem autorização;
- copiar write-ups sem compreender;
- publicar credenciais, tokens ou dados pessoais;
- executar scripts desconhecidos fora de uma VM;
- confundir resultado automatizado com vulnerabilidade confirmada;
- colecionar cursos sem construir projetos;
- apresentar laboratórios como experiência profissional real.

## Próximos passos

- Siga a [Trilha prática de 16 semanas](TRILHA-16-SEMANAS.md).
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
