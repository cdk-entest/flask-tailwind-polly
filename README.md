## Compile Tailwind

```bash
npx tailwindcss -i ./src/input.css -o ./templates/output.css --watch
```

```ts
<link href="{{ url_for('static', filename='output.css')}}" rel="stylesheet" />
```
