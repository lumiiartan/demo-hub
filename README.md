# Demo Hub

**Meeting URL:** https://lumiiartan.github.io/demo-hub/

One page that lists all digitalization demos. Open this in client meetings.

## Live demos linked here

| Demo | Live | Repo |
|------|------|------|
| Bursat Suharekë | https://lumiiartan.github.io/bursat-suhareke/ | [bursat-suhareke](https://github.com/lumiiartan/bursat-suhareke) |
| Praktika IAAP | https://lumiiartan.github.io/praktika-iaap/ | [praktika-iaap](https://github.com/lumiiartan/praktika-iaap) |

## Handbook

https://github.com/lumiiartan/digitalization-handbook

## Add a new demo (5 minutes)

1. Create a new public repo for the demo and enable **GitHub Pages**.
2. Edit `index.html` in this repo — add an object to the `demos` array (title, blurb, `live`, `repo` in `sq` + `en`).
3. Push. The hub updates automatically.

## Local preview

```bash
cd demo-hub
python3 -m http.server 5175
```

Open http://127.0.0.1:5175/
