# Project Strategy: Digital Lighthouse (Code Name)

> **Vision**: A resilient, low-bandwidth gateway to education for Afghan women, functioning as a "digital emergency kit" for knowledge.

## 1. Product Perspective (The "What" & "Who")

### Core Identity & Naming
*   **Recommendation**: **"Daricha" (The Window / دریچه)**.
    *   *Slogan*: "Lighting a candle where the electricity is cut."
*   **The Scope (The "Strategic Focus")**:
    *   **Primary Audience**: Girls in Afghanistan (and Iran) who are legislatively banned from education.
    *   **The Content Boundary**:
        *   ✅ **IN**: STEM, Languages, Digital Literacy, Mental Health, Safety.
        *   ❌ **OUT**: General political debates, Domestic (Chinese) gender issues, "Internet Warfare".
    *   *Why this boundary?*
        *   **Impact**: You solve a desperate, specific life-or-death need (Education), rather        than adding noise to general debates.
        *   **Safety**: International humanitarian aid is safe; Domestic ideological activism is risky.
*   **The "Product"**: Not just a website, but a **Progressive Web App (PWA)**.
    *   It must feel like a native app that can be "installed" on a phone home screen directly from the browser.
    *   **Killer Feature**: **Offline Mode**. Once opened, the core "Survival Guide" content should be cached and readable without internet.

### Language Strategy (Internationalization)
*   **UI/Navigation**: **Must be Trilingual (Dari, Pashto, English)**.
    *   *Why*: English is for the diaspora/helpers to find it. Dari/Pashto is for the end-user.
    *   *Implementation*: Right-to-Left (RTL) support is critical.
*   **Content**:
    *   Tier 1 (Core Guides): Human-translated (verified).
    *   Tier 2 (External Links): Labelled clearly in local languages (e.g., "Khan Academy (English with subtitles)").

## 2. Technical Perspective (The "How")

### Accessibility & Performance
*   **The "10KB Rule"**: The critical rendering path must be under 10KB. Remove all heavy JavaScript libraries (React is likely overkill; use Astro or Hugo).
*   **Anti-Censorship Architecture**:
    *   **Host**: GitHub Pages / Netlify (Free, hard to block completely without blocking all of GitHub).
    *   **Mirroring**: Provide a "Download HTML" button so users can share the file via Bluetooth or SHAREit app (very popular in Afghanistan).

### Security
*   **No User Data**: No login, no cookies, no analytics that track IP.
*   **Panic Button**: A quick "Exit" button that redirects to Google.com immediately.

## 3. Operations/Growth Perspective (The "Reach")

### "Dark Social" Distribution Strategy
*   **Don't target the users directly.** It is hard to reach them via public SEO due to censorship and language barriers.
*   **The "Bridge" Strategy**: Target the **Diaspora** (Afghans in UK, US, Germany, Iran).
    *   They are the ones looking for "How to help my cousin in Kabul".
    *   They are the ones sending the link via WhatsApp/Telegram to their family.
*   **WhatsApp Packet**: Create a "Viral Forwarding Message" — a simple text message with the link and a brief description in Dari/Pashto that asks people to forward it to sisters/daughters.

### Public Social Media Strategy
*   **Twitter (X)**: *The Primary Battlefield*.
    *   **Target**: International NGOs, Journalists, Afghan Diaspora activists.
    *   **Content**: English for awareness, Dari/Pashto for utility. Use hashtags like #LetAfghanGirlsLearn #EducationIsARight.
    *   **Safety**: High (if using dedicated anonymous account).
*   **Xiaohongshu (Little Red Book)**: *The Storytelling Platform*.
    *   **Target**: Chinese community, volunteers, potential donors (if needed later).
    *   **Strategy**: "Soft" storytelling. Share the *process* of building the site, the *stories* of the girls (anonymously). Focus on "Girls Helping Girls".
    *   **Caution**: **Do not discuss politics**. Focus strictly on the humanitarian/educational aspect to ensure account safety.
    *   **Identity**: Use a dedicated project account, NOT your personal account.

### SEO Strategy
*   Target "Helper" Keywords in English: "Online education opportunities for Afghan girls", "Scholarships for Afghan women".
*   Target "Resource" Keywords in Dari/Pashto: "Free school books PDF", "Learning English at home".
