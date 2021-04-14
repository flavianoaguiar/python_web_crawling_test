![Dataminer](http://www.dataminerdbm.com.br/wp-content/uploads/2020/10/logomarca-1x.png)

# Teste para recrutamento de desenvolvedores Python - Web Crawling e Scraping ( Pleno )

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

## Instruções

Clone este repositório com o comando abaixo para acessar os arquivos necessários.

```
git clone https://github.com/dataminerdbm/python_web_crawling_test.git
```

### Dicas de bibliotecas e comandos a serem usados

- beautifulsoup4, scrapy, sellenium, requests, urllib3, re, jsonify, multiprocessing, concurrent, ThreadPoolExecutor


---

## Desafio 1 ( criar o arquivo desafio1.py )

Desenvolver uma solução em Python para resolver as seguintes tarefas:

1) Ler o arquivo response.html, que se encontra neste repositório;
2) Realizar o parser dos dados conforme o JSON abaixo;
3) Salvar o JSON em um arquivo de nome desafio1.json ( criar o arquivo )

desafio1.json ( Exemplo ):

```json

{
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
}

```

---

## Desafio 2 ( criar o arquivo desafio2.py )

Usando as técnicas de web crawling e scraping (human-like) que você conhece, realize as seguintes tarefas:

1) Acessar o link http://www.freeproxylists.net/ e capturar a lista de proxies até a página 7, usando uma thread para cada página da paginação executando simultâneamente.
2) Salve a lista completa de proxies ( até a página 7 ) no arquivo desafio2.json ( criar o arquivo )
3) Imprimir a quantidade de proxies capturados


desafio2.json ( Exemplo ):

```json 

[
    {
        "ip":"1.1.1.1",
        "porta":"8080"
    },
    ...
    ...
    {
        "ip":"999.999.999.999",
        "porta":"5000"
    }
]
```

# Conclusão

O projeto final deve conter os seguintes arquivos:

- README.md
- response.html
- desafio1.py
- desafio1.json
- desafio2.py
- desafio2.json
- requeriments.txt ( lista de bibliotecas necessárias para a execução )
- OBSERVACOES.md ( Opcional, use se achar necessários fazer alguma observação )

**Disponibilize em um repositório na sua conta do Github ou Gitlab e envie o link para o tech recruiter.**