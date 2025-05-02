*2025-05-02* | **Day 15 — False Positives & New Gates**

> [!info]+ Quick Recap  
> Missed logging Day 14 due to heavy rain and other priorities — back on track now.

# 🧠 Field Log  
Spent most of the day digging into a private program. Explored a few endpoints, especially one promising-looking functionality. For a moment, I thought I landed something real — but turned out to be a **false positive**. Classic bait.

Good news: Got **2 more private program invites** — will scope them out tomorrow and see what’s cooking.

---

## 📚 Knowledge Stack (Writeups Read Today)

- 🖼️ **Stored XSS via PNG Upload**  
  Crafty little vector hiding inside an image upload — classic case of mishandled content type.  
  → [HackerOne Report #880099](https://hackerone.com/reports/880099)

- 🌐 **Blind SSRF in `address` field (Request Body)**  
  Shows how buried parameters can open a gateway into internal networks.  
  → [HackerOne Report #1086206](https://hackerone.com/reports/1086206)

- 📸 **Blind SSRF through Image Upload (SVG Abuse)**  
  Neat trick — endpoint accepts image uploads and renders them raw. Swapped to SVG for SSRF payload.  
  → [Infosec Writeups](https://infosecwriteups.com/my-first-bug-blind-ssrf-through-profile-picture-upload-72f00fd27bc6)

---

Getting sharper again — slow and steady  
**Sign-off: Storms cleared, focus returned.**
