# Mesclador de PDF Visual e Local

Este é um projeto de uma ferramenta web de página única que permite aos usuários mesclar múltiplos arquivos PDF em um único documento de forma visual e interativa. A principal característica desta ferramenta é que todo o processamento é feito localmente no navegador do usuário, garantindo total privacidade e segurança, pois nenhum arquivo é enviado para um servidor.

## ✨ Funcionalidades Principais

- **Processamento 100% Local:** Os arquivos PDF são processados diretamente no seu navegador. Nada é enviado para a nuvem.
- **Interface Visual:** Gera miniaturas da primeira página de cada PDF para fácil identificação.
- **Ordenação com Arrastar e Soltar (Drag-and-Drop):** Reordene facilmente os documentos arrastando suas miniaturas para a posição desejada.
- **Seleção Múltipla de Arquivos:** Carregue vários PDFs de uma só vez.
- **Nome de Saída Personalizável:** Defina o nome do arquivo PDF consolidado antes de baixar.
- **Limpeza Rápida:** Um botão para limpar todos os arquivos carregados e recomeçar.
- **Design Responsivo:** Funciona bem em diferentes tamanhos de tela.

## 🚀 Como Usar

1.  **Abra o Arquivo:** Basta abrir o arquivo `UnirPDF.html` em qualquer navegador web moderno (como Chrome, Firefox, Edge).
2.  **Selecione os PDFs:** Clique na área de upload para selecionar os arquivos PDF que você deseja mesclar. Você pode selecionar vários de uma vez.
3.  **Aguarde as Miniaturas:** O sistema irá gerar e exibir uma pré-visualização da primeira página de cada PDF.
4.  **Ordene os Arquivos:** Clique e arraste as miniaturas para organizar os documentos na ordem correta de mesclagem. A numeração é atualizada automaticamente.
5.  **Defina o Nome do Arquivo (Opcional):** Altere o nome padrão "Documento_Consolidado" para o que preferir no campo de texto.
6.  **Mescle e Baixe:** Clique no botão **"Mesclar e Baixar"**. O processo de junção começará, e o download do arquivo finalizado será iniciado automaticamente.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando apenas tecnologias front-end, sem a necessidade de um back-end.

- **HTML5:** Estrutura da página.
- **CSS3:** Estilização e layout, incluindo variáveis CSS para um tema consistente.
- **JavaScript (ES6+):** Lógica da aplicação, manipulação do DOM e interatividade.
- **pdf-lib.js:** Uma biblioteca poderosa para criar e modificar documentos PDF em JavaScript. Usada aqui para a função de mesclagem.
- **PDF.js:** Uma biblioteca desenvolvida pela Mozilla para renderizar arquivos PDF no navegador. Usada para gerar as miniaturas das páginas.

## 🔒 Segurança e Privacidade

A principal vantagem desta ferramenta é a privacidade. Como todo o código é executado no lado do cliente (no seu navegador), seus arquivos nunca saem do seu computador. Isso elimina qualquer preocupação com a segurança e o manuseio de documentos sensíveis por terceiros.