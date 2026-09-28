# Module 3 — Multi-Factor Authentication (MFA)

## The one idea
MFA means a stolen password **isn't enough** to get in. It's the single
highest-impact thing most people can turn on today.

## The factors
- Something you **know** (password).
- Something you **have** (phone app, hardware key).
- Something you **are** (fingerprint, face).

## Strength, best to good-enough
1. **Hardware security key / passkey** (phishing-resistant) — best.
2. **Authenticator app** codes (TOTP) — strong, free, works offline.
3. **SMS codes** — better than nothing, but vulnerable to SIM-swap.

## Watch out for MFA fatigue
Attackers with a stolen password may spam you with push prompts hoping
you tap "approve" to make it stop. **Never approve a prompt you didn't
start.** A prompt you didn't trigger = someone has your password. Report it.

## Action
Turn on app-based MFA (or a passkey) for email, banking, and any work
account that offers it. Email first — it's the reset path for everything else.
