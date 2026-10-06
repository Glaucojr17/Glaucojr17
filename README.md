# Glauco Candido Santana Junior

Atuo há mais de 10 anos em tecnologia, com experiência em infraestrutura, sustentação de aplicações e desenvolvimento. Meu foco hoje é DevOps, SRE e automação: gosto de entender como um serviço é entregue, como se comporta em produção e o que precisa mudar quando algo falha.

Trabalho com AWS, Kubernetes/EKS, Docker, Linux, Terraform e pipelines de CI/CD em Azure DevOps, Jenkins e Harness. Também desenvolvo com Node.js, TypeScript e PostgreSQL. Minha experiência em suporte, redes e ambientes críticos me ajuda a investigar problemas que atravessam várias camadas da plataforma.

## Projetos que mostram meu trabalho

Os projetos abaixo nasceram de tarefas e problemas que fazem parte da minha rotina em infraestrutura, desenvolvimento e operações. Reproduzi esses cenários em laboratórios e pipelines de validação, com dados sintéticos, para mostrar como investigo, implemento e documento soluções sem expor código, credenciais ou informações de ambientes corporativos. Cada repositório informa o que foi executado e o que ainda exige validação em uma conta ou cluster de homologação; por exemplo, a rede Terraform foi testada com provider simulado, sem aplicar recursos AWS.

| Projeto | O que você pode avaliar |
| --- | --- |
| [Laboratório de plataforma DevOps](https://github.com/Glaucojr17/devops-platform-lab) | API Node.js com testes, imagem Docker, recursos Kubernetes e Terraform, probes de saúde, métricas e pipelines de validação. O README separa o que foi executado do que ainda exige um cluster e ferramentas locais. |
| [Rede AWS com Terraform](https://github.com/Glaucojr17/aws-network-terraform-lab) | VPC em duas zonas, sub-redes públicas e isoladas, rotas explícitas e testes com provider simulado. O CI valida a topologia sem criar recursos pagos. |
| [Entrega GitOps em Kubernetes](https://github.com/Glaucojr17/kubernetes-gitops-delivery) | Kustomize para dev/prod, Applications Argo CD, rollout em kind e smoke test HTTP. O README explica a política de sync e os limites do laboratório. |
| [Observabilidade e incidente SRE](https://github.com/Glaucojr17/sre-observability-incident-lab) | Serviço Node instrumentado, Prometheus, Grafana, teste de alerta e runbook para investigar uma falha 503 reproduzível. |
| [kube-triage: ferramenta para a comunidade](https://github.com/Glaucojr17/kube-triage) | CLI de leitura para a primeira triagem de pods Kubernetes. Correlaciona status e eventos, sugere próximos passos e permite praticar offline com exemplos sintéticos. Código aberto com testes e instruções de contribuição. |
| [Automação de agentes Zabbix](https://github.com/Glaucojr17/Script-Instala-o-Agente-Zabbix) | Scripts de infraestrutura e um gerador parametrizado de configuração em Linux, com validação de entradas, TLS com PSK, testes e runbook. A [mudança revisável](https://github.com/Glaucojr17/Script-Instala-o-Agente-Zabbix/pull/1) registra a implementação. |
| [Site VOLTTA System](https://github.com/Glaucojr17/voltta-system-site) | Site institucional responsivo em HTML, CSS e JavaScript. A [melhoria integrada](https://github.com/Glaucojr17/voltta-system-site/pull/1) documenta decisões, operação e valida páginas e referências locais no CI. |

Também trabalho no VolttaSystem ERP/CRM, um projeto privado com backend Node.js/TypeScript, APIs REST, PostgreSQL e publicação em Linux. Preservo o código e os dados privados; os repositórios acima mostram trabalho que pode ser inspecionado publicamente.

## Como trabalho

Gosto de automatizar tarefas repetitivas, deixar mudanças revisáveis e documentar o suficiente para outra pessoa conseguir operar o serviço. Em incidentes, começo pelo impacto e pelas evidências, investigo logs, métricas, rede e dependências e só considero a mudança concluída depois de validar o resultado.

📍 Maceió, AL · [Contato por e-mail](mailto:glaucojunior.017@gmail.com)
