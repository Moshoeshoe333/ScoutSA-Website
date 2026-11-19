# Website decision ledger

This ledger records decisions that shape the public ScoutSA website. A proposal is not an approved implementation.

| ID | Decision | Status | Rationale | Revisit condition |
|---|---|---|---|---|
| W-001 | Keep ScoutSA-Website separate from the ScoutSA research repository. | Accepted | Protects repository boundaries and prevents accidental disclosure or coupling. | Only by explicit project-owner decision. |
| W-002 | Position the website as a collaboration and credibility channel, not a product portal. | Proposed | The primary goal is to attract suitable collaborators while limiting disclosure of unfinished internals. | Revisit after stakeholder feedback. |
| W-003 | Use the A+B visual direction: premium football identity with grassroots warmth. | Proposed | Balances professional credibility and community relevance. | Revisit after visual concept review. |
| W-004 | Start with a static, responsive website. | Proposed | Minimises cost, attack surface and personal-data handling. | Revisit only when a validated requirement justifies application services. |
| W-005 | No database, authentication, player profiles, scout dashboard or public opportunity listings in the initial release. | Accepted boundary | These features create privacy, safeguarding, security and operational obligations. | Separate approved gate and evidence required. |
| W-006 | Treat all repository content as public because the repository is public. | Accepted | Prevents confidential project material from entering source control. | Revisit only if repository visibility changes; still assume history may persist. |
| W-007 | No claims of guaranteed discovery, trials, contracts, placements, verification or partnerships. | Accepted | Prevents misleading visitors and protects trust. | No exception without evidence and explicit approval. |
| W-008 | No contact form collecting personal data until its data flow and privacy basis are reviewed. | Proposed | Avoids collecting information before ownership, retention and response processes exist. | Review once an approved contact process is ready. |

## Change protocol

For each material decision change, record:
- decision ID;
- previous and new position;
- reason and evidence;
- affected pages, content and controls;
- reviewer and date;
- required tests or approvals.

Do not silently overwrite a decision history. Add a dated amendment or a new decision entry.
