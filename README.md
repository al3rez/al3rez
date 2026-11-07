<div align="center">

### Alireza Bashiri

Applied AI Engineer / Forward Deployed Engineer · Engineering Lead at Humano · Bangkok

[X](https://x.com/al3rez) · [LinkedIn](https://www.linkedin.com/in/al3rez/) · [colm.sh](https://colm.sh)

<br>

<table>
<tr>
<td width="50%" align="center" valign="top">
<a href="https://colm.sh"><img src="https://colm.sh/assets/screenshot.png" alt="colm" width="100%"></a>
<br><b><a href="https://github.com/al3rez/colm">colm</a></b>
<br><sub>The column terminal for coding agents, built on Ghostty</sub>
</td>
<td width="50%" align="center" valign="top">
<a href="https://github.com/al3rez/babbage"><img src="https://raw.githubusercontent.com/al3rez/babbage/main/docs/screenshot-asus.png" alt="babbage" width="100%"></a>
<br><b><a href="https://github.com/al3rez/babbage">babbage</a></b>
<br><sub>An opinionated Debian 13 desktop, built with Nix</sub>
</td>
</tr>
</table>

<br>

</div>

### Experience

<table>
<tr>
<td width="56" valign="top"><img src="logo-wildchild.png" width="48" height="48" alt="Wildchild"></td>
<td valign="top" align="left"><b>Wildchild</b><br><sub>Forward Deployed Engineer · Sep 2026 - Present</sub><br><br>Wildchild AI OS: Humano's multi-tenant agent and application platform. Meridian is the imaginary reference client used for evals and demos.<ul><li>Led the cutover of the runtime and workflows from Python to native .NET 10 / ASP.NET Core, removing 37K+ lines of Python. Shipped a Python-free image, an Aspire one-click local platform, and native production on GKE with digest-based release, backup, rollback, and Cloud Monitoring.</li><li>Built the agent surface clients use: a version-pinned skills library (max 12, fails closed), custom connectors (BigQuery, Composio, HTTPS JSON, remote MCP over streamable HTTP, SSRF-safe with row, time, and size caps), builder chat across devices, shared project rooms, and per-prospect workspaces. Several are in review as of Nov 2026.</li><li>Evals gate what ships. Two frozen Langfuse datasets on synthetic Meridian data: context-graph Q&amp;A went from 2/10 to 9/10 and invoice routing from 19/40 to 38/40, with gates on exception recall and log precision. Online LLM-judge scores, self-hosted Langfuse, OTel into Cloud Trace.</li><li>Each client gets an immutable OCI image, never the source repo. Deployable into client clouds behind provider seams; Keycloak OIDC and Google IAP for tenancy.</li></ul></td>
</tr>
<tr>
<td width="56" valign="top"><img src="logo-humano.png" width="48" height="48" alt="Humano"></td>
<td valign="top" align="left"><b>Humano</b><br><sub>Engineering Lead / Forward Deployed Engineer · Sep 2024 - Present</sub><br><br>Product owner and technical lead on client projects. Manage two QA engineers and two FDEs; run hiring. Joined for the LiveTwin MVP; now lead across Humano products and client work.<br><br>Internal: shared Jenkins CI/CD (merge to Cloud Run in 45-70s), Foundry (ticket to coding agent to green PR), Fyndry Slack agents with secrets kept out of sandboxes.</td>
</tr>
<tr>
<td width="56" valign="top"><img src="logo-equisoft.png" width="48" height="48" alt="Equisoft RFX"></td>
<td valign="top" align="left"><b>Equisoft RFX</b><br><sub>Humano client · InsurTech, Canada data residency</sub><br><br><ul><li>Challenged a SharePoint-only scope in discovery; the client reframed the win as fewer wrong answers, faster. Agreed weekly feedback (~50 answers/week for ~3 months) and mockups before UI.</li><li>Shipped Azure Container Apps (Bicep/azd), Entra SSO, IDOR/SSRF-gated APIs, bulk Q&amp;A upload, DOCX extraction of 121 requirements (62 tests, Azure prod).</li><li>Answers draw on 1,200+ approved Q&amp;As: exact match, then near match, then 70/30 hybrid RAG, then a human, with a claim verifier and Langfuse. Hotfixed an import that read 21 of ~409 questions.</li></ul></td>
</tr>
<tr>
<td width="56" valign="top"><img src="logo-bumi.svg" width="48" height="48" alt="Bumi"></td>
<td valign="top" align="left"><b>Bumi</b><br><sub>Humano client · Malaysian consumer lending, in production since July 2026</sub><br><br><ul><li>Constraints: BNM audit logging, maker-checker, 7-year WORM retention, 60% DSR ceiling, a partner bank portal with no API.</li><li>Shipped Innov8tif eKYC, headless portal sync, multi-bank routing, GPT-4o-mini document vision and a decline classifier (humans on doubtful cases, never auto-reject), WhatsApp/SMS OTP, Pulumi GCP, Jenkins CI, and a 13-finding pentest remediation.</li><li>About 470 API and Playwright specs gate each release; I own CI, staging, QA, and client retest.</li></ul></td>
</tr>
<tr>
<td width="56" valign="top"><img src="logo-livetwin.png" width="48" height="48" alt="LiveTwin.ai"></td>
<td valign="top" align="left"><b>LiveTwin.ai</b><br><sub>Humano product · app.livetwin.ai</sub><br><br><ul><li>Production owner (Vercel, Infisical).</li><li>25-tool MCP server, Tavus real-time avatars, Neo4j and Qdrant memory, Salesforce/HubSpot via Composio, 96.2% statement coverage.</li><li>Shipped a client product-expert avatar.</li></ul></td>
</tr>
</table>

### Stack

<img src="https://skillicons.dev/icons?i=python,ts,dotnet,nodejs,nestjs,nextjs,supabase,azure,gcp,kubernetes,docker,nix,zig,linux" alt="stack">

<sub>MCP · agent skills · Langfuse · LiteLLM · Temporal · Neo4j · Qdrant · Playwright</sub>
