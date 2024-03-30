How to reproduce the bug:

1. `npx wrangler deploy --triggers "* * * * *"`
2. `npx wrangler deploy`

If you see the triggers tab in the dashboard, `* * * * *` is still there.
