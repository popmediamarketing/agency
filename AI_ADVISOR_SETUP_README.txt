Chamuel & Co. AI Jewelry Advisor Integration Notes

What was added:
- engagement-ring-advisor.html
- Multi-step customer intake form
- Rule-based AI-style recommendation on the website
- Recommendation output:
  1. Suitable Setting
  2. Suitable Diamond
  3. Suitable Material
  4. Suitable Width
  5. Suitable Warranty
  6. Suitable After Sales
  7. Suitable Budget Allocation
  8. Timeline Advice
- WhatsApp result sharing
- Google Sheet backend template

Important:
The website is ready to send leads to Google Sheet, but the Google Apps Script Web App URL must be pasted into assets/site.js:
const CHAMUEL_LEAD_WEB_APP_URL = "";

After you deploy the Apps Script, paste the Web App URL between the quotes.

Current customer journey:
Customer clicks Engagement Ring Advisor → fills story/name/phone/questions → AI recommendation appears → customer sends to WhatsApp or backend saves to Google Sheet once connected.

Recommended next expansion:
- Build similar advisor pages for Wedding Bands, Custom Jewelry and Diamond Type.
