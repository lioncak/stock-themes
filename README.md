# stock-themes

Taiwan stock theme / concept mappings used by [stock-line-bot](https://github.com/lioncak/stock-line-bot).

## Structure

```
themes/
├── AI人工智慧.md
├── ChatGPT.md
├── CoWoS.md
├── GB200.md
├── GB300.md
├── HBM.md
├── PCB.md
├── 散熱模組.md
├── 電動車.md
└── ...  (67 themes total)
```

Each `.md` file lists the member stocks of a theme in the format:

```markdown
**2330 台積電**
**2454 聯發科**
...
```

## Sources

| Group | Count | Source |
|---|---|---|
| Original (fork from Timeverse/My-TW-Coverage) | 20 | Manual curation |
| Custom additions | 10 | Manual curation |
| CMoney concept stocks | 37 | CMoney official concept tables |

## Usage

The line bot reads these files directly via raw GitHub URL:

```
https://raw.githubusercontent.com/lioncak/stock-themes/master/themes/{theme}.md
```

## Upstream

Forked from [Timeverse/My-TW-Coverage](https://github.com/Timeverse/My-TW-Coverage).
