# Teste de seleção PHP Imobibrasil

## Regras:
- Você tem 10 dias corridos a partir do recebimento deste teste. Após o término do prazo, pode enviar o código mesmo que incompleto.
- O sistema deve ser feito na linguagem PHP e com o banco de dados MySQL. 
- Recomendamos para o sistema de arquivos e aplicativos do servidor utilizar o stack LAMP, mas você é livre para utilizar qualquer stack com server ou serverless.
- Para este desafio você deve utilizar PHP sem frameworks como: Laravel, Cake ou CodeIgnite.
- O código deve estar disponível no GitHub ou outra ferramenta de versionamento de sua escolha.
- Você poderá utilizar qualquer biblioteca de frontend JS ou CSS como: Bootstrap, Materialize CSS, Foundation, jQuery UI, Vue.js ou React)




## O projeto:
Você foi encarregado de desenvolver um sistema de gerenciamento de mídias dos imóveis dos clientes ImobiBrasil. Essas mídias podem ser imagens, documentos, Arquivos PDF, Word e etc. As mídias podem ou não ser anexadas a um determinado imóvel. Por exemplo: um imóvel pode ter um comprovante de locação, uma escritura ou uma foto da planta da casa. 

Importante: de última hora recebemos uma demanda de que os clientes vão precisar de muito espaço e algumas funcionalidades de gerenciamento. Por isso de uma olhada no tópico de funcionalidades extras, se você conseguir desenvolver essas funcionalidades extras será um baita diferencial.


### Gerenciamento de Mídias
Abaixo os requisitos da funcionalidade:

- Deve ter a listagem com busca por nome do arquivo, upload de arquivos, edição do nome, um select para anexar o arquivo a um imóvel e por fim a exclusão do arquivo.
- Campos: ID, ID imovel, nome do arquivo, caminho do arquivo,  data de upload.
- Campos obrigatórios: Nome e E-mail.
- Um arquivo de mídia pode estar ligado a um imóvel

### Imóveis
Abaixo os requisitos da funcionalidade:

- Deve ter a listagem com busca, cadastro, edição e exclusão do imóvel.
- Campos: Id, título do imóvel, descrição, endereço completo, preço e data do cadastro.


## Diferenciais para análise:
- Código organizado e limpo.
- Uso das PSRs.
- Montar a estrutura do projeto na ferramenta de sua preferência.


## Tabelas necessárias:
- imoveis
- midias


## Funcionalidades Extras:
- Armazenar os arquivos em uma Cloud de objetos como AWS S3, Google Cloud Storage e Linode Object Storage por exemplo.
- Exibir um botão para compartilhar os arquivos.
- Bloquear e liberar o acesso externo aos arquivos
- Permitir anexar uma tag de marcação nos arquivos como: importante, urgente e favorito.
- Permitir criação de pastas para organizar os arquivos.
- A partir do endereço do imóvel utilize a API do Google maps (ou outro provedor de mapas) para exibir um mapa de localização.
