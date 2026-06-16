# academic-citizens-landing

The umbrella landing page for **[academic-citizens.org](https://academic-citizens.org/)** —
open initiatives for the academic community. It lists the hosted projects and links to the
**SUIT Working Group** join flow at
[`join.suit.academic-citizens.org/welcome`](https://join.suit.academic-citizens.org/welcome).

Plain static site — `index.html` + `assets/`, no build step.

## Deploy

Hosted on Vercel (team `rightonskill`, project `academic-citizens-landing`), serving the apex
`academic-citizens.org` (and `www` → 308 → apex).

```bash
vercel --prod        # deploy the current folder to production
```

> DNS lives at OVH. The apex uses Vercel's current A records `216.150.1.1` / `216.150.16.1`
> (the legacy single IP `76.76.21.21` is blocked on some enterprise/university networks).

## License

MIT
