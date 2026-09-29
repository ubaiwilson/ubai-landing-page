# Design brief: Ubai Wilson landing page

## Product and audience
- Ubai Wilson, licensed real estate negotiator in Johor Bahru (IQI Realty, Elite Legacy). REN number to be added.
- Sells new-launch property near the JB CIQ (the Causeway border crossing) and the RTS Link rail to Singapore, targeted for early 2027.
- Featured projects: Exsim Kebun Teh and Exsim CIQ. Developers: Exsim, Setia, Eco World, Mah Sing, IWCity.
- Visitors: investors renting to cross-border workers, first-time buyers and people buying to live in; both Malaysians and Singaporeans. Most arrive on phones.

## Goal
- One action: message Ubai on WhatsApp (601126168047).
- Main button label: "Get your free consultation", with a WhatsApp icon. Pre-filled messages start "Hi Ubai, I'd like a free consultation…".
- Secondary: a custom "Free Consultation" form that submits to his Google Form in the background (no redirect). It is closed by default behind a "Prefer a form? Leave your details" button.
- The hero must say who he is and what he does within 3 seconds. The main button is the most prominent element after the headline.

## Colours
- Navy #0F1E2B (text, hero, final section); navy 2 #1A2E3F; footer #0A1622
- Paper #F4F4F1 (page background); white #FFFFFF; sand #EAE5DC (quiet bands)
- Hairlines #DCDFDA; field borders and slider track #858E88
- Secondary text: #56616B on light, #AEB8C2 on navy
- Green #1E6B5C (buttons on light sections); mint #8FD3BF (main button only); error #B3261E
- Only three full navy blocks: hero, final call to action, footer. Everything else is light.

## Type
- One font: Bricolage Grotesque.
- Hero headline: weight 800, condensed (75% width), the largest text on the page.
- Section headings: weight 700, normal width, about 26–40px.
- Body: 16px on phones, 17px on desktop, regular weight.
- Key figures (10,000 / RM2,200 / yield %) use the condensed style, with evenly spaced digits.
- Sentence case everywhere; no all-caps labels.

## Layout, in page order
1. Header: name with a tagline underneath, nav links (desktop only), main button (shortened to "Free consultation" on narrow phones).
2. Hero (navy):
   - headline "New homes in JB, by the Causeway." and a first-person intro
   - "I'm looking to" chips (Invest / Buy to live in / Check my loan) that change the WhatsApp message, always on one row
   - main button, then "Free, no obligation. I usually reply within a minute." and a small message preview
   - photo: 16:9 edge to edge on phones, 4:5 with a caption on desktop
   - route diagram (your home → JB CIQ → Singapore; dashed road, solid rail): vertical on phones, horizontal on desktop
   - the consultation form, closed by default
3. Why buyers are looking at JB now: a fact-sheet list, big figure on the left, statement and source on the right, thin lines between rows.
4. In the news: outlet name plus headline, four links.
5. Two projects I'd show you first:
   - framed white cards with photo, name, summary and one-column "label: value" facts
   - phones: sideways swipe that snaps, the next card peeking in by about 15%, a "1 of 2" counter and 44px arrow buttons
   - desktop: side by side
6. Buying new comes with extras: heading on the left, accordion on the right.
7. Hear about new launches before the public:
   - white logo tiles scrolling slowly right to left in a seamless loop, not pausing on hover
   - a still, wrapped row with reduced motion
   - use official logo files only; show names until they arrive
8. Check the rent against the price: two sliders and a navy result card. On phones, a compact yield result sits above the sliders.
9. Hi, I'm Ubai: 4:5 portrait, short bio, TikTok (@ubaiwilson), registration line.
10. How we'd work together: three numbered steps.
11. Questions buyers ask me: accordion.
12. Want to sell property too? A sand band with one button.
13. Final call to action (navy): "Tell me what you're looking for." plus the main button.
14. Footer: name, registration, links, disclaimer.
15. Phones: a sticky bottom bar with the main button. It appears after the hero button scrolls away and hides while the form is open or someone is typing.

Recurring detail: a small dashed-dot-solid "route mark" above section headings.
Corners: 6px on photos and panels, 8px on form fields; buttons are fully rounded.

## Buttons
- Pill shape, 2px border, solid bottom edge. They lift slightly on hover and press down when tapped. Icon on the left.
- Main button: mint fill, extra-bold, soft glow. 68px tall on desktop; full width, 64px, one line on phones. The hero button pulses twice after the page loads.
- It is the only mint button. Others: green on light sections, white outline on navy, white on sand.
- Labels say exactly what happens ("Ask about Kebun Teh", "Send these numbers on WhatsApp").
- Every tap target is at least 44px tall.

## Copy tone
- First person from Ubai, plain and direct: short sentences, active voice.
- Specific over hype. Hedge anything uncertain ("targeted for early 2027", "up to RM2,200… actual rent depends on the unit").
- English on the page (the Google Form options are Malay behind the scenes).
- Error messages say how to fix the problem.
- Include the disclaimer: figures are indicative; nothing on the page is financial advice.

## Motion and accessibility
- Motion only guides attention or gives feedback: a quiet hero entrance, the button pulses, the route drawing once, soft scroll reveals, the logo loop, the yield number counting.
- With reduced motion, all of it switches off.
- WCAG AA contrast, visible focus, keyboard support, semantic HTML.
- One self-contained HTML file. Works from 320px wide with no sideways scrolling. Form inputs at least 16px. Respect the iPhone safe areas.

## Do not
- Make it look like an ad or pop-up: no saturated clashing colours, loud colour blocks, or yellow/red sale banners.
- Use "WhatsApp me" as the main button label.
- Embed the Google Form as an iframe or redirect to Google on submit.
- Put a long form in front of the rest of the page; keep it closed by default.
- Use oversized or heavy text, or generic templated "AI" styling.
- Hide the project swipe, or let the chips wrap onto two lines.
- Pause the logo row on hover.
- Draw or recreate developer logos.
- Include any Taufiq Ismail details or anything from the old site.
- Change more than what's asked in a scoped edit.

## Still to fill in
REN number, header tagline, photos (hero, two projects, portrait), the four news links, and Exsim CIQ's distance and price.