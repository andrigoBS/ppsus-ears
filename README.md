# ppsus-ears (Meu primeiro alô)
Projeto de cunho social, visando acompanhar bêbes que testam negativo no teste da orelinha. A plataforma 
é pensada para ajudar pais, fonoaudiologas, orgãos governamentais e hospitais terem um maior controle e acompanhamento
desses casos.

### Git commands
- git clone --recurse-submodules
- git submodule update --remote <nome-do-submódulo>
- git submodule update --init --recursive

### Instalação do ambiente de desenvolvimento com docker
- Duplique o arquivo .env.exemple removendo .exemple
- Configure os parametros como desejar, obs host_name deve ser um ipv4
- Instale o projeto usando `docker-compose build` 
- E rode com `docker-compose up`
- Ou se preferir use `docker-compose up --build` para "buildar" antes de rodar

## Autores
O presente código foi implementado por:
* [Andrigo B. Santos](https://github.com/andrigoBS)
* [Gabriel Burich](https://github.com/gabrielburich)
* [Hilson A. W. Junior](https://github.com/Hilson-Alex)

## Links
**Como instalar o wsl do windows para rodar o docker via wsl**
- https://docs.microsoft.com/pt-br/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package

**Tutorial de docker legal**
- https://blog.rocketseat.com.br/introducao-ao-docker-criando-um-servidor-web-com-node-js-e-subindo-para-o-container/
