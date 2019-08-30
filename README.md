# abntex2ufop

## O que é o AbnTeX2UFOP?
É um modelo completo em LaTeX (template) adapdado para trabalhos acadêmicos, como monografias, dissertações ou teses, de acordo com as normas ABNT, subordinadas às exigências do Departamento de Engenharia de Controle & Automação da Universidade Federal de Ouro Preto (UFOP). Não se trata de uma utilização ampla das 'normas' ABNT, mas é uma aplicação possível delas, já que as recomendações da ABNT são, em alguns aspectos, contraditórias. Convém sempre conversar com os orientadores ou orientadoras do seu programa de pós-graduação sobre as vantagens de se utilizar tal modelo, antes de adotá-lo. 

## Como utilizar?
Faça o download dos arquivos deste repositótio, incluindo o arquivo de classe "abntex2ufop.cls" para a pasta do seu projeto. Em qualquer editor LaTeX, basta editar o arquivo principal "abntex2-modelo-trabalho-academico.tex" e os arquivos da pasta "capítulos". Este modelo é livre e obedece à licença pública padrão do LaTeX (LPPL) versão 1.3 ou superior, e pode ser compilado com o pdflatex.
Se você está dando os primeiros passos, [é bom ver isso primeiro.](https://github.com/tonidandel/abntex2ufop/wiki)

# abntex2ufop + BibLaTeX-ABNT ou "LaTeX para Filósofos"

## Por que LaTeX para filósofos?
Este modelo utiliza o sistema de citações em notas de rodapé com nomenclatura reduzida, tal como op. cit., idem, ibidem etc, bem comum às Ciências Humanas. É ideal para escritores que desejam fazer notas bibliográficas e comentários ao longo do texto em notas de rodapé, o que é permitido pelas 'normas' ABNT. É um modelo bonito e elegante, ideal para grandes volumes de texto. Este modelo segue a Licença Pública Padrão do LaTeX (LPPL).

## Do que se trata este modelo?
O LaTeX para Filósofos é um modelo aplicável em todas as áreas, e serve também para as monografias do departamento de Engenharia de Controle e Automação da UFOP. Ele utiliza a classe abntex2ufop mais o estilo de formatação de bibliografia biblatex-abnt, que é um estilo que foca na qualidade da apresentação das referências, sem a preocupação com regras estilísticas, que são definidas pela classe escolhida. Esse estilo é ideal também para a rápida conversão para outros idiomas, e funciona muito bem com hyperlinks e referências cruzadas. Embora tenha sido adaptado às necessidades da UFOP, o modelo pode ser facilmente alterado para qualquer instituição, desde que se substuam as imagens das logomarcas unidade e universidade, que ficam na pasta principal.

## Como usar?
Para usar este modelo, você deve compilar o trabalho utilizando um compilador XeTeX para o texto e o Biber para as referências biliográficas. Basta alterar as opções de compilação em qualquer edir LaTeX (como Texstudio, TeXMaker ou Overleaf). O estilo biblatex-abnt é mais poderoso e simples no quesito de formatação de estilo de referências, além de inúmeras outras vantagens. Vale lembrar que este modelo é incompatível com pdflatex, embora gere um arquivo PDF como qualquer outro.

Bons estudos!

Danny Tonidandel.
