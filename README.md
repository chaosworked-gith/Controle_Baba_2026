# Check-in Baba dos Eletricistas · CAE 2026

Controle de entrada do Baba dos Eletricistas. A equipe marca quem chegou (verde), quem não veio (vermelho) e quem participa do sorteio. Ao finalizar, o app gera a lista de presentes (XLSX) e os nomes do sorteio (TXT, um nome por linha).

## Arquivos

- `design.html`: vitrine com 24 participantes fictícios. Abre em qualquer navegador e no GitHub Pages. Dá para testar tudo, inclusive baixar o XLSX e o TXT. Nada é salvo.
- `codigo.html`: o app usado no evento. Roda dentro do claude.ai (Artifact), onde a lista é compartilhada entre vários celulares. Fora do claude.ai ele só mostra um aviso.

Para o GitHub Pages abrir a vitrine direto no endereço do site, renomeie `design.html` para `index.html`.

## Dados pessoais

Nenhum arquivo deste repositório tem nomes, telefones ou dados de saúde reais. No app, a lista entra pelo botão **Carregar planilha**, que lê a aba "Lista Geral" do .xlsx de inscritos.

## Colunas lidas da planilha

Nome completo, Modalidade, WhatsApp, Cadastrado no CAE?, Alergia / saúde.