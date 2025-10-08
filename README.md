[README_TradutorDeAtalhos.md](https://github.com/user-attachments/files/22757534/README_TradutorDeAtalhos.md)
# Tradutor de Atalhos (Detecção Automática → Português)

Este repositório contém o atalho **Tradutor de Atalhos (Detecção → PT)** para iOS — ele detecta automaticamente o idioma do nome dos atalhos da sua galeria e mostra a tradução para Português (BR).
> Nota: por medidas de segurança do iOS, a renomeação automática de atalhos pode exigir confirmação manual. Este atalho gera a lista e as traduções para você aplicar manualmente se desejar.

## Conteúdo
- `TradutorDeAtalhos_DetectaParaPT.shortcut` — arquivo pronto para importar no app **Atalhos** (iOS).

## Como publicar no GitHub (passo a passo rápido)
1. Crie um novo repositório no GitHub (ex.: `tradutor-de-atalhos`).  
2. Faça upload dos arquivos `TradutorDeAtalhos_DetectaParaPT.shortcut` e deste `README.md`.  
3. Opcional: crie uma **Release** no GitHub e anexe o arquivo `.shortcut` (ajuda a manter versões).  
4. Adicione uma `LICENSE` (recomendo MIT se quiser abrir o código).

## Como transformar este arquivo em um atalho "oficial" (link iCloud utilizável por qualquer pessoa)
1. No iPhone, abra o app **Atalhos**.  
2. Toque no ícone ➕ e depois em **Importar Atalho** (ou abra o arquivo `.shortcut` diretamente da pasta "Arquivos" / Safari).  
3. Teste o atalho e confirme que as traduções aparecem como notificações.  
4. Toque nos **três pontinhos (…)** do atalho importado.  
5. Toque no ícone de **compartilhar** (quadrado com seta para cima) → **Compartilhar Atalho** → **Copiar Link do iCloud**.  
6. Cole o link do iCloud no `README.md` do seu repositório (ou na descrição da Release).  
   - Este link é o que torna o atalho "oficial" / instalável com um clique por outras pessoas.

## Boas práticas (go-to-market)
- Teste em 2-3 iPhones diferentes (iOS 16/17/18) antes de publicar.  
- Inclua instruções claras de permissão: `Ajustes → Atalhos → Permitir Atalhos Não Confiáveis` e `Ajustes → Atalhos → Acesso à Internet` se necessário.  
- Se quiser versionamento automático, publique Releases no GitHub com tags (`v1.0`, `v1.1`, ...).

## Instalação pelo usuário final
1. Clique no link do iCloud (colocado no README).  
2. O Safari vai abrir a página do iCloud → toque em **Obter Atalho** → Atalhos abrirá e perguntará para adicionar.  
3. Aceite e execute.

## Observações técnicas
- O arquivo `.shortcut` incluído aqui é uma representação do fluxo criado com o app Atalhos e usa a ação nativa **Traduzir Texto** com detecção automática de idioma.  
- O iOS pode pedir confirmações em certas ações por segurança — isso é normal.

---
Se quiser, eu já coloco no seu repositório o `README.md` formatado e um `RELEASE` template. Também posso gerar um badge de instalação que aponta para o link iCloud assim que você me colar o link gerado no seu iPhone.
