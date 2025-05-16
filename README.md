# Processador de XML NFe/NFCe

Ferramenta web para processar XMLs de NFe/NFCe, extrair campos selecionados e exportar como CSV (delimitado por `;`) ou JSON para Excel. Permite salvar/carregar perfis de campos para agilizar relatórios.

## Funcionalidades
- Importar XML matriz para selecionar campos.
- Salvar/carregar perfis de campos selecionados.
- Processar múltiplos XMLs com barra de progresso.
- Visualizar dados extraídos em tabela.
- Baixar relatórios em CSV ou JSON.

## Como Usar
1. Salve `index.html` localmente ou hospede no GitHub Pages.
2. Abra no navegador (use servidor local se necessário: `python -m http.server`).
3. Carregue XML matriz, selecione campos, salve perfil (opcional).
4. Processe XMLs de dados e baixe CSV ou JSON.

## Importar no Excel
- **CSV**: Abra diretamente ou importe com delimitador `;`.
- **JSON**: Use **Dados** > **Obter e Transformar** > **Do JSON**.

## Hospedagem
- Faça upload de `index.html` para um repositório GitHub.
- Ative GitHub Pages no branch principal.
