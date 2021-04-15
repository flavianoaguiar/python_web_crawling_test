![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste de avaliação para seleção de desenvolvedores Python - Web Scraping e Crawlers ( Junior )

## Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo. Antes de iniciar, esteja num ambiente tranquilo e confortável, pense no problema e na melhor forma de resolvê-lo.
O nosso objetivo com este desafio é conhecer você como desenvolvedor. Por isso, não vamos estabelecer nenhum tipo de restrição sobre padrões de projeto, organização de código, bibliotecas ou boas práticas. Esteja à vontade para programar da maneira que mais gosta, e que você tenha autonomia para construir o projeto do seu jeito, com as suas regras e imprimindo o seu estilo.

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

---

## Resultado

O repositório esperado deve conter os arquivos abaixo mais o que você achar necessário para melhor solucionar o desafio:

- **requeriments.txt** ( lista de bibliotecas não nativas necessárias para a execução )
- **README.md** -> Faça suas observações, instruções de instalação e execução e aproveite para compartilhar outros repositórios(link) que demonstre melhor seu conhecimento ou escreva algo que, por exemplo, você considera importante para evitar o bloqueio de um crawler pelas regras de segurança atuais. Todo conhecimento demonstrado será considerado na sua avaliação.

**Opcionamente você pode incluir o arquivo para execução em container Docker ( Dockerfile )** 

Não há um prazo pré-estabelecido para a conclusão, mas o tempo será considerado na sua avaliação.

## **Disponibilize o repositório na sua conta do Github ou Gitlab e envie o link para o tech recruiter**

