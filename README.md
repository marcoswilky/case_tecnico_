# Case Técnico: Análise de Emissões de CO₂ e Cobertura Florestal

Este projeto apresenta uma análise comparativa das emissões de CO₂ e da cobertura florestal envolvendo Brasil, Alemanha e China, utilizando dados públicos e visualizações interativas em Python.

## Conteúdo

- **Emissões Anuais de CO₂**: Visualização das emissões ao longo dos anos para Brasil, Alemanha e China, com gráficos comparativos.
- **Perda de Floresta Primária Úmida no Brasil**: Correlação entre a perda de floresta e as emissões de CO₂e no Brasil.
- **Perda de Cobertura Arbórea**: Evolução da perda de cobertura arbórea nos três países selecionados.
- **Distribuição das Plantações Florestais no Brasil**: Gráfico de setores mostrando a proporção de diferentes tipos de plantações.
- **Referências**: Fontes de dados utilizadas na análise.

## Como Executar

1. **Pré-requisitos:**
   - Python 3.x instalado
   - Pacotes necessários: `pandas`, `matplotlib`, `seaborn`
   - Jupyter Notebook ou Google Colab

2. **Dados Utilizados:**  
   Os arquivos CSV utilizados estão referenciados no notebook (`case_tecnico_codigos.ipynb`). Certifique-se de ter os arquivos necessários na pasta `/content/` ao executar localmente.

3. **Execução:**
   - Abra o arquivo `case_tecnico_codigos.ipynb` no Jupyter Notebook ou Google Colab.
   - Execute as células sequencialmente para visualizar os gráficos e análises.

## Estrutura dos Dados

- **annual-co2-emissions-per-country.csv**  
  Emissões anuais de CO₂ por país.
- **treecover_loss_in_primary_forests_2001_tropics_only__ha.csv**  
  Perda de floresta primária úmida em hectares e emissões de CO₂e.
- **ganho_cobertura_arborea_2000-2020_by_region__ha.csv**  
  Ganho de cobertura arbórea por região.
- **perde_cobertura_arborea.csv**  
  Perda de cobertura arbórea por país.
- **treecover_extent_in__in_plantations__ha.csv**  
  Extensão da cobertura arbórea em plantações por tipo.

## Visualizações

- Gráficos de linha comparativos das emissões de CO₂.
- Gráficos de dispersão para correlação entre perda de floresta e emissões.
- Gráficos de linha e preenchimento para evolução da perda de cobertura arbórea.
- Gráfico de setores para distribuição das plantações florestais.

## Referências Bibliográficas

- Hannah Ritchie and Max Roser (2020) - “CO₂ emissions” OurWorldinData.org: [https://ourworldindata.org/co2-emissions](https://ourworldindata.org/co2-emissions)
- Brasil Interactive Forest & Tree Cover Change Data | GFW: [https://gfw.global/4mtCHwo](https://gfw.global/4mtCHwo)
- Global Forest Watch (2024) – with major processing by Our World in Data. “Tree cover loss”. Global Forest Watch, “Tree Cover Loss by Dominant Driver”.

## Autor

Projeto desenvolvido por [marcoswilky](https://github.com/marcoswilky).

---

> **Observação:** Este projeto tem finalidade de estudo e demonstração de análise de dados ambientais. Para dúvidas ou sugestões, abra uma issue neste repositório.
