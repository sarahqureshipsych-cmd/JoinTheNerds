# Join the Nerds - Membership Form

This is a single-page HTML application designed to act as a screening form for a private Telegram group. It collects applicant details, ensures they agree to the house rules, and generates a pre-formatted message for the user to copy and send via Telegram.

## Setup Instructions for Admin

Since this is a static HTML file, it requires no backend or database. All logic is handled in the browser.

To connect it to your specific Telegram account:

1. Open the `.html` file in any text editor.

2. Scroll to the very bottom to find the `<script>` section.

3. Locate the `TELEGRAM_URL` variable:

   ```
   var TELEGRAM_URL = "https://t.me/sarahqureshipsych";
   ```

4. Replace the URL with your own Telegram link (either a direct message link or a private group invite link).

5. Save the file and host it on any static web hosting provider (such as Netlify, Vercel, or GitHub Pages).

## Copyright and License

**© 2026 Sarah Qureshi. All Rights Reserved.**

This code and its associated design are proprietary. You are NOT permitted to copy, distribute, modify, publish, or use this code, in whole or in part, without explicit written permission from the copyright holder.