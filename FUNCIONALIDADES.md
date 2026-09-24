# Tomo: o que já tem e o que vem por aí

O Tomo é um **sistema de suporte para o mestre de RPG**, feito para **mesas presenciais** e **mesas no Discord**, para quem não quer usar um VTT (aquelas mesas virtuais com mapa e fichas).

> **Aviso honesto:** esta é uma versão **bem inicial, ainda antes da alfa**. Pode ter bug, e muita coisa vai mudar. A ordem abaixo também pode mudar, conforme o feedback de quem testa.

[Voltar para a página de download](README.md)

## Como ler esta lista

| Marca | Significa |
|---|---|
| ✅ | Já funciona no APK que está no link de download |
| 🧪 | Pronto e em teste, chega na próxima atualização |
| 🔜 | Planejado, ainda não existe |

## Plataformas

| Plataforma | Situação |
|---|---|
| **Android** | ✅ Único disponível no momento (por isso o arquivo é um APK) |
| **Windows** | 🔜 Planejado, depois do Android |
| **iPhone (iOS)** | Ainda não. Não está nos planos por enquanto |

---

## O que já tem (versão 0.0.1 e o começo da 0.0.2, de teste)

- ✅ **Mesas**: uma para cada campanha, com nome, descrição e um ícone pixel art à sua escolha.
- ✅ **Mobs completos**: comum, elite ou chefe, com descrição, defesas e atributos (valor fixo ou dado).
- ✅ **Ataques**: de dado ou de teste de dificuldade, com vários danos (1d6, 2d8+5...) e efeitos.
- ✅ **Habilidades** e **anotações do mestre**, que abrem e fecham ao toque.
- ✅ **Ficha do mob** com tudo numa tela só.
- ✅ **Vida com barra** e botões -10, -1, +1 e +10, mais restaurar.
- ✅ **Modo horda**: vários mobs iguais numa ficha só, com uma barra de vida para cada um e dano em área.
- ✅ **Favoritos, busca por nome e filtro** por nível. A lista continua rápida mesmo com centenas de mobs.
- ✅ **Ícone ou imagem em cada mob**: 20 ícones de mob para escolher, ou uma foto da galeria. A foto é reduzida e guardada só no seu celular, e, se ela sumir, o mob mostra o ícone com um aviso e o botão de reenviar.
- ✅ **Duplicar um mob**: cria uma cópia com tudo, com a vida cheia.
- ✅ **Modo exibição**: mostra a imagem do mob em tela cheia para os jogadores, sem revelar a vida, os ataques nem as anotações do mestre.
- ✅ **Backup**: exportar todas as mesas (ou só uma) em um arquivo JSON e importar de volta, com resumo antes de gravar. Nada do que você já tem é apagado, e uma mesa com o mesmo nome entra como cópia. As imagens ficam só no celular e não vão no arquivo.
- ✅ **Lembrete de backup**: depois de 3 dias sem backup, a lista de mesas avisa, e as Configurações mostram o último backup.
- ✅ **Configurações**: escolher o tema (claro, escuro ou automático).
- ✅ **Sem conta e sem internet**: tudo fica salvo no seu celular.
- ✅ **Visual pixel art** (8 bits) com tema escuro e claro, que acompanha o celular.

## O que falta para fechar a 0.0.1

- 🔜 Testes finais e ajustes, com a ajuda de quem está testando.

---

## O que vem depois

### 0.0.2: conforto e backup (o que falta)
- 🔜 **Copiar um mob para outra mesa**.
- 🔜 **Categorias** criadas por você.
- 🔜 **Áudio** nos mobs.
- 🔜 Exportar e importar **completo** (Excel ou JSON, com a opção de incluir as imagens).
- 🔜 Importar várias imagens e áudios de uma vez.
- 🔜 Ver quais mídias sumiram e quanto espaço elas ocupam.

O **backup automático** e a **senha do backup** ficam para a 0.5.0, junto com a conta.

### 0.1.0: NPCs, Discord e sistema da mesa
- 🔜 **NPCs**, junto dos mobs.
- 🔜 **Sistema da mesa**: ao criar a mesa você escolhe o sistema (no começo, Livre ou D&D 5e), e ele define como o modificador é calculado, como se rola e como funciona a iniciativa. Dá para trocar depois, com um aviso do que se adapta.
- 🔜 **Rolador de dados**: tocar num ataque ou atributo e ver o resultado rolar.
- 🔜 **Discord por webhook**: um botão "Mostrar" envia o mob ou o NPC para o canal da sua mesa, sem as anotações do mestre. As rolagens também podem ir para o canal.
- 🔜 O app continua funcionando sem internet. Só o "Mostrar" precisa de conexão.

### 0.2.0: mundo
- 🔜 **Locais** em hierarquia (país, região, cidade), com blocos opcionais (topografia, militar, economia e política).
- 🔜 **Organizações e facções**, inclusive secretas.
- 🔜 **Vínculos** entre qualquer item (um mob a um mapa, um NPC a uma organização).
- 🔜 **Sessões**: data, resumo, dados da sessão e planejamento das próximas.

### 0.3.0: mapas, viagem e eventos
- 🔜 **Mapa sobre a sua imagem**, com grade **quadrada ou hexagonal**. Você move, amplia e gira a imagem até encaixar na grade, e define quanto vale cada célula (por exemplo, 5 pés).
- 🔜 **Zonas** dos reinos pintadas célula a célula, com nome, descrição e uma bandeirola (a capital) com ícone e ligações a organizações, NPCs, cidades e dungeons.
- 🔜 **Pontos de interesse** com ícone, cor, nome e descrição, que você mostra ou esconde dos jogadores.
- 🔜 **Grupos** no mapa: mais de um, para dividir e juntar, movidos arrastando o ícone.
- 🔜 **Régua de distância** e alcance, pela escala do mapa.
- 🔜 **Mapas dentro de mapas**: o mapa da cidade dentro do mapa do reino, cada um com a sua escala.
- 🔜 **Viagem** com rota, etapas e o caminho percorrido, e **eventos de viagem** por tabela sua ou por sugestão de IA. Nada entra sem a sua aprovação.
- 🔜 Visões salvas (política, viagem, terreno) e exportar o mapa em imagem.

### 0.4.0: dungeon e combate
- 🔜 **Dungeon por salas**, com perigos, mobs, conexões e névoa opcional.
- 🔜 **Mapas de combate** com os mobs posicionados.
- 🔜 **Zonas de efeito** (como uma zona de lava com dano), **obstáculos**, **objetos para interagir** (baú, corpo, alavanca) e **armadilhas**, cada um com a cor que você escolher.
- 🔜 **Iniciativa** e vida durante o combate, com a escolha de qual grupo entra.

### 0.5.0: conta, nuvem e versão do jogador
- 🔜 Criar conta, entrar e sair.
- 🔜 **Backup automático** na nuvem.
- 🔜 **Senha do backup**, para proteger os seus arquivos de backup.
- 🔜 **Perfis offline** com senha, para usar sem internet.
- 🔜 **Convite para a mesa**, com papel de mestre ou jogador.
- 🔜 **Visibilidade por item**: "só mestre" ou "revelado aos jogadores".
- 🔜 **Ficha do jogador**.

### 0.6.0: sistemas de RPG e itens
- 🔜 Modelos prontos de sistema (a partir do D&D 5e), usando só conteúdo de licença aberta ou o que você mesmo cadastra.
- 🔜 **Inventário e itens**, **crafting** e **progressão de nível**.

### 0.7.0: bot do Discord e nuvem de arquivos
- 🔜 **Bot do Discord**: vincular a mesa pelo Discord, escolher para qual canal cada coisa vai e usar o "Mostrar" direto pelo bot.
- 🔜 Mapa e rota por comando do Discord.
- 🔜 Backup e áudio de sessão no **Google Drive ou OneDrive** da própria pessoa.

### 0.8.0: Windows
- 🔜 Versão instalável para Windows, feita a partir do mesmo código do Android.

### 0.9.0 e 1.0.0
- 🔜 Idiomas (português e inglês) e testes finais.
- 🔜 Lançamento oficial, na Play Store.

---

## Tem uma sugestão?

Se algo que você precisa não está na lista, conte para a gente. Como dar feedback está no [README](README.md#como-dar-feedback).

## Aviso

Copyright (c) 2026 Mayco (Maycotkp). **Todos os direitos reservados.** O Tomo, incluindo o aplicativo, o código, o design, os textos e as ideias, pertence ao autor. Esta lista é só informativa: não é permitido copiar ou reutilizar as ideias e os textos sem autorização por escrito do autor.
