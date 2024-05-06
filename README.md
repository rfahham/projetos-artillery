# projetos-artillery
Artillery é uma plataforma de teste de carga de código aberto. Ele contém tudo que você precisa para passar rapidamente do zero ao teste de carga de nível de produção.

## Instalação

```bash
npm install -g artillery@latest
```

## Requisitos de sistema

O Artillery é executado em sistemas Windows, MacOS e Linux e requer a versão LTS mais recente do Node.js..

## Verifique se o Artillery está instalado executando:

```bash
npx artillery dino
```
    ------------
    < Artillery! >
    ------------
            \
             \
              __
             / _)
      .-^^^-/ /
   __/       /
  <__.|_|-|_|


## Verificando a versão instalada

```bash
artillery version
```

            ___         __  _ ____
      _____/   |  _____/ /_(_) / /__  _______  __ ___
     /____/ /| | / ___/ __/ / / / _ \/ ___/ / / /____/
    /____/ ___ |/ /  / /_/ / / /  __/ /  / /_/ /____/
        /_/  |_/_/   \__/_/_/_/\___/_/   \__  /
                                        /____/

    VERSION INFO:

    Artillery: 2.0.11
    Node.js:   v20.12.2
    OS:        linux

## Criando o script de teste

## Executando o script

```bash
artillery run asciiart-load-test.yml
```