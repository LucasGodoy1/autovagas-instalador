# AutoVagas

Programa para **Windows** que procura vagas para você, avalia com inteligência artificial se combinam com o seu currículo e, se você quiser, **se candidata por você**. Funciona no LinkedIn (e na Catho, se você ligar).

## [⬇️ BAIXAR O AUTOVAGAS 1.0.0](https://github.com/LucasGodoy1/autovagas-instalador/releases/download/v1.0.0/AutoVagas-1.0.0.msi)

> Clique no botão acima, abra o arquivo baixado e siga o instalador. Leva uns 3 minutos.

---

## O que você precisa

| | |
|---|---|
| 💻 Computador | Windows 10 ou 11, com **Google Chrome** ou **Microsoft Edge** (o Edge já vem no Windows) |
| 👤 Conta | Uma conta no **LinkedIn** (e, se quiser, na Catho) |
| 🤖 Chave da IA | Uma chave de API do serviço de IA que você preferir: **DeepSeek, ChatGPT, Claude, Gemini, OpenRouter** ou outro compatível. O custo é seu, direto com o serviço. Sem preferência? O DeepSeek é o mais barato (uns **US$ 2** de crédito rendem bastante) |
| 📄 Currículo | O seu currículo em **PDF ou Word** |

## Instalando

1. Baixe o arquivo `AutoVagas-….msi` pelo botão acima.
2. Abra o arquivo. Se o Windows mostrar **"O Windows protegeu o computador"**, clique em **Mais informações** e depois em **Executar assim mesmo**. Isso acontece porque o instalador é independente e não tem a assinatura paga da Microsoft; ele pode ser conferido pelo código.
3. Leia os termos, clique em **Avançar** até **Concluir**. Não precisa de senha de administrador.
4. O AutoVagas abre sozinho: uma **janela preta** (é o motor do programa, deixe aberta) e uma **página no navegador** com o assistente de configuração.

## Primeira configuração (o assistente guia você)

O assistente mostra cada etapa e só libera o robô quando as obrigatórias estiverem prontas:

1. **Termos de uso**: o que fica no seu computador, o que vai para a IA e os riscos.
2. **Chave da IA**: escolha o serviço e cole a sua chave; o programa confere e escolhe dois modelos (um rápido e um forte), que você pode trocar.
3. **Seu perfil**: seu nome.
4. **Currículo**: envie o PDF ou Word; o programa lê e preenche o seu perfil e sugere cargos.
5. **Dados pessoais**: nome completo, e-mail, telefone e cidade (CPF, nascimento e endereço são opcionais e só usados quando um formulário pedir).
6. **O que você procura**: cargos, remoto/híbrido/presencial, nível e salário mínimo.
7. **Entrar no LinkedIn**: uma janela abre; entre normalmente. O programa guarda só a sessão, nunca a sua senha.

Pronto! Ele começa no modo **"Só pesquisar"**: busca e recomenda vagas, **sem enviar nada**. Quando confiar nas recomendações, ligue o modo **automático** no painel.

## No dia a dia

- **Painel** (abre no navegador): vagas recomendadas, candidaturas feitas, consumo da IA (e o saldo, no DeepSeek) e o que precisa de você.
- **Respostas salvas**: veja e corrija o que o robô responde nos formulários.
- **Parar**: botão no painel, ou feche a janela preta.
- Limite de segurança: **40 candidaturas a cada 24 horas**, com pausas, para reduzir o risco para a sua conta.
- O robô trabalha com o **navegador visível**: você acompanha e pode intervir. Se um site pedir verificação (CAPTCHA), ele avisa na tela e espera você.

## Atualizações

O programa avisa quando há versão nova (faixa azul no topo). Clique em **Atualizar agora**: ele baixa, confere a assinatura e instala sozinho. Também dá para clicar em **Verificar atualização** no rodapé do painel.

## Privacidade

- Currículo, dados, histórico e sessões ficam **só no seu computador**, em `AppData\Local\AutoVagas`.
- **Nada é enviado ao criador do programa.** Não existe servidor nem conta.
- O que sai do computador: as suas ações nos sites que você conectou; trechos do currículo e do perfil para o **serviço de IA que você escolheu** (para avaliar vagas e preencher formulários); e a consulta da versão mais recente ao GitHub.
- A chave da IA é sua e fica gravada só no seu computador.

## Perguntas frequentes

**O LinkedIn pode bloquear a minha conta?** O LinkedIn limita automação nos termos dele. O programa usa limites e pausas, mas o risco existe e é seu. Comece no modo "Só pesquisar".

**Quanto custa a IA?** Depende do serviço e de quantas vagas avaliar. O painel mostra o consumo (e o saldo, no DeepSeek). Avaliar vagas custa frações de centavo; preencher formulários de sites de empresas custa mais. Você controla o gasto pelo crédito que coloca na sua conta de IA.

**Posso usar para outra pessoa?** Só com a permissão dela. Cada pessoa tem perfil, currículo e login próprios (menu "Pessoas").

**Como desinstalar?** Configurações do Windows → Aplicativos → AutoVagas → Desinstalar. Seus dados continuam na pasta `AppData\Local\AutoVagas`; apague-a se quiser remover tudo.

**O robô não encontrou o Chrome.** Instale o Google Chrome (google.com/chrome); o Edge também serve.

**Esqueci de entrar no LinkedIn / a sessão caiu.** No painel, clique em **Conectar LinkedIn**.

---

*Programa independente, sem vínculo com LinkedIn, Catho ou com os serviços de IA.*
