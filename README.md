# Bootcamp Dio - Microsoft Azure AI Fundamentals.
Reconhecimento Facial e transformação de imagens em Dados no Azure ML.

Neste Projeto, tem como objetivo praticar a criação de reconhecimento facial, identificação de dados em documentos e também o reconhecimento de elementos em imagens. Através desse projetino(Lab),será possível fixar melhor o que foi excplicado e realizados nas aulas, proporcionando uma compreensão mais profunda e prática desses conceitos essenciais.


## Azure AI – Vision Studio - Detectar rostos com o Face Service.
<p>Dentre os serviços de IA do Azure. O serviço de detecção de rostos, objetos em imagem, incluindo atributos extras como pose, máscara facial e pontos de referências faciais, é um serviço que permite que nos possibilita a implantação de recursos como:</p>
      <p>1. Segurança(Correspondência de Similaridade) - Liberar apenas funcionários que estão previamente cadastrados com suas devidas imagem coletada. De posse destas imagens dar acesso ou negar em determinado ponto(lugar físico) onde o mesmo pode adentrar. Serviço que pode ser aplicado em Sistemas de diversos para dar acesso o negar.</p>
      <p>1. Em conjunto com IOT, disparar alarmes em caso da similaridade não for exata bem como outras implementações que forem necessárias para o caso uso. Abre um leque de implementações que podemos fazer uso do Face Service.</p>
<p>Ainda no Vision Studio, é possível:</p>
      <p> 1. Conferir a documentação.</p>
      <p> 2. Entender um pouco mais sobre com exemplos no Github.</p>
      <p> 3. Fazer uso da API Rest.</p>
Visão Geral do Vision Studio.

![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/3dba686f-2986-4511-b780-5772774be89b)

O processo é bem simples e muito intuitivo. Basta carregar a imagem desejada e temos algumas informações da mesma mostradas na guia - Detected Atributes ou em Json na guia Json. Como mostra a seguir.

![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/14b71504-1bb0-4202-b9f4-3e2b4427806a)
![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/6a5ce446-6ecf-448d-9d99-2634aa4e6deb)

Podemos então(“Meio que obvio”) ver na detecção de atributos que a imagem carregada gerou como resultado 1 Rosto(Face) sem Máscara Facial para esta imagem carregada.
Para implementação em uma aplicação ainda podemos contar com um “Código de Amostra”.Basta Selecionar a Linguagem que servirá para codificar a implementação.
![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/42dd987d-1c53-4769-92c1-a25079d9549f)

## Azure AI – Vision Studio - Extraia texto de imagens.

 API Reade extrair texto impresso e manuscrito em idiomas suportados de imagens, PDFs e arquivos TIFF. O recurso de reconhecimento óptico de caracteres (OCR) oferece suporte a imagens e documentos com idiomas mistos e não exige a especificação do idioma. 
 O uso para esta API também podem ser diversos, desde da leitura de uma Nota Fiscal, a qualquer documento ou imagem que seja necessário.
Como por exemplo podemos usar este recurso para extrair texto de livros físicos que não se encontram mais a venda, livros raros. É com isso extrair o conteúdo em texto das páginas digitalizadas e posteriormente usar de muitas formas exemplo: Comparar o texto de um autor de um livro antigo com um autor dos dias atuais a fim de encontrar algum padrão de semelhança na elaboração do texto, como ambos autores se expressão, se há alguma parte até mesmo plagiada!

![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/a9390bb4-3096-4360-a1e1-0cf737cfb8e1)

O processo neste caso também é bem simples e muito intuitivo. Basta carregar a imagem desejada e temos algumas informações da mesma mostradas na guia - Detected Atributes ou em Json na guia Json. Como mostra a seguir. É possível extrair qualquer informação como mostra na imagem a informação do cnpj contido na nota fiscal carregada.

![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/dae1a20c-0acd-4dc0-a789-e30cc80dcd91)

## Azure AI – Vision Studio - Adicione legendas às imagens.

Gera uma frase legível que descreva o conteúdo de uma imagem. Ao usar este serviço conseguimos acessibilidade, por exemplo, para uma pessoa cega. Com o uso deste serviço é possível obter esta descrição dos elementos que contém a imagem, em seguida podemos utilizar outros recursos para ler estas legendas que são descritas e com isso a pessoa com deficiência de visão poder acompanhar.
 O uso também e simples e intuitivo basta carregar a imagem que se deseja a descrição dos elementos contido na mesma. Como mostra a imagem a seguir.

 ![image](https://github.com/AdrianoProfileAdsCloud/Prj2-AI-900/assets/141897391/7188bfa8-8097-4fe5-8600-ac402f6ca67f)
