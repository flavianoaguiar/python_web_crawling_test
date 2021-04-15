![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste de avaliação para seleção de desenvolvedores Python - Web Scraping e Crawlers ( Junior )

## Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo. Antes de iniciar, esteja num ambiente tranquilo e confortável, pense no problema e na melhor forma de resolvê-lo.
O nosso objetivo com este desafio é conhecer você como desenvolvedor. Por isso, não vamos estabelecer nenhum tipo de restrição sobre padrões de projeto, organização de código, bibliotecas ou boas práticas. Nossa única exigência é que seja escrito em Python 3. Esteja à vontade para programar da maneira que mais gosta, e que você tenha autonomia para construir o projeto do seu jeito, com as suas regras e no seu estilo.

---

## Pré-Requisitos

- Python 3
- Conta no Github ou Gitlab 
- Editor ou IDE de sua preferência 

####***Dicas de bibliotecas e comandos úteis***

- beautifulsoup4, scrapy, sellenium, requests, urllib3, re, jsonify, multiprocessing, concurrent, ThreadPoolExecutor, aiohttp

---

## Instruções

Utilize as técnicas de web crawling/scraping ( "human-like / like a human" ) que você conhece, para realizar as seguintes tarefas:

1) Acesse o link http://www.freeproxylists.net e capture a lista de proxies ( até a página 7 ), considere usar threads para melhorar o tempo de execução.
2) Realize o parser dos dados de ip,porta,protocolo,país e uptime.
3) Save a lista de proxies em um arquivo com nome proxies.json, conforme exemplo abaixo.
3) Imprima a quantidade de proxies capturados e o tempo de execução.

proxies.json ( Exemplo ):

```json 

[
    {
        "ip":"1.1.1.1",
        "porta":"8080",
        "protocolo":"HTTP",
        "pais":"BRAZIL",
        "uptime":"32.8%"
    },
    ...
    ...
    {
        "ip":"999.999.999.999",
        "porta":"5000",
        "protocolo":"SOCKS5",
        "pais":"CHINA",
        "uptime":"80%"
    }
]
```

##### Não há um prazo pré-estabelecido para a conclusão deste teste, porém o prazo utilizado será considerado para desempate

---

## Resultado

O repositório esperado deve conter os arquivos abaixo mais o que você achar necessário para melhor solucionar o problema:

- **requeriments.txt** ( lista de bibliotecas não nativas necessárias para a execução )
- **README.md** -> Faça suas observações, instruções de instalação e execução. Aproveite para compartilhar outros repositórios(link) que demonstre melhor seu conhecimento.E/Ou escreva algo que você considera importante nessa área, como por exemplo, o que fazer para evitar o bloqueio de um crawler pelas tecnologias de segurança existentes atualmente, como captchas e regras de firewalls(Ex.: bloqueio de IP). Todo conhecimento demonstrado será considerado na sua avaliação.

###### Opcionalmente você pode adicionar o Dockerfile. Será um grande diferencial. 

---

## **Disponibilize o repositório na sua conta do Github ou Gitlab e envie o link para o contato abaixo**
---
### Contato

Fique à vontade para entrar em contato conosco através do e-mail flaviano.aguiar@dataminerdbm.com.br para tirar dúvidas. 
