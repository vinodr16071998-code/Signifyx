SIGNIFYX WEBSITE — QUICK SETUP

Files:
- index.html: complete responsive one-page website.

Before publishing:
1. Open index.html in a text editor.
2. Near the bottom, find: const CONFIG = { ... }
3. Replace:
   - whatsappNumber: "91XXXXXXXXXX" with your WhatsApp number, digits only.
   - businessEmail with your email.
   - phoneDisplay with your phone number as you want it shown.
   - serviceArea with the city/areas you serve.
   - businessHours with your business hours.
4. Save and open index.html in a browser to preview.

Enquiry form:
- The form opens WhatsApp with the customer's details pre-filled.
- It does not store enquiries on a server.
- The WhatsApp number must be configured before the form can send enquiries.

Free publishing option — GitHub Pages:
1. Create/sign in to a GitHub account.
2. Create a public repository named signifyx-website.
3. Upload index.html to the repository root.
4. Open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select main and /(root), then Save.
7. GitHub will provide the public website address after deployment.

A custom domain (for example, signifyx.in) is optional and usually costs extra.
