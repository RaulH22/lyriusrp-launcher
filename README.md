<div align="center">

# LyriusRP Launcher

**O launcher oficial do servidor de Minecraft LyriusRP.**
Entra no servidor sem `/login`, instala o modpack sozinho e se atualiza sozinho.

[**⬇ Baixar o launcher**](https://lyriusrp-conta.rubber-launcher.workers.dev/download) ·
[Criar conta](https://lyriusrp-conta.rubber-launcher.workers.dev/cadastro) ·
[Discord](https://discord.com/invite/lyrius) ·
[Loja](https://loja.lyriusrp.com/)

</div>

---

> [!IMPORTANT]
> **Baixe sempre pelo site:** <https://lyriusrp-conta.rubber-launcher.workers.dev/download>
> Lá tem o passo a passo da instalação e a versão mais nova. Não use instaladores enviados por outras
> pessoas (Discord, WhatsApp…): eles podem ter sido alterados.

Este repositório guarda **só os instaladores** (aba [Releases](../../releases)), de onde o launcher
baixa as atualizações automáticas. O código-fonte não fica aqui.

## O que o launcher faz

- **Conta Lyrius:** entre uma vez e jogue no servidor **sem digitar `/login`**. Dá para ter mais de um nick
  na mesma conta e trocar na tela inicial.
- **Conta Microsoft (Minecraft original):** também funciona, e dá para ligar um nick da conta Lyrius à
  sua conta original.
- **Modpack automático:** os perfis oficiais (LyriusRP, LyriusZombie…) baixam e atualizam os mods
  sozinhos. Também dá para criar perfis próprios, importar `.mrpack`/Modrinth/Prism e procurar mods no
  Modrinth pelo próprio launcher.
- **Skins e capas:** troque a skin de cada nick; todo mundo no servidor vê.
- **Estatísticas:** tempo de jogo por perfil, conta, nick e servidor.
- **Notícias** do servidor na tela inicial, **Discord Rich Presence**, logs do jogo e aviso claro
  quando o jogo fecha com erro (inclusive driver de vídeo desatualizado).
- **Atualização automática:** o launcher procura versão nova ao abrir, baixa em segundo plano e instala
  ao fechar. Não precisa baixar de novo daqui.

## Requisitos

- Windows 10 ou 11, 64 bits
- 4 GB de RAM (8 GB recomendado para jogar com mods)
- Placa de vídeo com OpenGL 3.2 ou mais e driver atualizado
- Uns 3 GB livres no disco
- O Java certo é baixado pelo próprio launcher

## Instalação

1. Baixe o instalador pelo [site](https://lyriusrp-conta.rubber-launcher.workers.dev/download)
   (precisa de uma conta com o e-mail confirmado).
2. Abra o arquivo `lyriusrp-launcher-setup-X.Y.Z.exe`.
3. Se aparecer **"O Windows protegeu o computador"**, clique em **Mais informações** →
   **Executar assim mesmo**.
4. Siga o assistente, abra o launcher e entre com a sua conta.

### Por que o Windows mostra esse aviso?

É o **Microsoft Defender SmartScreen**. Ele aparece para programas que ainda são pouco baixados ou que
**não têm assinatura digital**: um certificado pago, renovado todo ano, que identifica quem fez o
programa. Por isso a janela diz _Fornecedor desconhecido_.

O launcher ainda não tem esse certificado. **Isso não quer dizer que ele tem vírus:** só que o Windows
ainda não conhece o programa. Quanto mais gente instala, menos o aviso aparece.

Para conferir o arquivo, cada Release mostra o **SHA-256** de cada instalador (o GitHub calcula
sozinho). Você pode procurar esse código no [VirusTotal](https://www.virustotal.com/) — o site de
download já tem um link direto.

## Perguntas frequentes

**O antivírus bloqueou ou apagou o instalador.**
Alguns antivírus desconfiam de programas novos sem assinatura digital. Confira o arquivo no VirusTotal
e, se estiver tudo certo, crie uma exceção no antivírus e baixe de novo.

**Onde o launcher guarda os arquivos?**
Em `%APPDATA%\LyriusRP Launcher` (cole na barra do Explorador de Arquivos): perfis, mundos, prints e logs.

**Como desinstalar?**
Configurações do Windows → **Aplicativos** → **LyriusRP Launcher** → **Desinstalar**. A pasta acima
continua guardando seus mundos até você apagá-la.

**Achei um problema / preciso de ajuda.**
Fale com a equipe no [Discord](https://discord.com/invite/lyrius). Se puder, mande o log da aba
**Logs** do launcher (o launcher nunca grava senhas nem tokens nos logs).

---

<details>
<summary><b>English</b></summary>

**LyriusRP Launcher** is the official launcher for the LyriusRP Minecraft server: play without typing
`/login`, get the modpack installed and updated automatically, and receive launcher updates on its own.

- **Download it from the website only:** <https://lyriusrp-conta.rubber-launcher.workers.dev/download>
  (requires an account with a confirmed e-mail). This repository only hosts the installers used by the
  auto-updater; the source code is not here.
- **Requirements:** Windows 10/11 64-bit, 4 GB RAM (8 GB recommended), OpenGL 3.2+ graphics with an
  up-to-date driver, ~3 GB of free disk space. Java is downloaded by the launcher.
- **"Windows protected your PC":** click **More info** → **Run anyway**. Windows SmartScreen shows this
  for programs without a paid code-signing certificate (_Unknown publisher_). It does not mean the
  program is unsafe; you can check each installer's SHA-256 (listed in every Release) on VirusTotal.
- **Help:** [Discord](https://discord.com/invite/lyrius).

</details>
