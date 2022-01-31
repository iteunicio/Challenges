# Back-End Developer - Challenge


## Descrição (Caso de Estudo)
Desenvolver uma API RESTful que permita gerenciar as informações das propriedades dos países (identificador – gerado automaticamente, nome, capital, região, sub-região, área). A partir da API, deve ser possível:
 - Criar um novo país com todas as suas propriedades;
 - Listar todos os países anteriormente criados;
 - Modificar os dados de um país anteriormente criado;
 - Eliminar um país anteriormente criado;
 - Ordenar a lista dos países por qualquer uma das suas propriedades.

## Solução
Foi desenvolvida uma API RESTful baseada em Spring Boot framework e Maven. A informação é armazenada numa base de dados MySQL.
A partir da API, é possível:
 - Adicionar um país (link: https://challenge1-comsol.herokuapp.com/paises).;
 - Apresentar todos países registados (link: https://challenge1-comsol.herokuapp.com/paises);
 - Apresentar todos os países de uma determinada região (link: https://challenge1-comsol.herokuapp.com/paises/regiao/{regiao});
 - Apresentar todos os paises de uma determinada subregião (link: https://challenge1-comsol.herokuapp.com/paises/sub-regiao/{subRegiao});
 - Modificar dados de um país (link: https://challenge1-comsol.herokuapp.com/paises/{id});
 - Apresentar dados de um país pelo id (link: https://challenge1-comsol.herokuapp.com/paises/{id});
 - Apresentar dados de um país pelo nome (link: https://challenge1-comsol.herokuapp.com/paises/{nome});
 - Excluír um país pelo id (ttps://challenge1-comsol.herokuapp.com/paises/{id});
##
 A API foi desenvolvida seguindo o terceiro nível, de acordo com o Modelo de Maturidade de Richardson (https://en.wikipedia.org/wiki/Richardson_Maturity_Model). As informação são divididas em páginas (20 registos por página) e podem ser ordenadas por qualquer uma das propriedades dos países. Cada recurso contém link para outro, de forma que, desde que o cliente tenha acesso a um dos recursos ou através do link inicial é possível navegar e manipular qualquer registos, sem a necessidade de introduzir links de navegação.
##
Todos os dados de entrada são validados (campos obrigatórios validados), de forma a garantir que apenas dados permitidos sejam inseridos na base de dados. A API também trata devidamente excepções de forma a evitar que, caso o cliente insira dados inválido, links mal formados ou mesmo tente executar métodos impróprios, o sistema seja insperadamente paralizado.
## Documentação
Link de acesso à documentação da API: https://challenge1-comsol.herokuapp.com/swagger-ui/
## Execução
O link para executar a API : https://challenge1-comsol.herokuapp.com/paises
## Código fonte
Link de acesso: https://github.com/iteunicio/Challenges
## Contacto
 - Nome: Eunicio de Alberito
 - Email: euniciodealberito.cun@gmail.com
 - Telemóvel: (+258) 845555055 / 879990369
