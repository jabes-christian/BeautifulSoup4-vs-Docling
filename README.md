# Explorando a Extração de Conteúdo Web com BeautifulSoup4 e Docling

Este repositório demonstra a utilização de duas poderosas bibliotecas Python para a extração e o processamento de conteúdo de páginas web: **BeautifulSoup4** e **Docling**.

Utilizamos como referência o artigo "[Google paga Samsung para colocar Gemini em celulares da empresa](https://canaltech.com.br/mercado/google-paga-samsung-para-colocar-gemini-em-celulares-da-empresa/)" do Canaltech para ilustrar como cada biblioteca pode ser empregada na análise de documentos HTML.

## BeautifulSoup4: Navegação e Extração Granular de HTML

**BeautifulSoup4** é uma biblioteca consagrada no ecossistema Python para fazer *scraping* e analisar documentos HTML e XML. Sua interface intuitiva permite navegar pela estrutura do documento, buscar elementos específicos e extrair os dados desejados de forma eficiente.

No contexto deste repositório, demonstramos como usar o BeautifulSoup4 para:

* Fazer uma requisição HTTP para a página do Canaltech.
* Analisar o conteúdo HTML da resposta.
* Extrair todo o texto visível da página, ilustrando uma forma básica de obter o conteúdo principal do artigo.

O código de exemplo para trabalhar com BeautifulSoup4 pode ser encontrado [**[LINK PARA O ARQUIVO BEAUTIFULSOUP NO SEU REPOSITÓRIO]**].

## Docling: Processamento Robusto e Conversão de Formatos

**Docling** é uma biblioteca mais recente que visa simplificar o processamento de diversos formatos de documentos, incluindo HTML, PDF, DOCX e outros. Ela oferece uma abordagem unificada para a análise e conversão de documentos, com recursos avançados como compreensão de layout em PDFs e integração com ferramentas de IA generativa.

Neste repositório, exploramos o uso do Docling para:

* Converter o conteúdo HTML da mesma página do Canaltech para o formato Markdown. Isso demonstra a capacidade do Docling de não apenas analisar o HTML, mas também de transformá-lo em outros formatos estruturados.

O código de exemplo para trabalhar com Docling pode ser encontrado [**[LINK PARA O ARQUIVO DOCLING NO SEU REPOSITÓRIO]**].

## Conclusão

Este projeto oferece um ponto de partida prático para entender como **BeautifulSoup4** e **Docling** podem ser aplicadas na extração e no processamento de conteúdo de documentos HTML. Enquanto BeautifulSoup4 se destaca pela sua flexibilidade e controle granular sobre a estrutura do HTML, Docling oferece uma solução mais abrangente para lidar com múltiplos formatos e realizar conversões de maneira simplificada. A escolha da biblioteca ideal dependerá das necessidades específicas do seu projeto.
