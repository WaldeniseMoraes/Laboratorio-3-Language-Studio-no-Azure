# Laboratório-3
***
# Análise de Sentimentos com Language Studio no Azure AI.
***
A análise de sentimentos é uma técnica de processamento de linguagem natural (NLP) que permite identificar e extrair opiniões dentro de um texto. O Azure Language Studio oferece uma plataforma robusta para criar modelos personalizados de ML para processamento de texto, incluindo a análise de sentimentos. Vamos explorar como você pode realizar um laboratório de análise de sentimentos usando o Azure Language Studio.

## Introdução ao Azure Language Studio.
***

O Azure Language Studio é uma ferramenta intuitiva que permite aos desenvolvedores e cientistas de dados construir e treinar modelos de ML personalizados para classificação de texto, extração de entidades, modelos conversacionais e de perguntas e respostas. Além disso, oferece recursos pré-construídos de NLP que podem ser testados visualmente, como extração de frases-chave, análise de sentimentos e sumarização1.

### Configurando o Laboratório de Análise de Sentimentos.

Para começar, você precisa de uma assinatura do Azure e configurar um recurso de Language no portal do Azure.

**Precisa criar recurso no** _*+ create a resource:*_

![Captura de Tela (130)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/2a89af95-870b-473f-9d47-ece58de3f76f)

**Entrar em categorias e selecionar** _*AI + Machine Learning:*_

![Captura de Tela (131)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/88e8013e-eb5e-4d72-a25b-901af599c92c)

**Selecionar** _*Language service:*_

![Captura de Tela (152)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/581f718f-22c9-4575-96b8-1078df038602)

**Selecionar recursos adicionais e selecione** _*Continue to create your resource:*_

![Captura de Tela (153)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/02b688f2-668d-4305-bbab-6c0204ca66cc)

**Marque** _*check box:*_

![Captura de Tela (155)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/02f1157a-bf1e-4000-a32a-ac4b11f45b7e)

***Confirmação de criação do recurso***  _*Language service:*_

![Captura de Tela (158)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/4663fa0c-628d-4ad0-a15d-cc6a1eda1388)

## Análise de Sentimentos de Avaliações de Hotéis com Azure Language Studio.
***

A análise de sentimentos é uma técnica de processamento de linguagem natural que identifica e classifica opiniões expressas em textos. O Azure Language Studio, uma ferramenta da Microsoft Azure, permite realizar essa análise de forma eficiente e precisa. Neste artigo, exploraremos como o Azure Language Studio pode ser utilizado para analisar uma avaliação de hotel, identificando pontos positivos e negativos expressos pelo cliente.

## Avaliação do Hotel: The Seaside Oasis:

**Aspectos Positivos:**
* **Vistas Deslumbrantes do Oceano:** O hotel oferece vistas impressionantes do oceano a partir de seus quartos e varandas, permitindo que os hóspedes acordem com o som das ondas e desfrutem de pôr do sol fascinantes.
* **Equipe Atenciosa:** Os funcionários do hotel são amigáveis e sempre prontos para ajudar, melhorando significativamente a experiência geral dos hóspedes.
* **Quartos Limpos e Bem Conservados:** A limpeza impecável e a manutenção dos quartos garantem uma estadia agradável.
* **Opções Deliciosas de Refeições:** O restaurante do hotel oferece pratos saborosos de frutos do mar e especialidades locais, complementados pela vista do oceano.
* **Serviços Relaxantes de Spa:** O spa do hotel proporciona massagens e tratamentos rejuvenescedores, ideais para relaxar após um dia de passeio.

  **Aspectos Negativos:**
  * **Estacionamento Limitado:** A falta de vagas de estacionamento pode ser um problema durante a alta temporada, causando frustração aos hóspedes.
  * **Níveis de Ruído:** Alguns quartos voltados para a rua sofrem com o barulho do tráfego, o que pode perturbar o sono de hóspedes mais sensíveis ao ruído.
  * **Decoração Antiquada:** Apesar da limpeza, a decoração ultrapassada dos quartos poderia ser modernizada para melhorar o ambiente.
  * **Wi-Fi Inconsistente:** O sinal de Wi-Fi pode ser fraco em algumas áreas, o que é inconveniente para viajantes a negócios.
  * **Longos Tempos de Espera no Check-In:** Durante períodos movimentados, os hóspedes podem enfrentar atrasos no balcão de recepção, o que poderia ser otimizado.

### Utilizando o Azure Language Studio para Análise de Sentimentos.

Para realizar a análise de sentimentos dessa avaliação no Azure Language Studio, seguiríamos os seguintes passos:

1. **Acesse o Azure Language Studio:** Vá para o Language Studio e selecione a opção de análise de sentimentos.

![Captura de Tela (159)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/ea355943-2902-431b-8ced-69fd36ba6eaf)

**Selecione** _*Classify text:*_

![Captura de Tela (159)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/e7d5cc70-fe38-40b8-9841-200db9375f12)

**Selecione** _*Analyse sentiment and mine opinions:*_

![Captura de Tela (160)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/f709fbb8-610d-4e3c-b1d2-1ceb79fca115)

**Copie o texto na caixa de texto e sekecione o idioma:**

![Captura de Tela (162)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/0b52d133-e7bc-4d44-8b7d-441187d15dcd)

**Marque check box e clique no botão RUN:**

![Captura de Tela (163)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/c548567e-04e9-4058-b0c9-f89aba61dd3e)

**Análise de sentenças:**

![Captura de Tela (165)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/8158370d-47bd-4957-b672-9bfcb6b0d8b8)

**Análise de sentimentos:**

![Captura de Tela (164)](https://github.com/WaldeniseMoraes/Laboratorio-3-Language-Studio-no-Azure/assets/161647255/cd546a95-66fa-4b9e-998d-1fa1886c59d6)

2. **Análise de Sentimentos:** Utilizaríamos a funcionalidade de análise de sentimentos do Language Studio para processar o texto e identificar as emoções associadas a cada aspecto mencionado.
3. **Interpretação dos Resultados:** O Language Studio forneceria uma pontuação de sentimento para cada aspecto, permitindo-nos entender melhor as impressões do cliente sobre o hotel.

## Conclusão

A análise de sentimentos é uma ferramenta valiosa para entender as opiniões dos clientes e melhorar os serviços oferecidos. Com o Azure Language Studio, hotéis como o Seaside Oasis podem analisar avaliações de forma rápida e eficaz, identificando áreas de sucesso e oportunidades de melhoria. Ao aplicar essa tecnologia, os estabelecimentos hoteleiros podem aprimorar a experiência dos hóspedes e fortalecer sua reputação no mercado.

O Azure Language Studio se mostra, portanto, como uma solução avançada para a análise de sentimentos, oferecendo insights detalhados que podem ser decisivos para o sucesso no setor hoteleiro.
