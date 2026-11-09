# Crivo Atendimento: instaladores

Canal de distribuição do **Crivo Atendimento**, o atendente virtual por WhatsApp
(mensagens e ligações) para consultórios, clínicas, salões, restaurantes e outros
negócios pequenos. Este repositório guarda só os instaladores e o manifesto de
atualização; o código-fonte fica em repositório privado.

Serve a dois propósitos:

1. **Download do instalador**: baixe sempre o `CrivoAtendimento-x64-setup.exe`
   da versão mais recente pelo endereço fixo
   <https://github.com/diogohmendesr-create/crivo-atendimento-releases/releases/latest/download/CrivoAtendimento-x64-setup.exe>.
2. **Atualização automática**: o programa instalado consulta o `latest.json` daqui,
   confere a assinatura do instalador com a chave do canal e só então instala.

## Instalação

A instalação é **por usuário**, sem privilégio de administrador. Os dados (agenda,
contatos, conversas e sessões do WhatsApp) ficam em `%LOCALAPPDATA%\CrivoAtendimento`,
no próprio computador, e não são apagados nas atualizações.

Enquanto o instalador não tem certificado de assinatura de código, o SmartScreen do
Windows pode avisar: clique em **Mais informações** e depois em **Executar assim mesmo**.
Confira o código SHA-256 publicado em cada versão, se quiser ter certeza do arquivo.

Passo a passo completo, requisitos e perguntas frequentes:
<https://atendimento.crivolegal.com.br/download.html>.

## Requisitos

- Windows 10 ou 11, 64 bits
- Um número de WhatsApp dedicado ao atendente (no celular da empresa)
- Conexão com a internet
- Conta criada por convite (o produto está em beta fechado; inscreva-se na lista de espera
  em <https://atendimento.crivolegal.com.br>)

## Aviso

Instale somente os arquivos publicados aqui ou no site oficial. Os instaladores são
assinados com a chave do canal; o programa recusa qualquer arquivo com assinatura
diferente.

Crivo Soluções Tecnológicas Ltda. · <contato@atendimento.crivolegal.com.br>
