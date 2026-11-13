# QuotaGuard Showcase Media Guide

Follow this quick checklist to record clean, recruiter-ready visuals for your GitHub Showcase and LinkedIn post.

---

## 1. Recommended Screenshots (4–6 Images)

Save the screenshots inside this `screenshots/` folder using the exact filenames below so `README.md` displays them automatically (remember to replace the italic placeholder text in `README.md` with `![Label](./screenshots/filename.png)`):

1. `01_role_light.png` — Role Selection / Dashboard screen in **Light Mode** (`Daylight Paper Slate`).
2. `02_role_dark.png` — Same Dashboard screen in **Dark Mode** (`Neutral Carbon`).
3. `03_admin_group.png` — Admin Group Details showing member list, quota allocation, and chart.
4. `04_member_view.png` — Member Details / Live Enforcement status (`SLOWDOWN` or `KILL_SWITCH` active).
5. `05_qr_gate.png` — Encrypted QR Wi-Fi Gate dialog / onboarding screen.

---

## 2. 60–90 Second Demo Video Script (LinkedIn & GitHub)

Record a crisp screen-recording (720p/1080p MP4) demonstrating the **end-to-end engineering proof**:

1. **0:00 – 0:15 (Hook & UI):** Open QuotaGuard in Light Mode, switch smoothly to the Neutral Carbon Dark Mode, and open the Admin Group view.
2. **0:15 – 0:35 (Zero-Root Wi-Fi Gate):** Generate an encrypted QR gate payload and show how a member device joins the Wi-Fi network without ever seeing the password.
3. **0:35 – 0:60 (Real-Time Bandwidth Enforcement):** Set a strict throttle limit (`SLOWDOWN`) or `KILL_SWITCH` from the Admin phone -> show the instant FCM wakeup & VPN notification appearing on the Member phone -> show YouTube/browser actually slowing down or stopping immediately!
4. **0:60 – 0:75 (Home Router Isolation):** Disconnect from home Wi-Fi (or switch network) and show that enforcement suspends automatically (`Zero Outside Interference`).

> **Tip:** Once recorded, drag-and-drop the MP4 file directly into the GitHub `README.md` editor in your browser — GitHub automatically hosts MP4 videos and renders an inline native video player inside your README!
