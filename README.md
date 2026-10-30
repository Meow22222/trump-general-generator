# Make America General Again

**Satire / Parody.** A mobile-friendly political humor game about an invented
Trump-style promise to give supporters U.S. general ranks. All dialogue and
commissions are fictional. This is not a real quotation, military appointment,
endorsement, or campaign service, and has no affiliation with Donald Trump,
any campaign, the U.S. government, or the U.S. military.

## Play locally

Requires Python 3.9+; no packages or build step:

```sh
python3 trump.py
```

Open `http://127.0.0.1:8000` in your browser. Stop with Ctrl+C.
For a phone on a trusted local network, run `python3 trump.py --host 0.0.0.0`
and open your computer's LAN address on port 8000. This is a development server,
not a production server. You can also open `index.html` directly.

Enter a made-up ceremonial name, choose a fictional ballot response, and claim
a fake four-star promotion. Enjoy the paperwork meter, random silly missions,
star confetti, and printable souvenir. All choices receive a parody commission.
Reduced-motion preferences are respected, and controls work with a keyboard.

## Privacy

Use a nickname, not your real identity or voting history. Input stays in browser
memory; there are no analytics, cookies, storage, external assets, or API calls.
The local development server logs HTTP requests to the terminal, not form input.
User input is rendered as text, never HTML.

## Publish on GitHub Pages

In repository **Settings → Pages**, select **Deploy from a branch**, then
`main` and `/ (root)`. The site is plain HTML/CSS/JavaScript; `trump.py` is only
for local development. GitHub Pages publication is a separate repository setting.

## Checks

```sh
python3 -m py_compile trump.py
python3 trump.py --help
```

Browser smoke checks: test all three ballot choices, whitespace-only names,
HTML-like nicknames, repeated promotions, narrow mobile layouts, reduced motion,
and the print button. No dependency installation is required.

## License

MIT — see [LICENSE](LICENSE).
