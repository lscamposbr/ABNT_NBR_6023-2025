# ABNT_NBR_6023-2025
# Estilo ABNT para Microsoft Word (Atualizado 2025) 🇧🇷

Este repositório fornece um estilo de bibliografia customizado (`.XSL`) para o Microsoft Word, permitindo que a ferramenta nativa de "Citações e Bibliografia" do Word gere referências e citações automaticamente no padrão da Associação Brasileira de Normas Técnicas (ABNT).

Este arquivo é baseado no clássico projeto [BibWord](https://github.com/codingo/BibWord) (de Yves Dhondt), mas foi **profundamente atualizado** para atender às mudanças mais recentes das normas brasileiras.

## 🆕 O que há de novo nesta versão?
* **ABNT NBR 10520:2023:** As citações no texto (dentro dos parênteses) agora utilizam apenas a primeira letra maiúscula (ex: `Silva, 2023` em vez de `SILVA, 2023`).
* **ABNT NBR 6023:2018 (Emenda 1 de 2025):** 
  * Inclusão do termo *In:* em itálico para capítulos de livros e partes de obras.
  * Formatação adequada para o local e editora ausentes (`[S. l.: s. n.]`).
  * Correção da posição dos volumes na geração da referência e prefixos adequados (`v.` e `p.`).

## ⚙️ Como Instalar (Windows)

Para instalar o estilo no Word, você deve baixar o arquivo `ABNT_NBR_2025.XSL` e colá-lo na pasta oculta de Estilos do Microsoft Word. O local dessa pasta varia de acordo com a sua versão do Office.

**Passo a passo:**
1. Baixe o arquivo `ABNT_NBR_2025.XSL` aqui do repositório.
2. Pressione as teclas `Windows + R` no seu teclado (ou abra uma pasta qualquer no Explorador de Arquivos).
3. Copie o caminho correspondente à sua versão do Word (veja abaixo), cole na barra de endereços e aperte `ENTER`:

**Para Word 2013, 2016, 2019, 2021 e Office 365 (Mais comum):**
%userprofile%\AppData\Roaming\Microsoft\Bibliography\Style

**Se a pasta acima não existir ou o estilo não aparecer, tente este caminho alternativo do Office 365:**

%AppData%\Microsoft\Templates\LiveContent\16\Managed\Word Document Bibliography Styles

**Para Microsoft Word 2007**
<winword.exe directory>\Bibliography\Style

**Microsoft Word 2007 32-bit**
%programfiles%\Microsoft Office\Office12\Bibliography\Style

**Microsoft Word 2010 32-bit**
%programfiles%\Microsoft Office\Office14\Bibliography\Style

4. Cole o arquivo ABNT_NBR_2025.XSL dentro da pasta que se abriu.
5. Reinicie o seu Microsoft Word.

🍎 Como Instalar (Mac)

No macOS, as pastas da Microsoft são um pouco mais escondidas.
1. Baixe o arquivo ABNT_NBR_2025.XSL.
2. Abra o Finder > Pressione Cmd + Shift + G (Ir para a Pasta).
3. Cole o seguinte caminho:

~/Library/Containers/com.microsoft.Word/Data/Library/Application Support/Microsoft/Office/16.0/Custom Dictionary/Bibliography/Style

4. Cole o arquivo lá dentro e reinicie o Word.
(Nota: Se o caminho não funcionar, vá em Aplicativos > Microsoft Word > Clique com o botão direito e "Mostrar Conteúdo do Pacote" > Contents > Resources > Style).

📖 Como Usar

Com o Word aberto, vá na aba Referências.
Na seção "Citações e Bibliografia", clique no menu suspenso Estilo.
Selecione ABNT NBR 6023:2025*.
Adicione suas fontes clicando em Inserir Citação > Adicionar Nova Fonte Bibliográfica.

Créditos: Projeto original criado por Yves Dhondt (BibWord). Modificações e adaptações de código para as NBRs de 2023/2025 realizadas pela comunidade.
