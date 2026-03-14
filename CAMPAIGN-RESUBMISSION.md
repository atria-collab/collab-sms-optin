# Twilio A2P Campaign Resubmission — Collab Home

## Campaign Details

- **Brand SID:** BN7dcdd809a0ed393c8521c5f95312b878
- **Messaging Service:** MG6a85920ab3237b257bb69d1116a4f4a9 (Collab Home Messaging)
- **Use Case:** MIXED (property management communications)
- **Opt-In Page:** https://atria-collab.github.io/collab-sms-optin/

## Updated Fields (fixes for Error 30909 — CTA verification)

### Description
Property management communications for Collab Home tenants and contacts, including maintenance updates, leasing inquiries, rent reminders, and operational coordination.

### Message Flow (CTA — the key fix)
Tenants opt in to SMS by: (1) completing the online consent form at https://atria-collab.github.io/collab-sms-optin/, (2) providing their phone number and checking the SMS consent checkbox during lease signing, or (3) submitting a leasing inquiry on https://rentals.collabhome.io. All opt-in methods include clear disclosure that recurring SMS messages will be sent, message frequency varies, Msg&Data rates may apply, and reply STOP to opt out.

### Message Samples
1. "Hi [Name], this is Collab Home. Your maintenance request #1234 has been received. A team member will follow up within 24 hours. Reply STOP to unsubscribe."
2. "Reminder: Your rent payment of $X is due on the 1st. Please contact us at support@collabhome.io if you have any questions. Reply STOP to opt out."

### Opt-In Message
"You have opted in to receive SMS messages from Collab Home property management. Msg frequency varies. Msg&Data rates may apply. Reply HELP for help, STOP to cancel."

### Opt-Out Message
"You have been unsubscribed from Collab Home SMS. You will not receive any more messages from this number. Reply START to resubscribe."

### Help Message
"Collab Home SMS Help: Contact us at support@collabhome.io or call +1 (510) 900-0298. Reply STOP to unsubscribe. Msg&Data rates may apply."

### Keywords
- Opt-in: START, SUBSCRIBE, YES
- Opt-out: STOP, STOPALL, CANCEL, END, QUIT, UNSUBSCRIBE
- Help: HELP, INFO

### Embedded Links: false
### Embedded Phone: false
