# CyberProof training demo

A static lesson about phishing and QR-code trust. Open `index.html` to walk through a staged fake-login reveal, then a QR-code twist.

The page is a teaching screen only:

- It does not submit the form.
- It does not call `fetch`, XHR, or beacons.
- It does not use `localStorage`, `sessionStorage`, or cookies.
- It does not navigate to external websites.
- It does not collect or store real credentials.

The original uploaded sign-in file is not included. An unchanged Google-style credential form could be misused as a phishing page, so this bundle keeps the lesson and blocks submission and storage.

## Files

- `index.html` — the training demo
- `full_chat_and_structure.txt` — lesson structure from the design chat
- `uploaded_index_summary.txt` — summary of the original uploaded file
