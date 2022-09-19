# Projeto CleanArchitecture

Desenvolvido aplicando os conhecimentos adquiridos apos estudo.
Focando sempre na qualidade do codigo, baixo acoplamento e baixa dependencia entre as camadas

## Camadas de alto nível 

### Camada Domain
Responsável por aplicar as regras de negócio 

### Camada Application
Repsonsavel por regras dos serviços
##
### Camada Infra.Data
Contêm as dependências para logica de acesso ao dados utilizando Entity Framework core

### Camada Infra.IOC
Realiza a injenção de dependencia usado pelas camadas controlando o baixo acoplamento entre as camadas

### Camada WebUi
Responsavel pela apresentação do projeto.
Obs: lembrando que o foco do projeto é no backend e estruturação do projeto.
