---
title: "DeepSeek"
source: "https://chat.deepseek.com/a/chat/s/cb87f145-73f5-4c88-aa70-c1268c6d0e2d"
author:
published:
created: 2026-07-02
description: "Chat with DeepSeek AI – your intelligent assistant for coding, content creation, file reading, and more. Upload documents, engage in long-context conversations, and get expert help in AI, natural language processing, and beyond. | 深度求索（DeepSeek）助力编程代码开发、创意写作、文件处理等任务，支持文件上传及长文本对话，随时为您提供高效的AI支持。"
tags:
  - "clippings"
---
New chat

Yesterday

[

O que fazer no Obsidian

](https://chat.deepseek.com/a/chat/s/cb87f145-73f5-4c88-aa70-c1268c6d0e2d)

30 Days

[

Cafeteira portátil espresso

](https://chat.deepseek.com/a/chat/s/7b6b91e4-6a45-4d08-b02c-4bb7cfa8da7b)

Roberto Oliveira

Read 12 web pages

Sim, é possível, mas essa funcionalidade não é nativa do Obsidian. Para criar links para pastas ou arquivos fora do seu "vault", você precisará usar plugins da comunidade. Existem algumas abordagens diferentes, cada uma com suas vantagens.

### ⚙️ Como Funciona e Quais as Opções

O Obsidian, por design, foca em arquivos dentro do seu vault para manter a segurança e a simplicidade. No entanto, a comunidade criou plugins para resolver exatamente essa necessidade. Aqui estão as principais opções para conectar-se a pastas externas:

1. **Criar Atalhos com Links Simbólicos (Plugin `LNS Directories`)**
	- **Como funciona**: Este plugin cria atalhos (links simbólicos) dentro do seu vault que apontam para pastas ou arquivos em qualquer lugar do seu sistema. A pasta externa aparecerá no explorador de arquivos do Obsidian como se estivesse dentro do vault [3](https://github.com/choihunchul/lns_directories).
		- **Vantagem**: É a solução mais "natural" e integrada. Você navega pelos arquivos da pasta externa usando a interface padrão do Obsidian, como se eles fizessem parte do projeto [3](https://github.com/choihunchul/lns_directories).
		- **Limitação**: Este plugin funciona apenas na **versão desktop** do Obsidian [3](https://github.com/choihunchul/lns_directories). No Windows, a criação de links simbólicos pode exigir permissões de administrador [3](https://github.com/choihunchul/lns_directories).
2. **Embutir e Linkar Arquivos Externos (Plugins `DualLink` e `External File Embed and Link`)**
	- **Como funciona**: Esses plugins permitem que você crie links ou incorpore o conteúdo de arquivos externos diretamente em suas notas [1](https://github.com/mowdw/DualLink) [2](https://github.com/oylbin/obsidian-external-file-embed-and-link#readme). Você pode usar o formato `local-file:///caminho/para/seu/arquivo.pdf` ou definir "diretórios virtuais" para encurtar os caminhos [1](https://github.com/mowdw/DualLink) [2](https://github.com/oylbin/obsidian-external-file-embed-and-link#readme).
		- **Vantagem**: São muito flexíveis. Você pode, por exemplo, **visualizar imagens e PDFs** externos diretamente no corpo da sua nota, sem precisar copiá-los para o vault. O `DualLink` também permite arrastar arquivos de fora para dentro do editor, gerando o link automaticamente [1](https://github.com/mowdw/DualLink).
		- **Limitação**: Esses plugins geralmente trabalham com arquivos individuais. A funcionalidade de explorar pastas externas como se fossem parte do vault é menos direta do que na opção 1, embora o `DualLink` tenha um navegador de arquivos para facilitar [1](https://github.com/mowdw/DualLink).
3. **Usar a URI do Obsidian (Solução Alternativa)**
	- **Como funciona**: O Obsidian possui um sistema de URIs (`obsidian://`) que permite abrir arquivos específicos a partir de outros aplicativos ou scripts. Você pode usar o parâmetro `path` para abrir um arquivo em uma localização absoluta [5](https://github.com/obsidianmd/obsidian-help/blob/5fb785ac/en/Extending%20Obsidian/Obsidian%20URI.md?plain=1#L11-L23) [6](https://obsidian.md/help/uri#Create+note) [8](https://forum.obsidian.md/t/starting-obsidian-from-command-line-with-uri-open-path-is-not-working-under-windows/107025/5).
		- **Vantagem**: É uma solução nativa, sem precisar de plugins para criar os links.
		- **Limitação**: Mais adequada para automação externa (como um script que abre um documento) do que para criar links clicáveis dentro das suas anotações. Além disso, a URI só funcionará se a pasta do arquivo já for conhecida pelo Obsidian (estar listada no arquivo de configuração), o que pode ser um problema para pastas em unidades removíveis [8](https://forum.obsidian.md/t/starting-obsidian-from-command-line-with-uri-open-path-is-not-working-under-windows/107025/5).

### 🛠️ Tabela Comparativa das Soluções

| Solução | Funcionalidade Principal | Vantagem para Seu Caso | Plataforma |
| --- | --- | --- | --- |
| **LNS Directories** [3](https://github.com/choihunchul/lns_directories) | Criar atalhos (symlinks) para pastas externas dentro do vault. | Acessar e navegar por pastas de projetos como se estivessem dentro do Obsidian. | Desktop |
| **DualLink** [1](https://github.com/mowdw/DualLink) | Linkar e visualizar arquivos externos em notas. | Visualizar PDFs, diagramas ou fotos do projeto sem copiá-los. | Desktop/Mobile (provavelmente) |
| **External File Embed and Link** [2](https://github.com/oylbin/obsidian-external-file-embed-and-link#readme) | Linkar arquivos com caminhos virtuais. | Criar links que funcionam em diferentes computadores, independente do caminho absoluto. | Desktop/Mobile (provavelmente) |

### 💎 Qual escolher para projetos de subestações?

Para o seu caso, a melhor opção provavelmente é combinar duas abordagens:

1. **Para pastas com muitos documentos (ex: uma pasta `Projeto_X/Documentação/`)**, a solução mais prática é usar o plugin **`LNS Directories`**. Você criaria um link simbólico dentro do seu vault para essa pasta. Assim, ela aparecerá no seu explorador de arquivos do Obsidian e você poderá abrir qualquer PDF, DWG ou planilha dali com um clique, sem sair do ambiente [3](https://github.com/choihunchul/lns_directories).
2. **Para documentos-chave que você quer referenciar diretamente em uma nota (ex: anexar o diagrama unifilar à ata de uma reunião)**, o **`DualLink`** é mais poderoso. Você pode não só linkar, mas também incorporar uma prévia do PDF ou da imagem diretamente no corpo da nota, o que é excelente para consultas rápidas [1](https://github.com/mowdw/DualLink).

Para começar, sugiro instalar o **`LNS Directories`** e o **`DualLink`** pela loja de plugins da comunidade e testar com uma pasta pequena de documentos. É a melhor forma de sentir qual se adapta melhor ao seu fluxo de trabalho.

Se tiver dúvidas sobre a configuração de algum deles, pode me perguntar!

12 web pages

quando tento adicionar um diretorio nestes plugin eles exibe uma mensagem com caminho invalido

Read 14 web pages

Esse erro de "caminho inválido" é chato, mas bem comum e geralmente tem algumas causas principais. Vamos ver as mais prováveis para você testar.

### 🧐 As Causas Mais Comuns

1. **Formatação do caminho no Windows**  
	O problema mais frequente, especialmente no Windows, é usar as barras invertidas (`\`) no lugar das barras normais (`/`). O sistema costuma aceitar melhor caminhos no formato `C:/MeusDocumentos/Pasta` do que `C:\MeusDocumentos\Pasta` [8](https://deepwiki.com/danielshue/notebook-automation/10.1-configuration-issues).
2. **Permissão de Administrador para Links Simbólicos**  
	No Windows, para criar um link simbólico para uma pasta fora do seu "vault", você geralmente precisa de **permissões de administrador** [2](https://pkmer.cn/Pkmer-Docs/10-obsidian/obsidian%E7%A4%BE%E5%8C%BA%E6%8F%92%E4%BB%B6/lns-directories/#%e6%a6%82%e8%bf%b0) [12](https://github.com/choihunchul/lns_directories) [13](https://www.obsidianstats.com/plugins/lns-directories). Se você está em um computador corporativo, essa pode ser a causa. Tente abrir o Obsidian como administrador (clicar com o botão direito no ícone e escolher "Executar como administrador").
3. **Problemas com Caracteres Especiais ou Espaços**  
	Nomes de pastas com caracteres que o sistema não gosta (como `*`, `:`, `?`, `"` ou `<` e `>`) ou com espaços em branco podem causar problemas de interpretação do caminho [9](https://github.com/mnaoumov/obsidian-advanced-note-composer) [11](https://github.com/scottTomaszewski/obsidian-bible-references-plugin/issues/1).
4. **Plugin `LNS Directories` e a Restrição de Pastas**  
	A documentação do plugin explica que ele só deve ser usado para criar links que apontem para **pastas completamente separadas** do seu vault. Ou seja, a pasta externa não pode ser uma subpasta do vault, nem uma pasta pai, nem ter ligações que causem uma "confusão" de diretórios [6](https://obsidian.md/help/symlinks). Se você está tentando adicionar a raiz de um disco (ex: `D:/`), pode não funcionar.

### 🛠️ Como Resolver

Teste essas soluções, começando pela mais simples:

1. **Verifique a Barra**: Substitua todas as `\` por `/` no caminho [8](https://deepwiki.com/danielshue/notebook-automation/10.1-configuration-issues). Exemplo: `C:\Projetos\Subestação\Documentos` vira `C:/Projetos/Subestação/Documentos`.
2. **Teste com um Caminho Simples**: Crie uma pasta só com letras e números, sem espaços, no seu `C:/` (ex: `C:/TesteObsidian`) e tente adicionar ela. Se funcionar, o problema está no nome ou local da sua pasta original.
3. **Execute como Administrador**: Feche o Obsidian, clique com o botão direito no ícone e selecione **"Executar como administrador"**. Tente o processo de novo.
4. **Use a Interface do Plugin**: Em vez de digitar o caminho, use o botão **"Browse"** (ou "Procurar") dentro do plugin para navegar até a pasta e selecioná-la. Isso garante que o caminho será inserido no formato correto [12](https://github.com/choihunchul/lns_directories) [13](https://www.obsidianstats.com/plugins/lns-directories).

Se, depois de tentar esses passos, o erro persistir, me avise qual é o caminho que você está tentando adicionar (pode mascarar o nome do projeto, se preferir) e em qual momento exato o erro aparece (ao digitar, ao clicar em "Browse", ou ao confirmar). Assim, consigo te ajudar melhor.

14 web pages

Daria pra usar o cofre em uma pasta da rede e acessar o cofre de várias máquinas

Read 12 web pages

Sim, é possível usar um cofre (vault) em uma pasta de rede e acessá-lo de várias máquinas. Porém, essa abordagem direta tem riscos sérios e pode não ser a mais recomendada para um ambiente de trabalho, especialmente para projetos complexos como os de subestações.

A boa notícia é que existem caminhos melhores e mais seguros para alcançar o que você quer, que é o acesso centralizado aos seus arquivos de qualquer máquina.

### ⚠️ O risco de usar a pasta de rede diretamente

A documentação oficial do Obsidian desaconselha fortemente armazenar o cofre diretamente em serviços de sincronização de arquivos como Dropbox, OneDrive ou Google Drive, e o mesmo princípio se aplica a pastas de rede mapeadas [3](https://obsidian.md/help/sync/switch).

O principal problema são os **conflitos de arquivos**. O Obsidian grava constantemente em arquivos de configuração (na pasta `.obsidian`) enquanto você trabalha [4](https://www.npmjs.com/package/obsyncd). Se duas pessoas (ou a mesma pessoa em duas máquinas) abrirem o cofre ao mesmo tempo pela rede, o sistema de arquivos pode tentar sincronizar essas mudanças simultâneas, resultando em:

- **Arquivos "cópia conflitante"** duplicados pela rede [4](https://www.npmjs.com/package/obsyncd).
- **Corrupção de arquivos** importantes do cofre [4](https://www.npmjs.com/package/obsyncd).
- **Perda de dados**, pois uma versão mais antiga pode sobrescrever uma mais nova sem aviso [5](https://github.com/bobhy/vault-share).

Além disso, alguns sistemas de arquivos em rede bloqueiam os arquivos durante a sincronização, o que pode causar erros de "acesso negado" no Obsidian, especialmente em Windows com pastas de rede [12](https://forum.obsidian.md/t/how-to-avoid-access-denied-eacces-errors-with-proton-drive-others/83120/6) [10](https://forum.obsidian.md/t/network-drive-links-absolute-links/103631).

### ✅ Soluções recomendadas e mais seguras

Em vez de usar a pasta de rede diretamente, o ideal é manter os cofres **locais** em cada máquina e usar um método para sincronizá-los. Aqui estão as melhores opções para o seu caso:

**1\. Obsidian Sync (Solução Oficial e Robusta)**

Este é o serviço pago da própria Obsidian e a opção mais segura e recomendada [6](https://github.com/obsidianmd/obsidian-help/blob/5fb785ac/en/Obsidian%20Sync/Local%20and%20remote%20vaults.md?plain=1#L97-L109).

- **Como funciona**: Você mantém um cofre local em cada máquina. O Obsidian Sync cria um "cofre remoto" centralizado na nuvem da Obsidian. As mudanças são enviadas (upload) deste cofre remoto e baixadas (download) para os outros cofres locais [6](https://github.com/obsidianmd/obsidian-help/blob/5fb785ac/en/Obsidian%20Sync/Local%20and%20remote%20vaults.md?plain=1#L97-L109).
- **Vantagens**: É a única solução que funciona de forma consistente em todos os sistemas operacionais (Windows, Mac, mobile) sem os problemas de conflito de arquivos de serviços de terceiros [6](https://github.com/obsidianmd/obsidian-help/blob/5fb785ac/en/Obsidian%20Sync/Local%20and%20remote%20vaults.md?plain=1#L97-L109). O comportamento é previsível e a sincronização é gerenciada pelo próprio aplicativo.
- **Desvantagem**: É um serviço pago.

**2\. Soluções com sincronização inteligente (Plugins e Ferramentas)**

Se você não quiser usar o Obsidian Sync, existem plugins e ferramentas feitas especificamente para sincronizar cofres de forma confiável, evitando os conflitos de arquivos de soluções genéricas.

- **Plugin `vault-share`**: Este plugin foi criado para resolver exatamente o problema de sincronizar um cofre entre múltiplos dispositivos, usando o **Google Drive** como repositório central [5](https://github.com/bobhy/vault-share).
	- **Como funciona**: Ele sincroniza apenas os arquivos que mudaram e tem um sistema inteligente para resolver conflitos, incluindo a opção de fazer um **merge (mesclagem)** de alterações em arquivos `.md` e `.txt` [5](https://github.com/bobhy/vault-share).
		- **É uma boa pedida para você**: Funciona muito bem para equipes e evita que você tenha que gerenciar manualmente os arquivos. Vale a pena testar, pois você pode configurar a pasta do Google Drive para ser acessada pela equipe.
- **Ferramenta `obsyncd`**: É uma ferramenta de linha de comando que você instala no computador via `npm` e que faz a sincronização bidirecional entre o seu cofre local e uma pasta de sincronização (que pode ser na rede ou em um serviço como Dropbox) [4](https://www.npmjs.com/package/obsyncd).
	- **Como funciona**: Ela sincroniza apenas as suas notas, ignorando os arquivos internos do Obsidian que causam conflitos [4](https://www.npmjs.com/package/obsyncd).
		- **Vantagem**: Oferece controle total e estratégias de resolução de conflito (como usar o arquivo mais recente ou o da fonte) [4](https://www.npmjs.com/package/obsyncd). É uma solução para quem não tem medo de usar o terminal.

### 💡 O que fazer com os documentos de rede? Uma solução híbrida

Como você mencionou que usa o Obsidian para organizar projetos de subestações, imagino que tenha muitos documentos em pastas de rede (PDFs, DWGs, fotos). Você não precisa mover tudo para o cofre.

Aqui está uma estratégia que pode atender perfeitamente ao seu fluxo de trabalho:

1. **Para suas notas e organização (o "coração" do projeto)**: Use um cofre **local** em cada máquina e o sincronize com o restante da equipe usando uma das soluções acima (de preferência o **Obsidian Sync** ou o plugin **vault-share**). Isso garante a integridade dos seus dados de texto e da sua estrutura de conhecimento.
2. **Para acessar os documentos pesados (PDFs, imagens)**: Use um plugin como o novo **Folder Bridge** [2](https://forum.obsidian.md/t/new-plugin-folder-bridge-mount-your-folders-into-obsidian/111496/6) ou o **LNS Directories** [7](https://github.com/choihunchul/lns_directories) [9](https://www.obsidianstats.com/plugins/lns-directories) para "montar" suas pastas de rede dentro do Obsidian.
	- O **Folder Bridge** parece ser o mais poderoso para isso, pois permite montar pastas de rede (incluindo caminhos UNC do Windows) como se fossem parte do seu cofre, sem copiar ou duplicar os arquivos [2](https://forum.obsidian.md/t/new-plugin-folder-bridge-mount-your-folders-into-obsidian/111496/6). Além disso, ele oferece uma ótima integração com plugins como o Quick Switcher e o de busca [2](https://forum.obsidian.md/t/new-plugin-folder-bridge-mount-your-folders-into-obsidian/111496/6).

Com essa abordagem, suas notas ficam seguras, sincronizadas e livres de conflitos, enquanto você mantém o acesso rápido a todos os documentos que estão na rede, exatamente no lugar onde eles precisam estar.

12 web pages

Acho que o Obsidian não atemde bem o que eu quero, quero algo como uma central de informações para projetos, isso ele atende porém as ferramentas de para usar links externos do sistema não funciona como deveria.

DeepThink

Search

AI-generated, for reference only

O que dá pra fazer no Obsidian

Este Obsidian da pra trabalhar em equipes?

Eu trabalho com projetos de subestações, pensei em usar o Obsidian para catalogar e registrar comentários de projetos e reuniões ou organizar ideias para um projeto em. Não sei bem se o Obisidian serve para este proposito ou algo mais elaborado.

O Obsidian não aceita link de pasta local do sistema operacional? isso seria muito útil para abrir documentos em pastas expecificas no sistema.

quando tento adicionar um diretorio nestes plugin eles exibe uma mensagem com caminho invalido

Daria pra usar o cofre em uma pasta da rede e acessar o cofre de várias máquinas