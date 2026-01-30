
# action-repo

This repo is used to trigger GitHub events:
- Push
- Pull Request
- Merge

Configure webhook:
Settings → Webhooks → Payload URL → http://<your-server>/webhook
Content-Type: application/json
Events: Push, Pull Request
