# The High 5 Guys – Review Site

Static site at review.thehigh5guys.com (Vercel project `high-five-guys-review`).

## How it works
- `/` star page: "How was your experience with The High 5 Guys?"
- 4–5 stars open the Google review page and land on `/thank-you`.
- 1–3 stars go to `/feedback`, a private form that posts to the High 5 Guys Hub (`/api/review-feedback`) and shows up under Client Reviews. A small "Leave a Google review" link stays at the bottom of the form.
- Config (Google review URL, threshold) lives at the top of `index.html`.

## Deploy
Push to `main`; Vercel deploys automatically.
