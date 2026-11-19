# Website architecture

**Status:** Foundation proposal  
**Target:** Public-facing ScoutSA information website  
**Hosting preference:** Cloudflare Pages  
**Source repository:** ScoutSA-Website (separate from the ScoutSA research repository)

## 1. Product boundary

The initial website is a responsive, primarily static information and collaboration website. It introduces the initiative and provides a safe route for prospective collaborators to make contact.

It is not the ScoutSA platform itself.

## 2. Initial page map

- **Home:** concise mission, problem framing, principles and collaboration invitation.
- **About:** purpose, values and current stage.
- **Players:** public explanation of the intended focus on grassroots talent; no profiles or registration.
- **Coaches & Academies:** who the initiative hopes to learn from and collaborate with.
- **Opportunities:** responsible-opportunity principles and clear non-guarantee language; no live listings.
- **Partners:** collaboration areas and an invitation to discuss contribution.
- **Safeguarding:** public commitments, boundaries and contact/escalation guidance once approved.
- **Contact:** approved official enquiry route only.

Navigation may be simplified during prototyping. Page names do not imply that a service is operational.

## 3. Technical baseline

| Area | Initial position |
|---|---|
| Delivery | Static site |
| Hosting | Cloudflare Pages |
| Source control | Separate GitHub repository |
| Domain | Custom domain considered later |
| Database | None |
| Authentication | None |
| Player accounts | Not in scope |
| Public player profiles | Not in scope |
| Scout dashboard | Not in scope |
| Opportunity listings | Not in scope |
| Forms collecting personal data | Not in scope until reviewed |
| Analytics | Off by default pending privacy review |

A lightweight static framework may be selected after the design prototype and deployment requirements are reviewed. Avoid adding dependencies without a clear need.

## 4. Quality requirements

- Responsive from small mobile screens upward.
- Semantic HTML and keyboard-operable navigation.
- Accessible colour contrast, visible focus and meaningful alternative text.
- Good performance and minimal third-party scripts.
- HTTPS and secure deployment configuration.
- No secrets or private data in source, build output or client-side code.
- Clear error and unavailable states for any future interactive feature.
- Automated checks for links, accessibility basics, build output and prohibited content where practical.

## 5. Future change control

Any move beyond static public information requires a separate decision and risk review. Database, authentication, personal-data collection, player profiles, messaging, dashboards and opportunity publication are excluded until their requirements, ownership, safeguarding controls, privacy basis, security design, testing and approval are documented.

## 6. Repository separation

The website project must not modify, import, mirror or expose the internal research and domain-model materials of the separate ScoutSA repository. Only explicitly approved public facts and assets may cross this boundary.

## 7. Deployment boundary

Cloudflare Pages is the intended hosting target, not a claim that deployment is configured or live. Production deployment, custom-domain activation and public launch each require explicit review and approval.
