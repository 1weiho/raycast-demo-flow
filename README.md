# Demo Flow

Demo Flow is a Raycast extension that lets you organize demo snippets and quickly paste the next/previous snippet during a walkthrough.

**Features**
- Create and manage demos and snippets
- Paste next/previous snippet with a command
- Menu bar preview of upcoming snippets
- Import/export demos (JSON)

**Commands**
- `Manage Demo Snippets`: manage demos and snippets
- `Next Snippet`: paste the next snippet
- `Previous Snippet`: paste the previous snippet
- `Menu Bar Demo Snippet`: menu bar preview
- `Import Demo Snippet`: import JSON

**Import format**
```json
{"name":"My Demo","snippets":["npm install","npm run dev"]}
```

**Development**
```bash
npm install
npm run dev
```

**Build/Lint**
```bash
npm run build
npm run lint
```
