# -Configurando-Recursos-e-Dimensionamentos-em-M-quinas-Virtuais-na-Azure
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

Resumo do que aprendi: Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

No curso aprendi como ajustar os recursos de hardware virtual de uma VM e como usar as opções de dimensionamento que o Azure oferece para equilibrar custo e desempenho.

Principais pontos:

Recursos que podem ser configurados em uma VM

Tamanho da VM: define quantidade de vCPUs e memória.

Discos: SSD Premium, SSD Standard ou HDD.

Rede: configurar IP público, NSG (firewall) e balanceadores.

Sistema Operacional: escolher imagens Linux ou Windows.

Dimensionamento (Scaling)

Vertical (Scale Up/Down) → alterar o tamanho da VM para mais ou menos recursos.

Horizontal (Scale Out/In) → adicionar ou remover instâncias usando VM Scale Sets.

Permite ajustar a capacidade conforme demanda e controlar custos.

Boas práticas que vi

Avaliar sempre o tamanho correto da VM para não pagar por recursos ociosos.

Usar Autoescala em Scale Sets para lidar com picos de tráfego.

Configurar zonas de disponibilidade para alta resiliência.

Monitorar desempenho com Azure Monitor e métricas de CPU/RAM.

Aplicar tags para rastrear custos por projeto ou equipe.

Dicas importantes

Dimensionar pensando no perfil de carga de trabalho (teste de performance ajuda).

Ajustar discos e IOPS de acordo com a aplicação (ex.: banco de dados precisa de SSD Premium).

A região escolhida pode impactar no preço e na disponibilidade de SKUs de VM.
