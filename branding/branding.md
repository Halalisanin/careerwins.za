# careerwins Branding

```css
/* ============================================================
   BRAND — careerwins (Instagram)
   Palette: Deep Teal + Golden Sand
   Tone: Aspirational, celebratory, achievement-driven
   ============================================================ */

[data-brand="careerwins"] {
  --brand-primary: #006D77;
  --brand-secondary: #E9C46A;
  --brand-accent: #E9C46A;
  --brand-bg: #F0F9FA;
  --brand-text: #0A2A30;
  --brand-muted: #6B9EA5;
  --brand-font-heading: Arial, Helvetica, sans-serif;
  --brand-font-body: Georgia, "Times New Roman", serif;
  --brand-border: #E9C46A;
  --brand-radius: 10px;
}

[data-brand="careerwins"] h1 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 2.25rem;
  font-weight: 800;
  color: #006D77;
  line-height: 1.15;
  letter-spacing: -0.75px;
  text-transform: uppercase;
}

[data-brand="careerwins"] h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.5rem;
  font-weight: 700;
  color: #006D77;
  line-height: 1.25;
  letter-spacing: -0.25px;
}

[data-brand="careerwins"] h3 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1.125rem;
  font-weight: 700;
  color: #E9C46A;
  line-height: 1.4;
}

[data-brand="careerwins"] p,
[data-brand="careerwins"] li {
  font-family: Georgia, "Times New Roman", serif;
  font-size: 1rem;
  font-weight: 400;
  color: #0A2A30;
  line-height: 1.8;
}

/* ============================================================
   SHARED UTILITY CLASSES
   ============================================================ */

.brand-card {
  background: var(--brand-bg);
  color: var(--brand-text);
  border: 1px solid var(--brand-border);
  border-radius: var(--brand-radius);
  padding: 1.5rem;
}

.brand-btn {
  background: var(--brand-primary);
  color: var(--brand-bg);
  border: none;
  padding: 0.5rem 1.25rem;
  border-radius: var(--brand-radius);
  font-family: var(--brand-font-body);
  font-size: 0.875rem;
  cursor: pointer;
}

.brand-btn:hover {
  opacity: 0.9;
}

.brand-heading {
  font-family: var(--brand-font-heading);
  color: var(--brand-primary);
  line-height: 1.2;
}

.brand-link {
  color: var(--brand-primary);
  text-decoration: underline;
  text-decoration-color: var(--brand-accent);
}

.brand-muted {
  color: var(--brand-muted);
}

.brand-accent {
  color: var(--brand-accent);
}

.brand-post {
  background: var(--brand-bg);
  color: var(--brand-text);
  border: 1px solid var(--brand-border);
  border-radius: var(--brand-radius);
  padding: 1.25rem;
  font-family: var(--brand-font-body);
  max-width: 600px;
}

.brand-post h3 {
  font-family: var(--brand-font-heading);
  color: var(--brand-primary);
  margin: 0 0 0.5rem;
}

.brand-post .meta {
  color: var(--brand-muted);
  font-size: 0.8rem;
}

.brand-hashtag {
  color: var(--brand-primary);
  opacity: 0.8;
  font-size: 0.8rem;
}
```
