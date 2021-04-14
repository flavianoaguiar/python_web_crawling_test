![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste para recrutamento de desenvolvedores Python - Web Crawling e Scraping ( Pleno )

## Introdução

Este é um teste prático para avaliar conhecimentos do candidato durante seu processo 
seletivo.

Antes de iniciar, esteja num ambiente tranquilo e confortável, pense no problema e a melhor forma de resolvê-lo.

Não estamos avaliando apenas o resultado final, mas como foi pensado e implementado, boas práticas de desenvolvimento contam muito, comente no seu código.

Qualquer dúvida, pode entrar em contato com o tech recruiter.

---

## Pré-Requisitos

- Python 3
- Conta no Github 
- Editor ou IDE de sua preferência 

## Instruções

Clone o repositório com o comando abaixo para baixar os arquivos necessários.

```
git clone https://github.com/dataminerdbm/python_web_crawling_test.git
```

**Solucione os dois desafios abaixo e disponibilize em seu repositório privado. Envie o link para o tech recruiter.**

### Sugestões de bibliotecas e comandos a serem usados

- Beautiful Soup
- Scrapy
- Sellenium
- Requests
- re
- jsonify
- pprint
- dict, list


---

## Desafio 1 ( desafio1.py )

Desenvolver uma solução em Python para resolver as seguintes tarefas:

1) Ler o arquivo response.html, que se encontra neste repositório;
2) Realizar o parser dos dados conforme o JSON abaixo;
3) Salvar o JSON em um arquivo de nome desafio1.json

desafio1.json ( exemplo )

```json

{
    "result": {
        "cpf": "112.348.828-25",
        "nome": "MARIA ISABEL MESSIAS",
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


## Desafio 2 ( desafio2.py )

Usando as técnicas de web crawling e scraping (human-like) que você conhece, realize as seguintes tarefas. 

1) Capturar todos os IPs e PORTAS da página 1 do site http://www.freeproxylists.net/ e os links da paginação ( até a página 7 ). 
2) Salvar a lista de proxies no arquivo desafio2Proxies.json
3) Salvar a lista de links da paginação ( até a página 7 ), no arquivo desafio2Pages.json


desafio2Proxies.json ( Exemplo ):

```json 

[
    {
        "ip":"1.1.1.1",
        "porta":"8080"
    },
    ...
    {
        "ip":"999.999.999.999",
        "porta":"5000"
    }
]

```

desafio2Pages.json ( Exemplo ):

```json 

[
    "http://www.freeproxylists.net/?page=2",
    "http://www.freeproxylists.net/?page=3",
    "http://www.freeproxylists.net/?page=4"
]

```


