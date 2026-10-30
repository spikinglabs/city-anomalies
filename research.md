# Research brief

- **Idea:** Rare things in a big city that parents should know before they go out with
  children: a large demonstration or march in the centre, a big police operation, a WWII bomb
  defusal with an evacuation zone, a transit strike, a closure of central roads or lines.
  Allo Outings (outings.allo.land, 小鹿出游) turns confirmed ones into short alerts for parents,
  for example on Rednote. Started 2026-10-30 after a 15,000-person demo in Köln on Halloween.
- **Records look like:** one announced event with city, day, time, place, route and a link to
  the official source (see `schema.yaml`).
- **In scope:** Köln, Berlin, München, Hamburg, Frankfurt am Main, Düsseldorf. Official
  sources first: police press releases and assembly lists, city traffic calendars, transit
  operators (KVB, BVG, MVG, HVV, VGF, Rheinbahn), union strike notices. Up to a year ahead;
  press releases from the last 14 days.
- **Out of scope:** ordinary crime and accident reports, rumours, social media posts, news
  sites (use them only to find the official source), small towns.
- **Preferred source types:** feeds (`.ics`, RSS, JSON) before HTML pages, and HTML with
  schema.org data before pages that need selectors. Many sources carry everything the police
  publish; the `teaser` pattern in `schema.yaml` keeps only the relevant ones.
- **A person decides.** Nothing collected here is shown to parents without a human check.
