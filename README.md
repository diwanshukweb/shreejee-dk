# Shreejee Banquet rebuild

An independent static rebuild of the supplied Emergent preview, using its observed public images and content. The source is in `dist/index.html`, `dist/style.css`, and `dist/app.js`; edit these files directly. No installation or build is needed.

Run `python3 -m http.server 4173 --directory dist` from this directory for local preview.

Includes responsive navigation, event selection, venue setup tabs, gallery filters and keyboard-accessible lightbox, FAQs, phone/map links, and a validated five-step enquiry form. Enquiries open a prefilled WhatsApp message for the visitor to send. Drafts are held only in the current browser tab's session storage. No server database, availability service, or Emergent backend has been migrated. Images are the placeholder stock photos shown in the reference; replace with business photos when available. Business claims and review excerpts retain the reference's confirmation note.

Live concept: https://shreejee-dk.netlify.app

Independent concept work, not commissioned by the business.
