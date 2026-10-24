# TabNotes Website

Static website, support information, privacy policy, and terms for the TabNotes browser extension. The extension source and production backend are maintained separately.

## Preview locally

Serve this directory with any static HTTP server, for example:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000`. The pages are plain HTML and CSS; `styles.css` contains shared styling. `launch-config.json` holds public website links and contact information only. Do not put credentials in it.

The published site is available at <https://manojmallick.github.io/tabnotes/>.

## License

Original website code and assets are licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE). Third-party materials remain under their respective licenses.
