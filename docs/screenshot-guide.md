# Screenshot and Image Guide

The uploaded documents contain useful visuals, but many should not be published directly. Prefer self-created diagrams and sanitized tables over raw assignment screenshots.

## Recommended Image Locations

| Image File | Folder | Use In | What To Show |
|---|---|---|---|
| `01-policy-governance-map.png` | `assets/screenshots/` | `README.md`, `docs/executive-summary.md` | A clean map showing incident, privacy, compliance, and legal-accountability themes. |
| `02-incident-reporting-flow.png` | `assets/screenshots/` | `docs/incident-governance.md` | A sanitized flow from incident detection to legal review and reporting decision. |
| `03-cisa-sec-comparison.png` | `assets/screenshots/` | `docs/incident-governance.md` | A cropped comparison table with no cover-page or student details. |
| `04-ftc-cfaa-comparison.png` | `assets/screenshots/` | `docs/legal-framework-map.md` | A sanitized FTC vs CFAA comparison table. |
| `05-privacy-by-design.png` | `assets/screenshots/` | `docs/privacy-and-ethics.md` | A self-created privacy-by-design lifecycle diagram. |
| `06-iot-risk-map.png` | `assets/screenshots/` | `docs/iot-privacy-security.md` | A self-created IoT data/security risk map. |

## Images From Uploaded Documents: Safe or Not?

| Source Image Type | Publish? | Reason |
|---|---|---|
| Assignment cover pages | No | They show university/course metadata and personal academic identifiers. |
| Full assignment pages | No | They look like homework uploads and may include personal/course details. |
| CISA vs SEC comparison table | Maybe, after crop | Only safe if the crop removes page borders, course context, and identifying information. |
| FTC vs CFAA comparison table | Maybe, after crop | Use only as a clean cropped table or recreate it in Markdown. |
| Ethics/privacy page screenshots | Not raw | Better to summarize into a case-study table. |
| References pages | No | They do not add portfolio value and can expose raw academic formatting. |

## Best Practice

For this repo, the strongest images are self-created diagrams. I added SVG diagrams under `assets/diagrams/`, which are safer and more professional than raw screenshots.

## Markdown Examples

From a file inside `docs/`:

```md
![Incident reporting flow](../assets/diagrams/incident-reporting-flow.svg)
```

From the root README:

```md
![Cyber policy governance map](assets/diagrams/policy-governance-map.svg)
```

## Redaction Checklist Before Uploading Any Image

- Remove student identifiers, email, phone, course details, and professor names.
- Remove university cover pages and logos unless you have a clear reason and permission.
- Remove raw assignment formatting that makes the repo look like a homework dump.
- Remove personal data, addresses, or sensitive details.
- Crop tightly so only the concept or table being explained remains.
- Prefer recreated diagrams over raw screenshots.
