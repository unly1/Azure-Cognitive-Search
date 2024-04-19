# Azure Cognitive Search

## Problema 
Explorar a configuração de uma pesquisa revela um caminho rico em descobertas: desde o meticuloso passo a passo da sua configuração até a profunda análise dos insights obtidos. Durante esse processo, não apenas desvendamos as possibilidades de diversas ferramentas que se beneficiam desse método, mas também adquirimos valiosos aprendizados sobre os nuances da coleta e interpretação de dados.

[Documentação: Explore an Azure AI Search index (UI)](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)

### Criando recurso do Azure AI Search:
![1 - Azure AI Service](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/6acc5a5e-71e8-4ec6-aa07-7b889dd1dffa)
![1 1 - Azure Search](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/3a8f8736-6549-4124-a044-6f2d4698c666)
![1 1 1 - Criar um servico pesquisa](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/f56967c3-e638-4ab4-8f0e-0f58dda311aa)
...

### Criando recurso do Azure AI Service:
![2 - Implantacao ](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/a67b121a-7635-4325-a509-c2c1b2b1b672)
![3 - Criando Service](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/5cf2f640-c657-4e72-ab26-98cdc05ab9a8)
![3 1 - Criando Azure AI Service](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/554821a0-3118-4397-9462-a2fce394beed)
![3 2 - Finalizando a criacao Azure AI Service](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/5f6291e6-a982-4a8b-a65b-3d8549345f2c)
...

### Criando Storage Account:
![4 - Storage Account](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/dd24e2ac-0720-4a5c-b3c3-eb2e05d7ccb2)
![4 1 - Criando Storage Account](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/08eb2119-7f6e-43aa-b711-9cf3371fe912)
![4 1 1 - Criando Storage Account](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/e4699b9f-b719-494d-b932-6059056e560c)
![4 2 - Revisao Storage Account](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/d78c01db-b4a3-4141-9068-04dc3d4b7bd1)
![4 2 1 - Concluido Storage Account](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/fae38a3d-029d-46d0-8487-127119439316)
...

### Permissão de Acesso anônimo ao Blob:
![5 - Habilitando o Blob para Anonimo](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/6135f2d1-b320-4aa6-bbe2-249f460d478b)
...

### Criando Container:
Data Storage > Containers, para criar o contanier dentro do storage para que pesquisa sejam analisadas pelo Service.
![6 - Criacao do conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/ba045fc5-680b-4062-aac6-c06afdfa6fe1)
![6 1 - Criacao do conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/fdd23add-480c-4567-a46d-c16d4c65fade)
![6 2 - Carregando conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/723e7998-5790-4c85-ad34-859f562e2b1d)
![6 2 1 - Apos carregado os conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/93c86dd9-12d3-46e1-b820-29f81e8278c7)
![6 2 2 - importar dados para search](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/44a51b12-b510-4551-8d28-fcb930619ee9)
...

### Import e Index Data AI Search:
Nesta parte precisaremos criar uma conexao/link/importar os dados.
![7 - volta para search](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/f5852c03-c492-4373-be49-c22ac57f459a)
![7 1 - Selecionando conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/bda4ebd0-b3ec-4d4d-928d-6ed8a6bb4ed7)
![7 1 3 - Selecionando conteineres](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/adf8a6b5-edc3-4598-93b2-23431092a425)
OBS: Essa parte muda completamente do bootcamp que precisa seguir a risca, como estou realizando em 18/04/24 a Microsft modificou o caminho então segui a [Documentação Oficial](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html).

### Consultando o Índice:
![8 - Gerenciador de pesquisa](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/e5a40bc0-1cc5-4355-8299-68bc4b28a9ca)
...

#### Verifica se a indexação esta funcionando: ( search=*&$count=true )
![9 - pesquisa](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/3a6f5149-c7b3-481e-93a1-8ed9f77f8c51)
...
#### Consulta as ocorrencias acontecidas em Chicado ( search=locations:'Chicago' )
![9 1 - pesquisando sobre chicado](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/f52c98b9-977f-440c-878c-6a6d5aa07c3e)
...
#### Consulta as ocorrencias com sentimento negativo ( search=sentiment:'negative' )
![9 1 2 - pesquisando sobre coisas negativas](https://github.com/unly1/Azure-Cognitive-Search/assets/92002986/917b63b4-92b3-4a1d-af62-f9ac72215212)

## Resultado final
As ferramentas de inteligência artificial do Azure simplificam a busca em documentos, pesquisas e depoimentos, tornando mais ágil a análise da satisfação de empresas em relação aos seus produtos e serviços.
