# Hospitality Lawsuit Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) landing page for the **California adult sexual abuse claims for hospitality industry employees** sponsored by **Andrews & Higgins**, built on the framework of your uploaded Taco Bell page (`index-7.html` / `style-7.css` — your published, edited version) and filled with content from **hospitalitylawsuit.com**. Because this is the same law firm as the Taco Bell project, branding and firm information were kept the same, per your instruction; only the subject content changed.

## Kept from your framework, unchanged

- Page structure, classes, the MTAA CIPA block script, and your current Meta Pixel (`1459701774055745`).
- Your current form embed: `forms.mtaa.ai/f/nf_14bb49f057af4602b5676b8892df3c32`, in the overflow form card — the container hangs past the hero over the section below it, the frame scrolls internally with `overflow: auto` if the embed runs tall, and your mobile values are preserved.
- Your design additions from the framework: the `.basic-imaga` photo style, the two parallax variants (`.section-parallax` on the hero, `.section-parallax-info1` on the middle section), the two-column image layout in the middle section, and the two-column attorney area.
- Firm assets, exactly as in your framework (same firm): the Andrews & Higgins logo image (hero and footer, consumerclaimnow.com), Anne Andrews' and Sean Higgins' photos with their titles (Managing Partner / Partner), the 4701 Von Karman Ave, Newport Beach, CA 92660 address, the attorney-advertising sponsorship line, the "No representation is made that the quality of the legal services…" + co-counsel disclaimer text, © 2026 Andrews & Higgins, and the call/text consent paragraph.
- Footer legal links still point to your `privacy-policy.html` and `disclaimer.html` on justicehelpnow.com, as in the framework.

## Phone number — this sample has one

Unlike the Taco Bell page (which displays no phone), hospitalitylawsuit.com prominently displays **(855) 719-3161** with "Call Us For Immediate Assistance," so the number is included in the attorney block and the footer contact block. The framework has no header phone slot, so it does not appear in a header.

## Parallax and subject images — placeholders, as instructed

- Both parallax blocks keep your code, with the overlay tint recolored to this site's dark navy (`--overlay-rgb: 8, 25, 52`, opacity 0.75). Their image lines are placeholders again — `YOUR-IMAGE-URL-HERE` (hero) and `YOUR-IMAGE-URL-HERE-2` (middle section) in `css/style.css` — because the framework's URLs are Taco Bell subject photos (your published Taco Bell hero image and the tacos photo). Send the hospitality image URLs and they drop into those lines.
- The middle section's side photo (your salad-image slot) is likewise a marked placeholder: `images/REPLACE-WORKPLACE-IMAGE.jpg`. Drop a hospitality workplace photo into an `images/` folder with that name, or swap in a hosted URL.
- The attorney photos and logo are firm assets rather than subject images, so they stay live, as noted above.

## Colors and typeface

`css/style.css` is your uploaded `style-7.css` with **color values only** changed (diff-verified), plus the two parallax placeholder URL lines. Palette sampled from the rendered hospitalitylawsuit.com on 2026-11-04:

- Very dark navy `#0a1c3a` (their footer) for the top bar, dark section, and footer; royal blue `#1c417b` through the hero gradient to hero navy `#081934`
- Royal blue `#2458a7` for kickers, headline accents, and checkmark circles (white checks)
- Logo gold `#f7d101` for highlights on dark backgrounds (hero eyebrow text under the logo, dark-section kicker, footer phone)
- Bright green `#22a717` CTA buttons with white text — this needed no change: your framework's CTA is already the sample's exact green (hover `#1e9413`)
- Light gray `#d6d8dd` (their form-panel tone) for the claims band and border lines
- Typeface: no change needed either — the sample's headlines and body are the same heavy Arial/Helvetica-like sans as the Taco Bell site, and your framework already runs Inter with Arial/Helvetica fallbacks everywhere. The sample also uses a vivid red accent (`#ff0000`, e.g. the first words of its headline); the framework has no equivalent element, so red was not mapped. Colors are close visual approximations sampled from the rendered page.

## Content (from hospitalitylawsuit.com)

Handled in the sample's own compassionate, confidentiality-first framing:

- Hero: their headline — "Hospitality Industry Employees May Be Eligible for Financial Compensation," under "California Adult Sexual Abuse Claims" — with their lines on holding predators accountable, still being able to take legal action, and information always remaining 100% confidential.
- We Understand How Difficult It Can Be — coming forward is never easy; survivors delay reporting out of fear of retaliation, losing their job, not being believed, embarrassment, or wanting to move forward; you are not alone; speaking with an attorney does not obligate you to file.
- A Workplace That Should Have Been Safe — restaurants, bars, hotels, catering companies, event venues, and other hospitality workplaces; late-night shifts, isolated work areas, alcohol service, and power imbalances; employers who fail to maintain a safe workplace; holding abusers and the businesses that protect them accountable.
- Environments That Can Enable Abuse — nine cards built from the sample's factors (shifts, isolation, alcohol service, power imbalances, unsafe workplaces, cover-ups, retaliation fears, not being believed, adult survivors).
- California Law May Still Allow Your Claim — adult survivors can file previously time-barred claims if a business or its representatives covered up, or attempted to cover up, prior sexual assault allegations against the perpetrator; free consultations for survivors of abuse.
- What We Look At — their form's details: the workplace, what happened (sexual abuse, assault, or repeated workplace sexual misconduct as an adult), when it happened (less than 1 year ago, 1–2, 3–4, or over 4 years ago), and what the business knew or covered up. The sample's note that completing the evaluation does not guarantee compensation, and that qualifying criteria may change, is included at the end of the workplaces section.

## Files

```
github-hospitality-lawsuit-landing-page/
├── index.html
├── css/style.css   (your framework CSS, colors only changed + parallax placeholders)
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root).
