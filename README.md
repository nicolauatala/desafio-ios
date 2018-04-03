# Aplicativo de consulta a API do [GitHub](https://github.com)#

Aplicativo para consultar a API do GitHub e trazer os repositórios mais populares de Java.

### **Contem** ###

- __Lista de repositórios__. Chamada na API: `https://api.github.com/search/repositories?q=language:Java&sort=stars&page=1`
* Paginação na tela de lista, com endless scroll / scroll infinito (incrementando o parâmetro `page`).
* Cada repositório exibi Nome do repositório, Descrição do Repositório, Nome / Foto do autor, Número de Stars, Número de Forks
* Ao tocar em um item, leva a lista de Pull Requests do repositório
- __Pull Requests de um repositório__. Exemplo de chamada na API: `https://api.github.com/repos/<criador>/<repositório>/pulls`
* Versão mínima do iOS : 8.*
* Storyboard e Autolayout.
* Framework para Comunicação com API.
* Mapeamento json -> Objeto.
* App Universal , Ipad | Iphone | Landscape | Portrait (Size Classes)
* Cache de Imagens. Ex SDWebImage

2018