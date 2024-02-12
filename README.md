# SENAI: Estudo de caso
## CONTEXTUALIZAÇÃO
A manutenção preditiva está revolucionando a gestão de ativos industriais,proporcionando uma abordagem proativa para evitar falhas não planejadas. Ao integrar técnicas de aprendizado de máquina e análise avançada de dados, a inteligência artificial capacita as organizações a prever a necessidade de manutenção com base em indicadores de desempenho em tempo real. Isso é possível através do monitoramento contínuo de diversas variáveis coletadas diretamente dos equipamentos em análise.

Recentemente, uma indústria de grande porte localizada em São Paulo contratou um projeto para implementar um sistema completo de manutenção preditiva em seu chão de fábrica. Este projeto abrange desde o desenvolvimento de algoritmos sofisticados capazes de identificar uma variedade de falhas em máquinas e equipamentos, até a instalação de sensores e placas por equipes especializadas, como o time de automação e Instrumentação do SENAI.

Com o suporte do time de software do SENAI, um banco de dados robusto foi modelado e implementado para armazenar os dados coletados pelos sensores. Esses dados foram então disponibilizados para o time de IA, permitindo análises avançadas para identificar padrões e tendências nos equipamentos.

Você como pesquisador da área de Inteligência Artificial, foi designado para analisar os dados coletados das máquinas e equipamentos. Você deve desenvolver um modelo de Aprendizado de Máquina para identificar padrões do equipamento em análise.

**Sabe-se que cada arquivo foi adquirido por um sensor, os dados são oriundos de uma máquina com motor elétrico, os quais foram aquisitados a uma taxa de 10 KHz. Os dados de todos os sensores, foram adquiridos de forma simultânea, ou seja, no mesmo instante de tempo. O arquivo Classes.npy possui diferentes estados de funcionamento dessa máquina, podendo ou não possuir diferentes falhas e/ou funcionamento normal.**

OBS: sensores, são dispositivos capazes de medir grandezas físicas, tem seu funcionamento com base em sinais elétricos, em ambiente industrial podem captar sinais de ruídos e até mesmo entrarem em falha.
