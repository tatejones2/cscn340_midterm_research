# CSCN 340 — MID-TERM Research Progress Presentation

**Topic:** Passwordless Authentication and Passkey Adoption Barriers in Enterprise Environments  
**Deliverable:** Mid-Term Project Review (recorded video, **5–10 minutes**)  
**Suggested format:** 7 content slides + 1 references slide  
**Target speaking time:** About 7–8 minutes  
**Date prepared:** October 11, 2026

> **Accuracy note:** The three scholarly publications below are verified and their findings are summarized from their published abstracts and available text. Identifying or summarizing a study is not equivalent to having completed a full literature review. Before recording, read at least each article's abstract, introduction, and conclusion. Describe progress based on what you have actually done; do not claim to have completed research you have not completed.

## What this midterm must include

Per the course assignment handout, the video should include an introduction, review of the selected topic and any change in direction, an honest status of the technology research/literature review, a timeline to the final paper and presentation, and a conclusion. The professor expects technology research to be completed by midterm and the literature review underway. The **final paper** must later address a technology literature review, **at least two ethical issues and two professional responsibilities using the ACM Code of Ethics**, and a Christian worldview discussion.

**Keep this distinct from the final in-class presentation:** The final in-class presentation has a different stated length (4–5 minutes). This guide is for the **midterm video** only.

---

## Slide 1 — Title & Introduction (≈ 40–50 seconds)

### On-screen text
- **Passwordless Authentication and Passkey Adoption Barriers in Enterprise Environments**
- CSCN 340 — Mid-Term Research Progress Review
- Your name · October 2026

### Speaker notes
“Hello, today I'm giving a progress update on my CSCN 340 research topic: passwordless authentication and passkey adoption barriers in enterprise environments. Passwords create risks such as phishing, credential theft, and password reuse. Passkeys are designed to reduce many of these risks, but rolling them out across an organization is more complicated than enabling a login feature. My research focuses on what prevents organizations from moving to passkeys and how those obstacles might be addressed.”

### Visual suggestion
Simple title design with a small key/shield icon. Avoid large paragraphs.

---

## Slide 2 — Technology Background (≈ 55–65 seconds)

### On-screen text
**How passkeys work**
- FIDO2 / WebAuthn authentication
- Public-private cryptographic key pair
- Private key remains under authenticator control
- User verification with device PIN or biometrics
- Phishing resistance through origin-bound authentication

**Core distinction:** Password = shared secret; passkey = cryptographic proof.

### Speaker notes
“Traditional password systems authenticate users with a secret they know and can accidentally reveal. Passkeys use public-key cryptography: a service stores the public key, while an authenticator protects the private key. During sign-in the authenticator signs a challenge, and the service verifies the response. The user may unlock their authenticator with a fingerprint, facial recognition, or PIN. Importantly, the biometric itself is not a password sent to the website. WebAuthn also ties authentication to the legitimate website or application, which is why passkeys can resist many phishing attacks. However, a strong authentication method does not automatically solve enrollment, recovery, and support problems.”

### Visual suggestion
Two-column diagram: **Password → shared secret** versus **Passkey → public key + protected private key**.

### Research basis
Technical overview consistent with the studies below; for full technical details review official FIDO Alliance/WebAuthn and NIST guidance before final paper.

---

## Slide 3 — Topic Scope and Research Question (≈ 50–60 seconds)

### On-screen text
**Topic status:** Original topic retained; no change proposed

**Research question:**
> What technical, organizational, and user-related barriers prevent enterprises from widely adopting passkey-based authentication?

**Focus areas**
- Employee/workforce sign-in
- Identity management and legacy apps
- Account recovery and device replacement
- Rollout, training, and policy

### Speaker notes
“I plan to keep my approved topic, but I am narrowing the emphasis to employee and workforce authentication rather than consumer login experiences. Enterprise environments have unique issues involving company-managed devices, identity providers, legacy applications, remote workers, and account recovery. My central question is which technical, organizational, and user-related barriers matter most and what organizations can do to reduce them. That scope should help keep the literature review focused.”

### Visual suggestion
Large research question with three small labels: Technical / Organizational / User.

---

## Slide 4 — Initial Scholarly Research (≈ 90 seconds)

### On-screen text
**Three starting scholarly publications**

1. **Kepkowski et al. (2023), IEEE SecDev** — 118 professionals; account recovery selected as a challenge by **over 60%** of respondents.
2. **Lassak et al. (2024), USENIX Security** — 28 interviews; barriers included recovery, friction, technical issues, regulation, and security culture.
3. **Matzen et al. (2025), Applied Sciences** — literature review; user perception, recovery, sharing, and delegation are recurring challenges.

**Emerging synthesis:** Deployment success depends on more than cryptographic security.

### Speaker notes
“Three scholarly sources provide a useful starting point for this research. First, Kepkowski and colleagues' 2023 IEEE study gathered perspectives from 118 professionals with enterprise FIDO2 experience. Account recovery stood out: more than 60 percent selected it as a challenge, with remote workforce and legacy system scenarios also relevant. Second, Lassak and colleagues interviewed 28 security and authentication professionals for a 2024 USENIX Security paper. They identified barriers including account recovery, technical issues, regulatory requirements, friction, and organizational security culture. Third, Matzen and colleagues published a 2025 literature review emphasizing user-centered barriers, particularly understanding, recovery, credential sharing, and delegation. Taken together, these studies suggest that successful enterprise adoption requires operational processes and user support—not just strong cryptography.”

### Visual suggestion
Three clean research cards, one per study. Add small bottom citations: (Kepkowski et al., 2023), (Lassak et al., 2024), (Matzen et al., 2025).

### Verify before delivery
Read each paper's abstract and conclusion. The statistics above come from the published source descriptions; **do not present them as personally collected survey results**.

---

## Slide 5 — Findings, Gaps, and Current Status (≈ 60–70 seconds)

### On-screen text
**Preliminary themes**
- Recovery after lost/replaced devices
- Compatibility with legacy infrastructure
- User education and help-desk support
- Security policies and organizational buy-in

**Project status (adjust to truth before recording)**
- Topic and question: **Defined**
- Scholarly articles: **3 identified for initial review**
- Full technical research: **Not complete**
- Written literature review: **Not complete**
- Ethics / Christian worldview: **Planned**

### Speaker notes
“The strongest preliminary pattern is that account recovery appears repeatedly across the research. Enterprise compatibility and organizational readiness are also important. An organization cannot simply assume that employees will understand passkeys or that every application and device will support them. In terms of my progress, I have established a research question and assembled three scholarly starting sources. I still need to complete a deeper technical analysis, compare more studies, and turn the evidence into a structured written literature review. I'll also need to examine the ethical and Christian worldview dimensions required for the final paper.”

### Visual suggestion
A small 'themes' panel alongside an honest milestone checklist. If you have not yet read an article, keep the phrase **identified for initial review** rather than **reviewed**.

---

## Slide 6 — Plan and Timeline (≈ 80–95 seconds)

### On-screen text
| Period* | Work | Output |
|---|---|---|
| Week 1 | Read three studies; study FIDO2/WebAuthn | Source notes + technical outline |
| Week 2 | Add 3–5 scholarly/standards sources; compare barriers | Literature review draft |
| Week 3 | ACM ethics + Christian worldview; integrate research | Full paper draft |
| Week 4 | Revise citations/paper; rehearse final presentation | Paper + presentation ready |

\*Relative schedule; replace with actual course deadlines once confirmed.

**Research goal:** 6–10 credible sources, with scholarly studies and authoritative technical standards clearly distinguished.

### Speaker notes
“My plan has four stages. First, I will read and annotate the three identified studies while building a technical explanation of FIDO2, WebAuthn, and enterprise authentication. Second, I will add more peer-reviewed research and relevant standards, then organize the literature by recurring barriers such as recovery, integration, costs, and usability. Third, I will draft the paper's ethical analysis using the ACM Code of Ethics and develop the required Christian worldview discussion. Finally, I will revise the paper, verify all citations, and prepare the shorter final in-class presentation. These are target stages rather than confirmed course deadlines, so I'll align them with the syllabus.”

### Visual suggestion
Four-step horizontal timeline, with a small note: **Adjust to instructor due dates**.

---

## Slide 7 — Conclusion (≈ 40–50 seconds)

### On-screen text
**Main takeaway:** Passkey security is promising, but enterprise adoption depends on secure recovery, integration, and usable deployment.

**Next steps:**
- Expand literature review
- Compare implementation challenges
- Connect technology to ethics and Christian worldview

### Speaker notes
“To conclude, passkeys offer promising security improvements over passwords, but the initial scholarly research points to barriers that go beyond the authentication protocol itself. Account recovery, enterprise integration, and employee adoption are all important areas to examine. My next steps are to finish the technical research, expand and write the literature review, and connect the findings to professional ethics and a Christian worldview. The final objective is to explain not just why passkeys are useful, but what would make enterprise adoption practical and responsible. Thank you.”

---

## Slide 8 — References (leave on screen briefly; no extended narration needed)

**APA-style references**

Kepkowski, M., Machulak, M., Wood, I., & Kaafar, D. (2023). Challenges with passwordless FIDO2 in an enterprise setting: A usability study. *2023 IEEE Secure Development Conference (SecDev).* https://doi.org/10.1109/SecDev56634.2023.00017

Lassak, L., Pan, E., Ur, B., & Golla, M. (2024). Why aren't we using passkeys? Obstacles companies face deploying FIDO2 passwordless authentication. *33rd USENIX Security Symposium*, 7231–7248. https://www.usenix.org/conference/usenixsecurity24/presentation/lassak

Matzen, A., Rüffer, A., Byllemos, M., Heine, O., Papaioannou, M., Choudhary, G., & Dragoni, N. (2025). Challenges and potential improvements for passkey adoption—A literature review with a user-centric perspective. *Applied Sciences, 15*(8), Article 4414. https://doi.org/10.3390/app15084414

### Direct reading links

- Kepkowski et al. (IEEE): https://ieeexplore.ieee.org/document/10305624/
- Kepkowski et al. (accessible preprint): https://arxiv.org/abs/2308.08096
- Lassak et al. (USENIX, open-access PDF linked): https://www.usenix.org/conference/usenixsecurity24/presentation/lassak
- Matzen et al. (open access): https://www.mdpi.com/2076-3417/15/8/4414

---

## Additional research to complete for the FINAL paper

The following is **future work**, not something to claim as completed in the midterm:

### Technical literature review
- Distinguish FIDO2, WebAuthn, and CTAP.
- Understand device-bound versus synced passkeys and their management tradeoffs.
- Study how SSO/identity providers and legacy applications affect deployment.
- Evaluate lost device, employee termination, account recovery, and fallback authentication scenarios.
- Compare study methods and limitations rather than merely listing article conclusions.

### Ethics: ACM Code of Ethics
Develop at least **two ethical issues** and **two professional responsibilities**, as required by the assignment. Candidate angles to research include:
- Privacy and employee data protection
- Equal access, usability, and accessibility of authentication
- Preventing harm from insecure fallback and recovery processes
- Professional diligence in risk assessment, testing, and secure system design

Official code: https://www.acm.org/code-of-ethics

### Christian worldview
Develop a thoughtful, supported connection to stewardship of entrusted information, honesty/integrity, and responsibility for protecting others. Possible Bible passages to **read in context** include Luke 16:10, Proverbs 11:3, and Philippians 2:4. Avoid suggesting a Bible passage specifically endorses any authentication technology.

---

## Production checklist

- [ ] Open and read the abstracts/introduction/conclusion of the three studies.
- [ ] Update Slide 5 status to match what you actually completed.
- [ ] Replace relative week labels with actual due dates from your course calendar if known.
- [ ] Create 8 slides (7 content + 1 references); use short bullets, not script paragraphs.
- [ ] Put speaker notes in PowerPoint/Google Slides or a separate reading copy.
- [ ] Cite studies in small text on Slides 4–5; include full references on Slide 8.
- [ ] Practice once; the spoken sections should total around 7–8 minutes.
- [ ] Record the 5–10-minute midterm video and check audio/video before submission.

**Suggested file name for the actual slide deck:** `CSCN340_Mid-Term_Research_Progress_Presentation.pptx`
