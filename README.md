<div align="center">

# 📈 Monitor IQ Option

**Monitor de padrões de candles em tempo real para opções binárias na IQ Option**

[![Última versão](https://img.shields.io/github/v/release/RalphRebello/market-monitor-releases?label=vers%C3%A3o&color=2ea44f)](https://github.com/RalphRebello/market-monitor-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/RalphRebello/market-monitor-releases/total?label=downloads&color=blue)](https://github.com/RalphRebello/market-monitor-releases/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?logo=windows&logoColor=white)

### [⬇️ Baixar a última versão](https://github.com/RalphRebello/market-monitor-releases/releases/latest)

</div>

---

## O que é

O monitor acompanha **todos os ativos abertos** do tipo que você escolher (binárias, digitais, forex...) e,
a cada candle fechado, procura as sequências de candles dos padrões configurados. Quando um padrão se forma,
ele avisa na hora, com popup e som, mostrando **o ativo, o padrão e o horário da entrada**.

Ele só lê os candles: **não abre operações nem mexe no seu saldo**.

## Recursos

- 🔍 **Procura em todos os ativos abertos** do tipo escolhido, estejam ou não na tela
- 🔔 **Alerta na hora**: popup colorido e som, ~1,5 s após o fechamento do candle
- 🖱️ **Clique no alerta** para abrir o cartão do ativo que alertou
- 🌡️ **Termômetro dos padrões** em cada cartão: quanto de cada padrão já se formou, quantos candles faltam
  e o horário previsto da entrada
- 🧩 **Padrões e sequências** que você liga e desliga no painel, sem reiniciar a procura
- 🕐 **Filtro de minutos** opcional nos padrões que têm regra de horário
- 📝 **Histórico** de cada padrão salvo em arquivos na pasta `logs\`
- 💾 **Escolhas salvas**: ativos, tempo, padrões ligados e tamanho da janela voltam como você deixou
- 🔄 **Reconexão automática** se a conexão cair ou parar de responder
- 🪟 **Janela que se adapta** a qualquer tamanho, com áreas ajustáveis

## Como instalar

1. Baixe o `MonitorIQOption-vX.Y.Z.exe` em
   [**Releases**](https://github.com/RalphRebello/market-monitor-releases/releases/latest) (em *Assets*).
2. Coloque o arquivo numa pasta só dele, por exemplo `C:\MonitorIQOption\`. O histórico é gravado na pasta
   `logs\`, ao lado do `.exe`.
3. Dê dois cliques no `.exe`. Não precisa instalar nada.

> [!NOTE]
> Na primeira vez, o Windows pode mostrar **"O Windows protegeu o computador"**. Isso acontece porque o
> executável não tem assinatura digital paga. Clique em **Mais informações → Executar assim mesmo**.

## Como usar

1. Entre com o **e-mail e a senha da sua conta IQ Option** e clique em **Entrar**.
2. Escolha o **Tipo** de ativo e o **Tempo** dos candles.
3. Clique em **Iniciar procura**.
4. Use o **+** para colocar na tela os ativos que você quer acompanhar de perto. Os alertas chegam de todos
   os ativos abertos, com ou sem cartão.

O e-mail e a senha **nunca são gravados**: eles só são usados para conectar.

## Como atualizar

1. Baixe o `.exe` da versão nova em
   [**Releases**](https://github.com/RalphRebello/market-monitor-releases/releases/latest).
2. Feche o monitor, apague o `.exe` antigo e coloque o novo na mesma pasta.

Suas escolhas e o histórico continuam: as escolhas ficam em
`%USERPROFILE%\.config\monitor_padroes\` e o histórico na pasta `logs\`, que não são apagados.

## Requisitos

- Windows 10 ou 11 (64 bits)
- Conta na IQ Option (de preferência comece pela **conta de treinamento**)
- Internet estável

## ⚠️ Aviso

- Este é um projeto pessoal, **sem ligação com a IQ Option**. A IQ Option não tem API pública e o monitor usa
  uma biblioteca não oficial, que pode parar de funcionar se a plataforma mudar.
- O uso de ferramentas de automação pode contrariar os termos de uso da IQ Option. **Use por sua conta e risco.**
- Os alertas são **apenas informativos** e não são recomendação de investimento. Opções binárias têm alto
  risco e você pode perder todo o valor investido.

---

<div align="center">
<sub>O código-fonte é privado. Este repositório guarda apenas as versões publicadas do monitor.</sub>
</div>
