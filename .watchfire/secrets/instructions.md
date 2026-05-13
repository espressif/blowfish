# Secrets & Setup Instructions

Use this file to tell agents how to access external services and credentials
for this project. Agents will read these instructions before starting work.

## Examples

### CLI Tools (already authenticated)
```
# Firebase — I'm already logged in via `firebase login`
# Use `firebase use <project-id>` to switch projects

# AWS — credentials configured in default profile
# Use `aws sts get-caller-identity` to verify access

# gcloud — authenticated via `gcloud auth login`
```

### Environment Variables
```
# Set these before running the app:
# export DATABASE_URL=<value>
# export API_KEY=<value>
```

### API Keys & Tokens
```
# Stripe test key: use the key in .env.local
# OpenAI: use the org key from 1Password CLI (`op read ...`)
```

---
Delete this sample content and replace with your own instructions.
