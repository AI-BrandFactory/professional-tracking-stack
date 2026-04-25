# The Compliant Tracking Stack for Professionals

Conversion tracking quietly broke for professional services in 2025 and 2026. Consent Mode v2 became mandatory in the EEA. Meta restricted lower-funnel events for healthcare and behavioral health accounts. Third-party cookies are gone in Chrome. Most law firms, medical practices, and home service businesses are flying blind on attribution and do not know it. This is the playbook that fixes it: GA4, Meta CAPI, Google Ads Enhanced Conversions, CallRail, and consent management, set up the way your industry's rules require, with a companion git repo that has the working code.

---

> **Part of the AI BrandFactory open toolkit.**
> Free to use and adapt with attribution.
> More tools, templates, and AI systems at [aibrandfactory.com](https://www.aibrandfactory.com)

---

## What's Inside

- GA4 plus Google Tag Manager plus Consent Mode v2: the foundation every professional services site needs in 2026, with the consent gating logic that keeps you legal in the EEA, California, and Quebec.
- Server-side conversions via Meta CAPI and Google Ads Enhanced Conversions: how to send leads back to the ad platforms without leaking PHI, attorney privilege, or PII, with the SHA-256 hashing pattern and the eventID dedup logic.
- The vertical-specific layer: doctor pattern (HIPAA, Meta health-cat restrictions, BAA-signed CDP), lawyer pattern (state bar advertising rules, privilege-preserving forms), home service pattern (call-driven, service-area attribution, route tracking).
- Call tracking done right: CallRail dynamic number insertion that survives React hydration, BAA setup for medical, recording controls for legal, plus the callback API that fires GA4 and Google Ads conversions on every qualified call.
- Lead attribution that survives: the first-party UTM capture middleware, the lead_attribution table schema, the Google Search Console API integration that pulls the actual organic queries driving traffic to each landing page.
- Validation, deployment, and the 8 failures that silently break tracking: GTM preview, Meta Test Events, Tag Assistant, the pre-launch checklist, plus the companion git repo with working Next.js templates for every component.

## Files

- `playbook.md` — full playbook source in Markdown
- `playbook.pdf` — rendered PDF for download / sharing
- `copy.json` — title, hook, benefits, schema for re-publishing
- `image-prompts.json` — Gemini prompts for the brand 4 images (cover, hero, og, notion-cover)


## Read or Download

- Live page: [files.aibrandfactory.com/playbooks/professional-tracking-stack](https://files.aibrandfactory.com/playbooks/professional-tracking-stack)
- Notion duplicatable template: [https://massiveimpact.notion.site/The-Compliant-Tracking-Stack-for-Professionals-34cfb27e6634811a9275e6550d3b2514](https://massiveimpact.notion.site/The-Compliant-Tracking-Stack-for-Professionals-34cfb27e6634811a9275e6550d3b2514)

## Use

Fork this repo, edit `playbook.md` for your own audience or customize the prompts in `image-prompts.json` to re-skin for your brand. Attribution required per LICENSE.

## License

Free to use with attribution. See [LICENSE](LICENSE) for details.

Built by [AI BrandFactory](https://www.aibrandfactory.com), tools and systems for AI-powered content businesses.
