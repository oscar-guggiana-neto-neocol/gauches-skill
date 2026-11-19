# Gauchês 🧉

Um skill para o Claude conversar contigo em **gauchês**: o jeito de falar do Rio Grande do Sul, com "tu", "bah", "tchê", "tri", "bagual", "capaz" e companhia.

O conteúdo das respostas continua igual em precisão. Só muda o sotaque.

## O que ele faz

- Usa "tu" com o verbo do jeito coloquial gaúcho ("tu vai", "tu viu?").
- Traz interjeições, vocabulário (mais de 70 palavras), comparações e ditados do RS.
- Tem três níveis de intensidade: **leve** (assunto sério), **médio** (padrão) e **forte** (papo descontraído, ou quando tu pedir "carrega no gauchês").
- Não mexe em código, números, termos técnicos nem em e-mails e documentos que tu vai mandar pra outras pessoas.
- Para na hora se tu disser "fala normal".

## Exemplo

> **Neutro:** Ficou ótimo! O teste passou em todos os cenários.
>
> **Gauchês:** Bah, ficou tri bom! O teste passou em todos os cenários. Pode ficar faceiro.

## Como instalar

### No app do Claude (claude.ai, desktop ou celular)

1. Baixa este repositório como `.zip` (botão **Code → Download ZIP**) ou só a pasta `gauches`.
2. Compacta a pasta `gauches` (com o `SKILL.md` dentro) num `.zip`.
3. No Claude, vai nas configurações de **Skills** e envia o `.zip`.
4. Para valer em todas as conversas, coloca nas tuas preferências algo como: *"sempre usar o skill gauches comigo"*.

### No Claude Code

```bash
git clone https://github.com/oscar-guggiana-neto-neocol/gauches-skill.git
mkdir -p ~/.claude/skills
cp -r gauches-skill/gauches ~/.claude/skills/
```

O Claude Code carrega o skill na próxima sessão.

## Estrutura

```
gauches/
└── SKILL.md   # instruções completas do skill
```

## Contribuindo

Conhece uma expressão gaúcha que ficou de fora? Abre uma issue ou um pull request, tchê. Só pedimos expressões reais e correntes no RS, sem termos pejorativos.

## Licença

MIT. Pode usar, adaptar e compartilhar à vontade.
