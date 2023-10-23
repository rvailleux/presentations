```bash
//Install the marp tooling
npm install -g @marp-team/marp-cli
npm install -g scss

//Run the server with a preview that keep on watching for change
sass --watch ./themes/olive.scss ./themes/olive.css
marp -w *.md -o index.html
```