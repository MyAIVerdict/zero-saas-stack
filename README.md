# The $0 AI SaaS Stack (2026 Edition)

This is the configuration repository for the "Anti-Subscription" stack featured on MyAIVerdict.com.

## 1. The Stack
- **Editor:** Roo Code (VS Code Extension)
- **Brain:** DeepSeek R1 (via API)
- **Database:** Supabase (Free Tier)

## 2. Roo Code Settings (VS Code)
Copy this into your Roo Code settings JSON to enable the "Reasoning" model:

```json
{
  "apiProvider": "deepseek",
  "modelId": "deepseek-reasoner",
  "temperature": 0.6
}

3. How to Use
Install Roo Code.

Get a key from DeepSeek.

Run Supabase init in your terminal.

Maintained by MyAIVerdict.com
