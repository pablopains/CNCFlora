<p align="center">
<img src="http://cncflora.jbrj.gov.br/portal/static/images/logo-cnc.png"/>
</p>

***

# Repositório com scripts R para download, pre-validação e preparação de dados para avaliação de risco de extinção da flora

***

## Contexto e motivação
  O Brasil é signatário da Estratégia Global de Conservação de Plantas (*Global Strategy for Plant Conservation* - GSPC) que norteia as ações de conservação dos países pela Convenção da Diversidade Biológica. A meta 2 da GSPC prevê avaliar o risco de extinção de toda a flora do planeta até 2020. O Centro Nacional de Conservação da Flora (CNCFlora) foi criado em 2008 como referência brasileira em geração, coordenação e difusão de informação sobre biodiversidade e estado de conservação da flora ameaçada de extinção do país. Apesar dos enormes avanços conduzidos pelo CNCFlora na avaliação do estado de conservação das espécies da flora nativa, o Brasil ainda está longe de atingir a meta 2 da GSPC contando atualmente com aproximadamente 20% de toda sua flora avaliada.

## Objetivos
  Otimizar e agilizar o processamento de informações das espécies para avaliação do risco de extinção.
  
## Índice scripts

  01. Baixar e formatar dados **Flora do Brasil 2020** (**FB202**; **IPT**)
  02. Cruzar inforamações **FB2020**
  03. Baixar, organizar, juntar e limpar dados do **GBIF**, **speciesLink** e **REFLORA**  
  03.1 **GBIF** utilizando o pacote rgbif
  03.2 **speciesLink** utilizando API
  03.3 **REFLORA** utilizando API
  04. Limpezas espaciais e adicionar centróides dos municípios nas coordenadas
  05. Estimando **EOO** e **AOO** 
  06. Buscando uso das espécies (fonte: *Useful Tropical Plants Database*)
  07. Cruzar o tipo de vegetação com código **IUCN**
  08. Apêndice CITES (*Convention on International Trade in Endangered Species of Wild Fauna and Flora*)
  09. Ocorrência em Unidades de Conservação
  10. Juntando todos os dados
  
  # Funções
  01. FB2020_get_taxon_scientificname_from_API
  02. GlobalTreeSearch_Check_Specie
  03. IUCNRedList_Check_Specie
  04. reflora_get_all_records_scientificname_HTML_API
  05. splink_get_record_scientificname_API

## Desenvolvedores
* Lucas Moraes            - lucascmoraes@gmail.com - 
* Andrea Sánchez-Tapia    - andreasancheztapia@gmail.com - [GitHub](https://github.com/AndreaSanchezTapia)
* José Wagner Ribeiro Jr. - jwribeirojunior@gmail.com - [GitHub](https://github.com/Xuletajr)
* Pablo Hendrigo Alves de Melo - melo.hendrigo@gmail.com - [GitHub](https://github.com/pablopains)
