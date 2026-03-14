# Template LaTeX para Relatório de Estágio e TCC - UNIJUÍ

Este repositório contém um template LaTeX customizado para a elaboração de Relatórios de Estágio e Trabalhos de Conclusão de Curso (TCC) da **UNIJUÍ (Universidade Regional do Noroeste do Estado do Rio Grande do Sul)**.

O template utiliza a classe `abnTeX2` para garantir a conformidade com as normas da ABNT e possui uma parametrização específica para atender aos requisitos visuais e estruturais da instituição.

## Como Começar

Para utilizar este template, recomenda-se o uso de plataformas online que facilitam a edição e compilação sem a necessidade de instalação local:

# Uso no Overleaf

1.  Baixe o código deste repositório como um arquivo `.zip`.
2.  No [Overleaf](https://www.overleaf.com/), clique em **New Project** > **Upload Project**.
3.  Selecione o arquivo `.zip` enviado.
4.  O Overleaf irá carregar todos os arquivos e você poderá começar a editar o `main.tex` imediatamente.


### Estrutura do Projeto

O projeto está organizado da seguinte forma:

*   `main.tex`: Arquivo principal do projeto.
*   `unijui.sty`: Arquivo de estilo com as customizações da UNIJUÍ.
*   `capitulos/`: Pasta contendo os arquivos `.tex` de cada capítulo.
*   `figuras/`: Pasta para armazenamento de imagens.
*   `referencias.bib`: Arquivo para gestão das referências bibliográficas.
*   `apendices/` e `anexos/`: Pastas para documentos complementares.

## Compilação

Ao utilizar o **Overleaf**, a compilação é automática. Basta clicar no botão **Recompile** (no Overleaf) para gerar o PDF atualizado.

> **Nota:** Para usuários avançados que desejam compilar localmente, o repositório inclui um script `build-latex.sh` para sistemas Linux/macOS.

## Personalização

Abra o arquivo `main.tex` e localize a seção **DADOS DO TRABALHO**. Lá você deve preencher:
*   Título do trabalho;
*   Nome do estudante;
*   Nome do orientador;
*   Curso e Campus;
*   Data da banca.

## Repositório Original

A versão mais atualizada deste template pode ser encontrada em:
[https://github.com/eldair-dornelles/Relatorio-de-Estagio-Template-Latex](https://github.com/eldair-dornelles/Relatorio-de-Estagio-Template-Latex)



---
*Desenvolvido para auxiliar os alunos da UNIJUÍ na formatação de seus trabalhos acadêmicos.*
