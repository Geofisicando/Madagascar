# Introdução ao processamento sísmico com o pacote Madagascar

> Material complementar do curso de introdução ao processamento sísmico com o pacote Madagascar. Disponível no [Youtube](https://www.youtube.com/watch?v=m08qFF0Kv_E&list=PLLCFxfe9wkl9k6CDPEEC3ngxuMCHPrc_Z&index=4).

<img src="https://github.com/Geofisicando/Madagascar/blob/main/intro_madagascar.png" width=1000>

O pacote Madagascar é um pacote open-source (código aberto) para o processamento de dados geofísicos e experimentos numéricos reproduzíveis desenvolvido em linguagem C,
C++, Fortran e Python e que roda a partir do framework SCons.
Este pacote é utilizado para a análise de dados em geral e como kit de desenvolvimento de artigos científicos reproduzíveis.

Neste curso iremos utilizar o pacote Madagascar na sua principal aplicação: A modelagem, processamento, imageamento e inversão de dados sísmicos.
Iremos abordar os principais programas utilizados do pacote Madagascar para análise e visualização de dados sísmicos em geral.

[Site oficial do pacote Madagascar](https://ahay.org/wiki/Main_Page)

[Repositório oficial no Github](https://github.com/ahay/src)

## Índice

- #0 - Documentação e programas padrão (Parte 1)
- #1 - Documentação e programas padrão (Parte 2)
- #2 - Utilizar a interface de linha de comandos
- #3 - Operações aritméticas simples e exibir header
- #4 - Arquivos RSF e representação discreta de funções
- #5 - Como criar e manipular matrizes no Madagascar
- #6 - Como manipular o header (cabeçalho) dos arquivos
- #7 - Como plotar gráficos no Madagascar
- #8 - Como concatenar gráficos no Madagascar
- #9 - Como criar modelo de velocidades no Madagascar
- #10 - Modelo de velocidades com perturbação gaussiana
- #11 - Solução cinemática da equação da onda (eikonal)
- #12 - Exibir seção sísmica em formato wiggle trace
- #13 - Visualização do cubo de dados sísmico (3D)
- [#14 - Fluxo básico de processamento com scons (Flow)](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/Flow#aula-14---fluxo-b%C3%A1sico-de-processamento-com-scons-flow)
- [#15 - Automatizar a geração das figuras com scons (Plot)](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/Plot#aula-15---automatizar-a-gera%C3%A7%C3%A3o-das-figuras-com-scons-plot)
- [#16 - Gerar figuras com scons (Result)](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/Result#aula-16---gerar-figuras-com-scons-result)
- [#17 - Baixar arquivos de repositório com scons (Fetch)](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/Fetch#aula-17---baixar-arquivos-de-reposit%C3%B3rio-com-scons-fetch)
- #18 - Passar parâmetros ao scons e criar aliases de alvos
- #19 - Função End e mais detalhes sobre a função Fetch

- [#25 - Documentação de scripts SConstruct com função Help](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/Help#aula-25---documenta%C3%A7%C3%A3o-de-scripts-sconstruct-com-fun%C3%A7%C3%A3o-help)
- [#26 - Fluxo de processamento de Denoising (Parte 1)](https://github.com/Geofisicando/Madagascar/tree/main/exemplos/processing/denoising#aula-26---fluxo-de-processamento-de-denoising-parte-1)
