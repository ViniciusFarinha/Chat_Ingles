# Fique fluente em Inglês!


[![author](https://img.shields.io/badge/author-ViniciusFarinha-blue.svg)](https://www.linkedin.com/in/viniciusfarinha/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-blue.svg?style=flat)](https://github.com/ViniciusFarinha)

Chat criado usando api da openai para ajudar as pessoas à treinar o inglês em pegar a fluência. Destinado para pessoas que tem timidez ou querem treinar um pouco mais antes de conversar com um nativo. 

O projeto ainda está em desenvolvimento! E você pode contribuir. Entre em contato comigo pelas minhas redes se tem interesse de colaborar.

<p align="center">
  <img src="foto capa.png" >
</p>

# Objetivo

O objetivo do projeto é criar uma inteligencia artificial capaz de treinar a sua fluência em inglês. E como ela faria isso?

                             ┌─────────────────┐
                             │ Você manda um   │ 
                             │  áudio. Ele é   │
                             │  transcrito.    │
                             │                 │
                             └─────────────────┘
                                      │
                                      ▼
                       ┌──────────────────────────────┐
                       │ Seu áudio é enviado em texto │
                       │    para a api da openia e    │
                       │     ela gera uma resposta.   │
                       │                              │
                       └──────────────────────────────┘
                                      │
                                      ▼
                             ┌────────────────────┐
                             │    Resposta da     │
                             │openia transformada │
                             │de texto para audio │
                             │                    │  
                             └────────────────────┘

# Speech-to-Text

Aqui eu tenho usado a biblioteca _speech_recognition_ que é capaz de acessar o seu microfone e captar a sua fala. Assim a biblioteca capta o que você falou e transforma em áudio com o _recognize_google_.

# API OPEN AI

Nesta a parte vocÊ terá que gerar uma API da openai para conseguir prosseguir. No código, a função anterior que captava sua voz e gerava um texto com o que você disse, armazena esse texto em uma variável que é enviada como content para a api. 
Assim, a IA gera uma resposta baseada no que vocÊ disse e te entrega um texto. Este texto é armazenado em outra variável.

# Text-to-Speech
Por fim, a variável gerada pela IA é entregue para a biblioteca _gtts_ e gera um áudio de qualidade excelente com base no texto captado.


# Dificuldades do projeto

<p align="center"> ** Caso tenha se interessado pelo meu trabalho, te convido a conhecer minhas redes sociais. Obrigado! ** </p>

<p align="center">
  <img src="Logo.png"  width="400" height="350" >
</p>


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/viniciusfarinha) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ViniciusFarinha)[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white)]( https://viniciusfarinha.my.canva.site/)
      
