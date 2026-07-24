# 💎 Partner Support Triage Console

**L2 Ops Support simulation for incentive programs** — built for Aquent Ops Support Specialist role.

**Built by Dev Fred B** | 07/24/2026 ET

### Live Demos
- Netlify: https://partner-support-triage-console.netlify.app/
- GitHub Pages: https://westindies86-dev.github.io/partner-support-triage-console/

### How To Use (Step-by-Step)

1. Pick a Ticket (Left Inbox)
   - Click TK-1024, TK-1025, TK-1026, or TK-1027
   - Center panel shows details + message

2. Check The Rules (Center - SAMPLE_RULES.json)
   - This is editable! Click inside and change JSON
   - Try changing min_premium_for_bonus to $5000
   - Header shows start → end · min $X

3. Run Diagnostic Checks (Right Panel)
   - Check Eligibility: 6 real PASS/FAIL checks
   - Check Payment: File ID PAY-8821-1024
   - Check Fulfillment: Vendor WH2 status
   - Check Data Sync: EDI job 9912 debug

4. Work The Ticket Like L2 Support
   - Type internal note → Add Note (ET-stamped) or Save Draft
   - Check IT/Data/Vendor → Escalate
   - Click Resolve → ticket closes
   - Everything logs to bottom Audit Trail with ET timestamps

5. Test Features
   - Change agent name top-right (Dev Fred B)
   - Edit rules to make tickets fail, then re-check
   - Refresh page — notes persist (localStorage)

6. Audit Trail (Bottom)
   - Every action logged: ET time, ticket ID, action, agent

### What Makes It Premium
- Live Eastern clock (America/New_York)
- ET timestamps: MM/DD/YYYY, h:mm:ss PM ET
- SLA 4h, queue counter, toasts, Geist fonts
- Single file — no build needed

Built for Aquent Ops Support Specialist.
Local simulation — no real emails sent.

© 2026 Dev Fred B