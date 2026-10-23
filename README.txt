WESHARE ENHANCED PROTOTYPE
=========================
Open this folder in VS Code and use Live Server on index.html.

Included in this browser-only prototype:
- Login gate asking name, phone number and preferred language on opening
- Language selector: English, Tamil, Hindi, Telugu, Kannada, Malayalam, Bengali, Spanish and French (core navigation labels translated; not every sentence is translated)
- Browse/search/filter items
- Publish an item
- Create borrowing requests with pickup/return dates
- Demo owner accept/decline controls; contact details appear after accept
- WhatsApp contact link (uses the demo owner's entered phone; verify details first)
- Voice-to-text in supported browsers/languages and read-reply aloud
- Rule-based demo helper (NOT a connected AI model)
- Community help posts
- Browser localStorage persistence

IMPORTANT LIMITATIONS:
This is a frontend prototype, not a production app. Name/phone are not verified; there is no OTP, secure authentication, cloud database, real notifications, real multi-user sync, live chat, or actual AI API. Data is stored only in this browser/device and can be edited by someone with access to it. Demo accept/decline buttons simulate an owner response on the same device. For real private accounts and real user-to-user contact, a backend/authentication/database service is required.
Voice recognition availability varies by browser, device and language; some browsers use an online speech service. Give microphone permission only if comfortable.
