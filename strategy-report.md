# Growth Strategy Report: Cynbit × BitElevate

## Growth hypothesis
If we change our ads and landing page message from "certificates" to "real projects", then landing page conversion will increase, because students trust certificate-only courses less and want proof of skill they can show to recruiters.

## Rationale
- **Pain-led message:** students fear not being placed and get stuck in tutorial hell. The copy names this and offers a concrete 4-week fix.
- **Low-friction conversion:** nominal fees, one main action, short form.
- **Trusted distribution:** college clubs and peer groups carry more credibility than ads alone.
- **Built-in virality:** referral rewards are non-cash (mentor time), which protects margin.

## Metrics tracking plan
| Stage | Event / metric | Tool |
|---|---|---|
| Awareness | Impressions, reach, CTR | Meta Ads Manager |
| Visit | `page_view` with UTM parameters | GA4 |
| Interest | `cta_click` | GA4 |
| Sign-up | `signup_submit` (the conversion) | GA4 + form backend |
| Referral | `invite_sent`, referred sign-ups | Unique referral codes |

- Every link carries `utm_source`, `utm_medium`, `utm_campaign`, `utm_content`.
- A Google Sheet joins spend and sign-ups per channel to calculate CAC weekly.
- A weekly dashboard shows funnel by channel, CAC trend and A/B results.

## Risks and mitigation
- **Low-quality paid leads:** add college and year fields; review the first 100 sign-ups.
- **CAC above target after week 2:** shift effort to clubs and referrals.
- **Slow club partnerships:** start outreach in week 1; keep WhatsApp sharing as backup.

## Assumptions
Budget, targets and conversion rates are assumptions, not Cynbit's data. They would be replaced with real baselines after week 1.

## Facts from cynbit.in/bitelevate
- Engineering-student program run from Jaipur, with 15+ domain tracks and 4, 8 or 12 week durations.
- Cynbit claims 1000+ students trained and 88% post-program placement (their own claims, not independently verified).
- Pricing is "nominal fees", so ads must not say "free".
- Partner colleges named on the site (SKIT, JECRC, Poornima) make good first targets for club and ambassador outreach.
