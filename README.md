# Zendesk Timer 1.0 - Suporte Saipos

Esta extensão foi desenvolvida especificamente para os **Analistas de Suporte da Saipos**, com o objetivo de auxiliar no monitoramento de inatividades e otimizar o fluxo de atendimento.

## 🚀 Propósito da Ferramenta

A ferramenta atua como um assistente para o analista, alertando automaticamente ("Enviar sem retorno") quando um cliente permanece inativo por mais de 4 minutos e meio após, o envio de uma mensagem. Isso garante que nenhum chat seja esquecido e que o tempo de resposta seja sempre otimizado.

## 🤝 Código Aberto e Colaboração

O código desta extensão é **livre para editar e colaborar**. Sinta-se à vontade para:
- Sugerir novas funcionalidades.
- Ajustar os tempos de alerta conforme a necessidade da operação.
- Melhorar a interface visual.
- Otimizar a lógica de detecção para novas atualizações do Zendesk.

A colaboração de todos é fundamental para continuarmos melhorando nossas ferramentas de trabalho!

## ✨ Funcionalidades Principais

- **Monitoramento Multi-Chat**: Acompanha múltiplos tickets simultaneamente com cronômetros independentes.
- **Timer de 4 Minutos e 30 segundos**: Alerta automático após 270 segundos de espera pelo cliente.
- **Detecção de Mensagem (Anti-Loop)**: Lógica  que evita que o cronômetro reinicie por erros visuais ou atualizações automáticas do Zendesk.
- **Alerta Visual**: Banner compacto no canto superior direito com número do protocolo e nome do cliente.
- **Zerar Monitores**: A extensão possui um Botão de reset centralizado no ícone da extensão, mas que no momento, **não está funcionando**

## 🛠️ Como Instalar (Passo a Passo)

1.  Baixe o arquivo `zendesk-timer-v1.0-oficial-saipos.zip` e extraia o conteúdo para uma pasta (ex: `Documentos/ZendeskTimer`).
2.  No Chrome, digite `chrome://extensions`.
3.  Ative a chave **"Modo do desenvolvedor"** no canto superior direito.
4.  Clique em **"Carregar sem compactação"** no canto superior esquerdo.
5.  Escolha a pasta onde você extraiu os arquivos.
6.  **Pronto!**: A extensão já aparecerá na lista e estará ativa para o Zendesk.

## 📝 Notas para Manutenção

As configurações principais estão no início do arquivo `content.js`:
- `INACTIVITY_LIMIT`: Altera o tempo de alerta (padrão 4 min).
- `PROCESS_DELAY`: Ajusta a sensibilidade de detecção (padrão 0.5s).

---
*Criado para os Analistas de Suporte da Saipos. Colabore e ajude a evoluir nossa ferramenta!*
