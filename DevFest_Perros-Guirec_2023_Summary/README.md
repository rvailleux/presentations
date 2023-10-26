## Install the marp tooling

```bash
npm install -g @marp-team/marp-cli
npm install -g scss
```

## Run the server with a preview that keep on watching for change
```bash
sass --watch ./themes/olive.scss ./themes/olive.css
marp -w slides.md -o index.html
npx live-server .
```
