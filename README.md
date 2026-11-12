# Dash Digital — Website Project Questionnaire

Client questionnaire for new website projects, hosted at **questionnaire.dashdigital.ca**.

## Files
- `index.html`: the whole page (layout, styles and form logic)
- `logo.png`: Dash Digital logo

## Submissions
Answers are sent by Web3Forms to the email registered with the access key in `index.html` (`WEB3FORMS_ACCESS_KEY`). Each one arrives as "New website questionnaire: [Business Name]". Replying goes to the client.

## Deploy on Cloudflare Pages
1. Cloudflare dashboard → Workers & Pages → Create → Pages → Connect to Git.
2. Pick this repository.
3. Build settings: Framework preset **None**, build command **empty**, output directory **/** (root).
4. Deploy.
5. In the project → Custom domains → add `questionnaire.dashdigital.ca`.
