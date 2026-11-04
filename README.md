# Rob A Heating & Plumbing — rob a heating and plumbing engineer ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `robaheatingandplumbingengineerltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/robaheatingandplumbingengineerltd.mjs`).
> To change the content, edit that file and run `node build.mjs robaheatingandplumbingengineerltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@robaheatingandplumbingengineerltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($£[AMOUNT] / $£[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Rob A Heating and Plumbing Engineer Ltd is an England and Wales company working in heating and plumbing from High Wycombe. Most customers assume a heating engineer holds one credential that covers everything they might be asked to do. It does not work that way, and the gap is where people get hurt. Gas work is reserved: only a business registered with the gas safety register may work on gas fittings and appliances, and doing it without that registration is a criminal offence rather than a technicality. An unvented hot water cylinder is a different regime altogether, requiring a separate competence and counting as notifiable building work, and it matters because an unvented cylinder stores energy and can fail violently if its safety devices are wrong. Water fittings are a third regime again, with certain installations having to be notified to the water undertaker in advance and with backflow prevention existing to protect the public mains rather than your house. One registration tells you nothing about the other two. So ask which of the three a job actually touches, ask to see what covers it, and check the number on the public register rather than taking anybody's word, including ours. Site: robaheatingandplumbingengineerltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
