# Task: what it shows

MEGA.dev challenge S01E03. The support desk merged 412 date-related reports into one ticket,
`#4471`, and marked it "known" (one cause, one fix queued). Reading the kb export and the raw
reports shows it is actually three different problems, bundled together because the desk dedupes
on subject line alone.

- [`kb/incidents/4471-split/+page.svx`](kb/incidents/4471-split/+page.svx) — the kb page, signed.
- [`kb/incidents/4471-split/rendered.html`](kb/incidents/4471-split/rendered.html) — the same page
  as the desk would see it.
- the [Issues](../../issues) tab — one ticket per problem, each with its report count.

| problem | reports |
|---|---|
| parser reads month-first | 374 |
| `booking-v3` hint mismatches locale | 33 |
| one-day shift, not a swap | 5 |
