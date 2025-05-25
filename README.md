# Questionador
Sistema Interativo de Questionários
Este é um aplicativo web de página única (SPA) simples para gerenciamento e realização de questionários interativos. Desenvolvido com HTML, JavaScript puro e estilização básica via Tailwind CSS, ele permite aos usuários praticar questões, gerenciar bancos de perguntas e visualizar estatísticas de desempenho.

Funcionalidades
Questionário Interativo:
Seleção de bancas examinadoras e temas para montar o quiz.
Exibição de perguntas com opções de múltipla escolha ou Certo/Errado.
Feedback imediato sobre a resposta (correta/incorreta).
Contagem de acertos e erros ao final do quiz.
Gerenciamento de Conteúdo:
Gerenciar Bancas: Adicione novas bancas examinadoras, configurando o número de opções de resposta e se penalizam erros.
Adicionar Pergunta Manualmente: Inclua novas questões individualmente, especificando banca, disciplina, tema, pergunta, opções e a resposta correta.
Importar Perguntas via CSV: Carregue múltiplos questionários de uma vez através de um arquivo CSV (formato específico: banca,disciplina,tema,pergunta,opcao1,opcao2,...,opcaoN,correta).
Estatísticas de Desempenho:
Visualização geral do total de perguntas respondidas, acertos e erros.
Gráfico de Acertos vs. Erros: Um gráfico de rosca mostrando a proporção de acertos em relação ao total de perguntas.
Gráfico de Desempenho por Disciplina: Barras que ilustram o número de acertos e erros por cada disciplina praticada.
Conteúdos Mais Praticados: Um gráfico de barras que mostra os temas que mais foram respondidos.
Disciplinas que Carecem de Estudo: Uma lista ranqueada das disciplinas com maior percentual de erros.
Conteúdos que Mais Precisam de Prática: Uma lista ranqueada dos temas com maior percentual de erros, destacando áreas para focar o estudo.
Persistência de Dados: Todos os dados (bancas, perguntas e estatísticas de desempenho) são salvos automaticamente no localStorage do seu navegador, garantindo que suas informações não sejam perdidas ao fechar a página.
Tecnologias Utilizadas
HTML5: Estrutura base do aplicativo.
JavaScript (Puro): Lógica interativa e manipulação do DOM.
Tailwind CSS: Framework de CSS utilitário para estilização e responsividade. Carregado via CDN.
Chart.js: Biblioteca JavaScript para criação de gráficos. Carregada via CDN.
Como Usar (Localmente)
Salve o Código: Copie todo o código HTML fornecido e cole-o em um arquivo de texto simples.
Renomeie o Arquivo: Salve o arquivo com a extensão .html (ex: quiz_app.html).
Abra no Navegador: Dê um duplo clique no arquivo quiz_app.html ou arraste-o para a janela do seu navegador.
Como Publicar Online (Gratuitamente)
Você pode hospedar este aplicativo online sem custo e sem a necessidade de um servidor próprio usando serviços de hospedagem de sites estáticos:

GitHub Pages:

Faça upload do seu arquivo .html (e quaisquer outros assets, se houver) para um repositório público no GitHub.
Vá para as Settings do seu repositório > Pages e selecione a branch principal (main ou master) para o deploy.
Seu site estará disponível em https://[seu-usuario].github.io/[nome-do-repositorio]/.
Netlify:

Crie uma conta gratuita no Netlify.
Na sua dashboard, você pode arrastar e soltar a pasta contendo seu arquivo .html diretamente na área de deploy.
O Netlify irá gerar um URL gratuito para seu site (ex: https://nome-aleatorio.netlify.app). Você também pode conectar a um repositório Git para deploys automáticos.
Observação: Para que os estilos e gráficos apareçam, é necessária uma conexão com a internet na primeira vez que a página é carregada, pois o Tailwind CSS e o Chart.js são carregados via CDN. Após o cache, pode funcionar offline para a lógica principal.

Estrutura do Projeto (Arquivo Único)
O aplicativo é contido em um único arquivo HTML que inclui o HTML, o CSS básico do Tailwind (via CDN) e todo o JavaScript.
