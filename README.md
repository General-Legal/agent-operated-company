# Agent-Operated Company - Free Incorporation Templates

> Open-source legal templates and step-by-step instructions to form a U.S. company that an **AI agent** can operate day-to-day, while a human owner keeps control and limited-liability protection. Maintained by [General Legal](https://general.legal).

## What this is

A free starter kit for forming a Delaware LLC or C-corporation designed to operate through an AI agent under human oversight.

It includes:

- `templates/` - authoritative Word `.docx` formation and governance documents for C-corporations and LLCs.
- `manifest.json` - packet order, signer roles, substitution fields, and state-filing metadata.
- `filing-instructions/` - instructions for filing, obtaining an EIN, appointing a registered agent, and opening a bank account.

The Word documents use literal `{Field Name}` substitutions. PandaDoc signature fields use tags such as `{signature:founder_____}`; PandaDoc converts these tags into fields assigned to the matching recipient role during upload. `Company Name` means the full legal name, including its entity suffix and punctuation.

Each Word template has a same-basename Markdown companion for AI-assisted drafting. The Markdown file mirrors the operative document content but may also begin with a `Drafting note` block containing completion instructions. Those instructions are intentionally Markdown-only: preserve them when synchronizing the pair, and never copy them into a filing, signature packet, or `.docx` template.

## Ways to use it

1. **Do it yourself.** Use the templates and follow `filing-instructions/`.
2. **Have General Legal file it for you.** General Legal charges $50 for a standard single-class LLC or C-corporation, plus state and registered-agent fees. [Sign up here](https://portal.general.legal/signup?utm_source=github&utm_medium=repo&utm_campaign=agent-operated-company).
3. **Via MCP.** Connect to `https://mcp.general.legal/mcp` using Streamable HTTP and OAuth 2.1 after signing up through the link above.

## Quickstart

1. Read `filing-instructions/README.md`.
2. Choose `templates/certificate-of-formation-llc.docx` or `templates/certificate-of-incorporation-ccorp.docx`.
3. Fill every `{Field Name}` substitution and file only the applicable certificate with the state.
4. Execute the remaining documents in the entity packet in the order listed by `manifest.json`.
5. Obtain an EIN, open a separate business bank account, and observe the governance and recordkeeping requirements.

## Disclaimer

These templates and instructions are provided for general informational purposes only and do not constitute legal, tax, or accounting advice.

- Using these materials does not create an attorney-client relationship with General Legal, LLP. A relationship is formed only after General Legal agrees to represent you following a conflicts check and a signed or clickthrough engagement letter.
- Forming a company and delegating authority to an AI agent involves legal questions that depend on the facts and jurisdiction.
- Forming the entity is not sufficient by itself to preserve limited-liability protection. Maintain a separate bank account, adequate capitalization, and appropriate corporate formalities.

For advice or filing assistance, [engage General Legal](https://portal.general.legal/signup?utm_source=github&utm_medium=repo&utm_campaign=agent-operated-company).
