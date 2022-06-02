## Building Conversao-Temperatura 

#### Sobre a Aplicação

### Obtida por meio de fork do projeto do Desenvolvedor Fabricio Veronez
### URL do Projeto no GitHub ==> https://github.com/KubeDev/conversao-temperatura

- Aplicação usada para converter a temperatura em "Celsius" para "Temperatura" e vice-versa através de um frontend simples.
- Porta de execução: 8080
- Escrita em NODEJS

## Docker

Caso queira não queira usar o Dockerfile oferecido nesse repositório você pode clonar o projeto e fazer seus próprios ajustes no Dockerfile e gerar sua imagem local.

$ ```git clone https://github.com/ricellirousselet/conversao-temperatura.git```

$ ```docker build -t <image-name> .```

#### Usando a aplicação "Conversao-Temperatura" - Dockerfile do Projeto

## Versão Latest (1)

$ ```docker run -d -p 8080:80 --name conversao-temperatura ricellirousselet/conversao-temperatura```

## Versão 1

$ ```docker run -d -p 8080:80 --name conversao-temperatura ricellirousselet/conversao-temperatura:1```

## Acessando container "conversao-temperatura"

$ ```docker container exec -it conversao-temperatura /bin/sh```

