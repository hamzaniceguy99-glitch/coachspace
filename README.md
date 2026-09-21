# CoachSpace — coaching for coaches

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `coachspace.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/coachspace.mjs`).
> To change the content, edit that file and run `node build.mjs coachspace` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@coachspace.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($49 / $139 / $279) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Coaching for independent coaches building a practice, delivered online: one-on-one video sessions and small group workshops covering choosing a niche and defining an offer, finding the first paying clients, structuring and running client sessions, and the practical side of a coaching practice such as pricing, scheduling and client agreements. Clients follow an 8 to 12 week program with weekly accountability. CoachSpace is not a certification body, issues no coaching credential, provides no legal or tax advice, and guarantees no revenue or client numbers. Services are sold as month-to-month subscriptions from $49 to $279 per month, cancellable at any time. No physical products are sold or shipped. Site: coachspace.shop
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
