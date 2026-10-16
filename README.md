# Premium Detailing Belgium — STATIC WEBSITE (no Python / no paid services)

## Publish on GitHub Pages
Upload **index.html** and the **assets** folder to the root of your GitHub Pages repository. Enable GitHub Pages from the main branch root.

## Customer enquiries
The booking and contact forms prepare a message in the visitor’s email app (mailto), with an optional WhatsApp link. The visitor MUST press Send in their email/WhatsApp app. Telephone links dial the number. There is NO automatic email delivery, database, SMS service or paid backend. If no email app is configured, customers can use WhatsApp or the phone link.

## Admin editor — IMPORTANT LIMITATION
Open the website and choose Admin in the footer. The editor is a **browser-local preview editor**. It can change all the page text, prices, photos, language strings, settings and more in that browser. **These edits do NOT update the live website for other visitors** until you export the content and publish it. There is NO secure admin authentication on this static website. Do not use this as a password-protected online CMS.

To publish content changes for everyone: in Admin choose Backup & Export -> Download Full Backup (website-content.json). Replace the JSON content of `assets/defaults.js` (after `window.PD_DEFAULTS=` and before final `;`) with the exported JSON, then upload that changed file to GitHub. You may also edit `assets/defaults.js` directly.

Image uploads in this editor use browser storage and are limited to 700 KB per image; hosted image URLs are recommended. Browser storage has limits. For persistent cross-device online admin editing, an actual hosted backend/database or CMS would be required later.

## Temporary information
Business name, example prices, Brussels location and hours are placeholders. Contact email is funsfab@gmail.com, phone 06 21 14 47 67. Replace placeholders before final publication.
