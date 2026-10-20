# International Tax in Practice — Website starter

Static, responsive pre-launch landing site. No tracking, no functional enquiry form and no payments are enabled.

## Files
- `index.html` — main landing page
- `privacy.html` — **draft only**, must be completed/reviewed before being used publicly
- `styles.css` — responsive visual style
- `script.js` — mobile navigation and current-year footer
- `.nojekyll` — serves static files directly through GitHub Pages

## Deploy as separate site
1. Create a new GitHub repository named `international-tax-in-practice`.
2. Upload **the files inside this folder** into the repository root, not the parent folder.
3. In Settings → Pages, choose `Deploy from a branch`, `main`, `/(root)`, and save.
4. GitHub will assign an address such as `https://<your-username>.github.io/international-tax-in-practice/`. Confirm the actual URL in Settings → Pages.
5. Before advertising or accepting leads, replace the placeholders in `privacy.html`, review the notice, connect the real approved n8n **Production URL** to the site's CTAs, and publish and test the workflow. No production URL is assumed or invented here.
6. Optionally set up a dedicated purchased domain after launch.

## n8n integration
Use the existing `ITP-01 | Lead Capture & Classification` workflow. After final QA, replace the disabled 'Enquiry form coming soon' element with an anchor to its exact Production Form URL. Update the custom HTML privacy notice link within the n8n form to your actual published `/privacy.html` URL. Publish the n8n workflow only after final checks. Never expose n8n Test URLs in public links.

## Items to verify before go-live
- Responsible party's legal name and privacy contact
- Complete privacy notice, actual vendors, transfer safeguards, and retention schedule
- Browser-based success and error flow, verified consent/unsubscribe plan
- Concurrent duplicate protection or reconciliation
- Remove fictional test records and resolve inconsistent consent values
- Udemy enrollment URL and corporate pricing are deliberately omitted pending availability and approval
