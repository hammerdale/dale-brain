# Dale's Brain - Configuration

**Repository:** https://github.com/hammerdale/dale-brain

## Quick Access
- This file is your main reference
- On startup, fetch from: https://raw.githubusercontent.com/hammerdale/dale-brain/main/README.md

---

## Email

### LobsterMail
- **Email:** jakes-assist@lobstermail.ai
- **Account ID:** acct_gs6AFsW_Xt-DVzxg
- **Inbox ID:** ibx_8VMhGuQHdLR37s2J
- **Token:** [IN LOCAL CONFIG]
- **Tier:** 0 (needs verification)
- **Expires:** 2026-05-26

### Other Email
- **AgentMail:** dale-assistant@agentmail.to
- **Zoho:** jakewedge.com (SPF, DKIM, DMARC configured)

---

## Tools & APIs

| Tool | Status | Config Location |
|------|--------|-----------------|
| Browser | ✅ agent-browser | Local |
| Hunter.io | ✅ API key configured | Local |
| GitHub | ✅ Token available | Local |
| LobsterMail | ⚠️ Needs verification | Local |
| Zoho Mail | ✅ DNS configured | - |

---

## Credentials (Local Only - Don't Commit)

Store these locally, never commit to GitHub:
- `~/.openclaw/workspace/.lobstermail_token`
- `~/.openclaw/workspace/.lobstermail_inbox`
- GitHub token (in OpenClaw config)

---

## Business

- **Owner:** Jake - 20+ years marketing & sales training
- **Goal:** Build multiple online businesses, starting with automation workflows

---

## Notes

- Old LobsterMail inboxes (jake-dale, dale) from March 28, 2026 - UNRECOVERABLE without old tokens
- Only way to recover is with the original token (lm_sk_...)
- Search GitHub for "lm_sk_" if desperate

---

## How to Use

1. On startup, read this file from GitHub
2. Get live credentials from local config
3. Check LobsterMail tier before sending emails

## API Example
```bash
curl -s -H "Authorization: Bearer [TOKEN]" \
  -H "Content-Type: application/json" \
  -d '{"subject": "test", "body": {"text": "Hello"}}' \
  https://api.lobstermail.ai/v1/emails/send
```
