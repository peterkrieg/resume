## Resume

My resume is written in markdown and then uses the `md-to-pdf` package to convert markdown to pdf.  This can be viewed in real-time via the command:

```bash
open -a Skim.app ./test.pdf && npx md-to-pdf test.md -w --stylesheet=styles.css
```