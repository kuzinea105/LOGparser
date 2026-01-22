# LOGparser

n8n workflow for parsing storage/server logs (Dell, HPE, Lenovo, Huawei, etc.) using local LLM + offline RAG.

## Contents
- `LOGparser WF1305.json` — n8n workflow export (no secrets)

## How it works (high level)
1. Receives archive/log files from chat
2. Unpacks and extracts signal/digest
3. (Optional) Offline RAG lookup
4. LLM produces a structured report (4 sections)

## Notes
- Secrets/tokens are not stored in this repository.
- Configure environment variables in your local n8n `.env`.
