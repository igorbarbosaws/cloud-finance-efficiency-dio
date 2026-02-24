# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 23 de fevereiro de 2026  
**Empresa:** Abstergo Industries  
**Responsável:** Igor Barbosa

---

## Introdução
Este relatório apresenta o processo de implementação e modernização de infraestrutura na empresa Abstergo Industries, realizado por Igor Barbosa. O objetivo principal do projeto foi elencar 3 serviços da nuvem AWS com a finalidade de realizar a diminuição de custos imediatos da operação, focando em eficiência logística, redução do desperdício de recursos ociosos e otimização de armazenamento de dados regulatórios.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos focados na alocação inteligente de recursos financeiros e tecnológicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização Logística
- **Nome da ferramenta:** Amazon Location Service
- **Foco da ferramenta:** Otimização de rotas logísticas e rastreamento de frotas com precificação sob demanda.
- **Descrição de caso de uso:** Como um hub de distribuição farmacêutica, a Abstergo possui altos gastos com logística e controle de frota (combustível, tempo e devoluções). O *Amazon Location Service* permite adicionar mapas, rastrear veículos em tempo real e otimizar as rotas de entrega. Do ponto de vista financeiro, a empresa deixa de pagar licenças caras de serviços de mapas tradicionais (contratos anuais fixos), passando a pagar uma fração do valor apenas pelas requisições utilizadas (modelo *pay-as-you-go*). A otimização de rotas também reduz o consumo de combustível e agiliza a entrega de medicamentos termolábeis, diminuindo o índice de perdas.

### Etapa 2: Eficiência em Armazenamento
- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering
- **Foco da ferramenta:** Redução automatizada de custos de armazenamento em nuvem sem impacto na performance.
- **Descrição de caso de uso:** O setor farmacêutico é altamente regulado, obrigando a Abstergo a guardar volumes gigantescos de notas fiscais, registros de lotes e dados de *compliance* por anos. O *S3 Intelligent-Tiering* é um serviço de armazenamento que monitora o acesso a esses documentos e move automaticamente os arquivos menos acessados para camadas de armazenamento muito mais baratas (como o Amazon S3 Glacier). Isso elimina o trabalho manual da equipe de TI e reduz a fatura mensal de armazenamento da empresa de forma quase instantânea, mantendo os dados seguros e acessíveis para auditorias.

### Etapa 3: Banco de Dados Escalável
- **Nome da ferramenta:** Amazon Aurora Serverless
- **Foco da ferramenta:** Redução de custos com banco de dados através de escalabilidade automática.
- **Descrição de caso de uso:** O sistema de controle de estoque (WMS) e processamento de pedidos da Abstergo possui picos de acesso (horários de recebimento de grandes lotes) e períodos de ociosidade (madrugadas e fins de semana). O *Aurora Serverless* ajusta a capacidade do banco de dados automaticamente com base na demanda real. Para o gestor financeiro, isso significa uma redução agressiva de custos operacionais (OpEx), pois a empresa deixa de pagar por servidores potentes rodando 24 horas por dia e passa a pagar apenas pelos segundos exatos em que o banco de dados processou informações.

---

## Conclusão
A implementação destas ferramentas na empresa Abstergo Industries tem como esperado a redução imediata dos custos operacionais de TI e logística, o aumento da previsibilidade financeira e a eliminação do desperdício com recursos ociosos, o que aumentará a eficiência da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos de distribuição.

---

## Anexos

### Dashboard de Estimativa de Redução de Custos (Mockup Calculadora AWS)
*Visualização interativa com métricas de economia e comparativo financeiro.* 👉 [Acesse o Dashboard Aqui](https://script.google.com/macros/s/AKfycbyXfZDjSP059rnFBWTsvJqSatKTPTp9tttELxc3SWm3vyZBy-MWHNCLKOEjog-8p6zy/exec)

### Manuais e Documentações Técnicas
* [Manual do Amazon Location Service](https://docs.aws.amazon.com/location/index.html)
* [Guia de Usuário: S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html)
* [Documentação do Amazon Aurora Serverless v2](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html)
* [Whitepaper: Otimização de Custos na AWS (AWS Well-Architected)](https://docs.aws.amazon.com/wellarchitected/latest/cost-optimization-pillar/welcome.html)

---

**Assinatura do Responsável pelo Projeto:** <br>
***Igor Barbosa Wanderley da Silva*** <br>
