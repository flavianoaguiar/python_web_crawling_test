![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste para avaliação de desenvolvedores Python - Web Crawling e Scraping de nível pleno

## Introdução
Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo.

Antes de iniciar, esteja num ambiente tranquilo e confortável, pense no problema
e a melhor forma de resolvê-lo.

Não estamos avaliando apenas o resultado final, mas como foi pensado e implementado.

Qualquer dúvida, pode entrar em contato com o tech recruiter.

Clone o repositório com o commando abaixo para iniciar o seu teste:

```
git clone https://github.com/dataminerdbm/python_web_crawling_test.git
```

**Ao final do teste dê o commit com seu nome completo no comentário e faça o push**

## Requisitos

- Python 3
- Git
- Editor ou IDE de sua preferência 

### Sugestões de bibliotecas e comandos a serem usados

- Beautiful Soup | Scrapy
- Requests
- re
- jsonify
- pprint
- dict, list


---

## Desafio 1

Desenvolver um script em Python que realize as seguintes tarefas:

1) Ler o arquivo response.html, que se encontra neste repositório;
2) Realizar o parser dos dados conforme o JSON abaixo;
3) Salvar o JSON em um arquivo de nome jsonResult.json

jsonResult.json ( exemplo )

```json

{
    "result": {
        "cpfNumerico": "11234882825",
        "cpfFormatado": "112.348.828-25",
        "nomeCompleto": "MARIA ISABEL MESSIAS",
        "dataNascimento": "19/09/1964",
        "dataInscricao": "anterior a 10/11/1990",
        "protocolo": "F36E.8EC4.686D.422F",
        "protocoloDigitoVerificador": "03",
        "protocoloHora": "00:27:06",
        "protocoloData": "04/02/2021",
        "situacaoCadastral": "REGULAR",
        "anoObito": "2020",
        "dataHoraExecucao": "14/04/2021 11:49:10"
    },
    "cod": 1,
    "msg": "OK"
}

```

---


## Desafio 2

1) Capturar todos os IPs e PORTAS da página 1 do site http://www.freeproxylists.net/ e os links da paginação. 
2) Salvar lista de proxies no arquivo jsonProxies.json
3) Salvar lista de links da paginação no arquivo jsonPages.json



jsonProxies.json ( Exemplo ):

```json 

[
    {"ip":"1.1.1.1","porta":"8080"},
    ...
    {"ip":"999.999.999.999","porta":"5000"}
]

```

jsonPages.json ( Exemplo ):

```json 

[
    "http://www.freeproxylists.net/?page=2",
    "http://www.freeproxylists.net/?page=3",
    "http://www.freeproxylists.net/?page=4"
]

```


