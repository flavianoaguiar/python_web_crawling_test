![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste de avaliação para seleção de desenvolvedores Python - Web Scraping e Crawlers ( Junior )

## Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo.

Antes de iniciar, esteja num ambiente tranquilo e confortável, pense no problema e na melhor forma de resolvê-lo.

Não estamos avaliando apenas o resultado final, mas como foi pensado e implementado, boas práticas de desenvolvimento contam muito, comente no seu código.

Qualquer dúvida, pode entrar em contato com o tech recruiter.

---

## Pré-Requisitos

- Python 3
- Conta no Github ou Gitlab 
- Editor ou IDE de sua preferência 

### Dicas de bibliotecas e comandos úteis

- beautifulsoup4, scrapy, sellenium, requests, urllib3, re, jsonify, multiprocessing, concurrent, ThreadPoolExecutor, aiohttp

---

## Desafio ( Instruções )

Nome do arquivo: scrapyTest.py

Utilize as técnicas de web crawling/scraping ( "human-like / like a human" ) que você conhece, para realizar as seguintes tarefas:

1) Acesse o link http://www.freeproxylists.net e capture a lista de proxies ( até a página 7 ), executando uma thread para cada página simultâneamente.
2) Realize o parser dos dados de ip,porta,protocolo,país e uptime para uma lista ( list->[] ) de dicionários( dict->{} ). 
3) Converta a lista em json formatado ( jsonify ) e salve em um arquivo ( proxies.json ), conforme exemplo abaixo.
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

## Resultado

O repositório esperado deve conter os seguintes arquivos:

- scrapyTest.py
- proxies.json
- requeriments.txt ( lista de bibliotecas não nativas necessárias para a execução )
#### **Opcional:**
- Dockerfile ( diferencial )
- README.md -> Faça suas observações, instruções de instalação e execução e aproveite para compartilhar outros repositórios(link) que demonstre melhor seus conhecimentos ou escrever algo que você acha importante para evitar o bloqueio de um crawler, por exemplo. Todo conhecimento demonstrado será considerado.

Não há um prazo para devolução, mas o tempo de resposta será considera na sua avaliação.


## **Disponibilize o repositório na sua conta do Github ou Gitlab e envie o link para o tech recruiter**

