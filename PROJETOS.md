# Projetos Red Team para portfólio

Todos os projetos devem usar sistemas próprios, dados fictícios ou ambientes explicitamente preparados para estudo. Um projeto ofensivo responsável inclui escopo, limites, evidências, impacto, detecção e mitigação.

## Mapeamento de superfície de ataque

Use um domínio controlado por você para levantar DNS, certificados, serviços e tecnologias. Diferencie observações, hipóteses e vulnerabilidades confirmadas.

Entrega: inventário de ativos, diagrama, limitações, falsos positivos e recomendações.

## Avaliação web autorizada

Use OWASP Juice Shop ou a Web Security Academy para praticar metodologia, validação e documentação.

Entrega: relatório com resumo executivo, escopo, evidência, impacto, reprodução, telemetria defensiva e correção.

## Laboratório de identidade

Monte um ambiente local pequeno com Windows, usuários, grupos e permissões. Modele relações de confiança e identifique configurações excessivas sem usar dados reais.

Entrega: diagrama de identidade, caminhos de risco, logs relevantes e plano de hardening.

## Simulação ATT&CK controlada

Selecione uma técnica de baixo impacto do MITRE ATT&CK e simule seu comportamento em uma VM própria. Defina critérios de parada antes de executar.

Entrega: plano do exercício, ações, evidências, eventos gerados, oportunidades de detecção e limpeza.

## Analisador de evidências

Crie uma ferramenta que normalize resultados de laboratório, remova segredos e gere Markdown ou JSON para relatórios.

Entrega: código testado, exemplos fictícios, modelo de dados e explicação das limitações.

## Verificador de OPSEC operacional

Crie um checklist que valide nomes de arquivos, metadados, credenciais acidentais, caminhos locais e informações sensíveis antes de publicar um relatório.

Entrega: ferramenta ou processo reproduzível, casos de teste e lista de riscos que ele não cobre.

## Relatório de reconhecimento

Use o [00INFOSEC RECON](https://github.com/00infosec/00infosec-recon) somente em domínio próprio ou autorizado e revise manualmente cada resultado.

Entrega: relatório que separe fatos observados, candidatos e findings confirmados, com justificativa para cada classificação.

## Plano de Red Team fictício

Escreva regras de engajamento para uma organização fictícia: objetivos, escopo, técnicas permitidas, proibições, contatos, janelas, evidências, comunicação de emergência e encerramento.

Entrega: documento profissional sem execução técnica contra terceiros.

## Critérios de qualidade

Todo projeto deve incluir:

- objetivo, autorização e escopo;
- arquitetura do laboratório;
- metodologia e hipóteses;
- evidências sanitizadas;
- critérios de parada;
- limitações e falsos positivos;
- impacto, detecção e mitigação;
- limpeza do ambiente;
- README, licença e histórico Git claro;
- ausência de segredos e dados de terceiros.
