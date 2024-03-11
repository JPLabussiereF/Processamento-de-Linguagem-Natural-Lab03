# Processo, insights e possibilidades aprendidas durante o conteúdo de **"Análise de Sentimentos com Language Studio no Azure AI"**

## **1. Estúdio de Fala:**

- **Introdução**

A transcrição da fala em texto e a conversão de texto em fala audível por meio da IA são processos-chave na comunicação entre humanos e máquinas. A transcrição da fala em texto usa algoritmos de reconhecimento de voz para converter palavras faladas em texto escrito, enquanto a conversão de texto em fala utiliza sistemas de síntese de voz para transformar texto em uma saída audível.

Ambos os processos têm uma variedade de aplicações, desde assistentes virtuais até acessibilidade para pessoas com deficiência. Apesar de desafios como precisão em ambientes ruidosos e naturalidade na fala sintetizada, o desenvolvimento contínuo impulsiona uma interação mais intuitiva e inclusiva entre humanos e sistemas baseados em IA.

Sabendo disso, podemos através da função de [Conversão de fala em texto em tempo real](https://speech.microsoft.com/portal/3a8202b21299451ca3ac791302c5e372/speechtotexttool), o qual é o serviço Speech, que transcreve e exibe o texto em tempo real. Como também, caso você tenha áudio em seu computador, poderá ouvir a gravação enquanto o texto é transcrito.

- **Exemplo da conversão de fala em texto em tempo real realizada**

![Imagem de Exemplo da conversão de fala em texto em tempo real realizada](https://github.com/JPLabussiereF/Processamento-de-Linguagem-Natural-Lab03/blob/main/Pratica/ExploreSpeechStudio/Outputs/transcricao.png?raw=true)

Arquivo json gerado: [`transcicao.json`](https://github.com/JPLabussiereF/Processamento-de-Linguagem-Natural-Lab03/blob/main/Pratica/ExploreSpeechStudio/Outputs/transcricao.json)

## **2. Analise texto com Language Studio:**

- **Introdução**

A Análise de Sentimentos através de IA é um processo que envolve a utilização de algoritmos e técnicas de inteligência artificial para identificar e compreender as emoções expressas em textos, como opiniões, avaliações, ou mensagens em redes sociais. Essa análise pode classificar o conteúdo em categorias como positivo, negativo ou neutro, além de identificar nuances como ironia ou sarcasmo. 

A IA emprega métodos como aprendizado de máquina e processamento de linguagem natural para extrair significado e contexto das palavras, permitindo empresas e pesquisadores entenderem melhor o sentimento do público em relação a produtos, serviços, eventos ou tópicos específicos. 

Embora apresente desafios como o reconhecimento de sarcasmo e ambiguidades linguísticas, a análise de sentimentos através de IA continua a evoluir, fornecendo insights valiosos para diversas aplicações, como gerenciamento de reputação online, desenvolvimento de produtos e tomada de decisões estratégicas.

Sabendo disso, podemos através da função de [Análise de sentimentos e opiniões](https://speech.microsoft.com/portal/3a8202b21299451ca3ac791302c5e372/speechtotexttool), a qual é um ramo da IA ​​que lida com a linguagem escrita e falada analisando os sentimentos. Assim, fornecendo rótulos de sentimento (como "negativo", "neutro" e "positivo") e pontuações de confiança no nível da frase e do documento.

- **Exemplo da Análise de sentimentos e opiniões realizada**

![Primeira imagem de Exemplo da Análise de sentimentos e opiniões realizada](teste)

![Segunda imagem de Exemplo da Análise de sentimentos e opiniões realizada](teste)

![Terceira imagem de Exemplo da Análise de sentimentos e opiniões realizada](teste)

Arquivo json gerado: [`ResultadosExaminados.json`](teste)


## Referências

 - [DIO - Microsoft Azure AI Fundamentals](https://web.dio.me/track/a088cda7-a37f-451a-b392-46fa7e6ddc55)
 - [Explore Speech Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)
 - [Analyze text with Language Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)

