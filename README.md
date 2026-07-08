# Rendro Test

Test repo for Rendro docs hosting.

## CI Sync

Docs are automatically pushed to rendro.app on every push to main.
Set `RENRO_API_KEY` as a GitHub secret.

## Manual Sync

```bash
curl -sL https://raw.githubusercontent.com/Chaitanya045/rendro/main/bin/rendro.mjs -o rendro
chmod +x rendro
RENRO_API_KEY=xxx ./rendro push --source ./docs --org gmail --endpoint https://rendro.app
```
