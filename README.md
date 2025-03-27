# 𝐀𝐧𝐚́𝐥𝐢𝐬𝐞 𝐝𝐞 𝐒𝐞𝐧𝐭𝐢𝐦𝐞𝐧𝐭𝐨𝐬 𝐜𝐨𝐦 𝐋𝐚𝐧𝐠𝐮𝐚𝐠𝐞 𝐒𝐭𝐮𝐝𝐢𝐨 𝐧𝐨 𝐀𝐳𝐮𝐫𝐞 𝐀𝐈
* Transcreve um áudio ou transforma um arquivo de texto em áudio. Pode ser utilizado para passar um conteúdo em tempo real, para um filme, música e série. Pode automatizar a fala.

## 𝘗𝘢𝘴𝘴𝘰 𝘢 𝘱𝘢𝘴𝘴𝘰:
### Abrir um recurso de fala dentro de IA e Machine Learning, se você não tiver criar um.
### Ir na conversão de fala e texto e selecionar o idioma e o arquivo.
### Quando finalisar o deployde a ggente vai criar um recurso.
### Ir em analisar sentimento, selecionar o idioma e analisar.


# Explore an Azure AI Search index (UI)
Entre no portal do Azure .

Clique no botão + Criar um recurso , pesquise por Azure AI Search e crie um recurso do Azure AI Search com as seguintes configurações:

Assinatura : sua assinatura do Azure .
Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .
Nome do serviço : Um nome exclusivo .
Localização : Escolha qualquer região disponível. Se estiver no leste dos EUA, use “East US 2” .
Nível de preço : Básico
Selecione Revisar + criar e, depois de ver a resposta Validação bem-sucedida , selecione Criar .

Após a conclusão da implantação, selecione Ir para o recurso . Na página de visão geral do Azure AI Search, você pode adicionar índices, importar dados e pesquisar índices criados.

Criar um recurso de serviços de IA do Azure
Você precisará provisionar um recurso de serviços de IA do Azure que esteja no mesmo local que seu recurso de Pesquisa de IA do Azure. Sua solução de pesquisa usará esse recurso para enriquecer os dados no datastore com insights gerados por IA.

Retorne à página inicial do portal do Azure. Clique no botão ＋Criar um recurso e pesquise por Azure AI services . Selecione criar um plano de serviços do Azure AI . Você será levado a uma página para criar um recurso de serviços do Azure AI. Configure-o com as seguintes configurações:
Assinatura : sua assinatura do Azure .
Grupo de recursos : o mesmo grupo de recursos que seu recurso do Azure AI Search .
Região : o mesmo local do seu recurso do Azure AI Search .
Nome : Um nome único .
Nível de preço : Standard S0
Ao marcar esta caixa, reconheço que li e compreendi todos os termos abaixo : Selecionado
Selecione Revisar + criar . Após ver a resposta Validação aprovada , selecione Criar .

Aguarde a conclusão da implantação e visualize os detalhes da implantação.

# Explore generative AI in Azure AI
Em uma guia do navegador, navegue até Azure AI Foundry .

Entre com sua conta.

Na página inicial do portal do Azure AI Foundry, selecione Create a project . No Azure AI Foundry, os projetos são contêineres que ajudam a organizar seu trabalho.
No painel Criar um projeto , você verá um nome de projeto gerado, que pode ser mantido como está. Dependendo se você criou um hub no passado, verá uma lista de novos recursos do Azure a serem criados ou uma lista suspensa de hubs existentes. Se você vir a lista suspensa de hubs existentes, selecione Criar novo hub , crie um nome exclusivo para seu hub e selecione Avançar .
No mesmo painel Create a project , selecione Customize e selecione um dos seguintes Locations : East US, France Central, Korea Central, West Europe ou West US para concluir o restante do laboratório. Em seguida, selecione create .
Na página Playgrounds do Azure AI Foundry, selecione Try the Chat playground . O Chat playground é uma interface de usuário que permite que você experimente criar um aplicativo de chat com diferentes modelos de IA generativa.

Para usar o Chat playground, você precisa associá-lo a um modelo implantado. No Chat playground, selecione Create a deployment . Pesquise e selecione gpt-4 .

Na janela Deploy model , mantenha a nomenclatura e seleção padrão e selecione Deploy . Pode levar um momento para o modelo ser implantado. Você pode verificar o status da sua implantação selecionando Models and endpoints no menu à esquerda em My assets .
No playground de bate-papo, você pode usar seu modelo implantado quando ele aparecer no menu de seleção Implantação . Certifique-se de que o modelo implantado esteja selecionado. É importante que você selecione Aplicar alterações depois de fazer qualquer alteração na Configuração .

Considere as seguintes maneiras de melhorar as respostas de um assistente de IA generativa:
Comece com uma meta específica para o que você quer que o assistente faça
Iterar com base em prompts e respostas anteriores para refinar o resultado
Forneça uma fonte para fundamentar a resposta em um escopo específico de informações
Adicione contexto para maximizar a adequação e relevância da resposta
Defina expectativas claras para a resposta

