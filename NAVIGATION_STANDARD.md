# Navigation standard

Canonical Academy compatibility shell:

```html
<script defer src="https://skunkworksacademy.com/assets/academy-navigation.js?v=2026.08.15.1" data-skunkworks-global-nav="v10"></script>
```

The compatibility loader delegates to the canonical runtimes in `skunkworks-academy/www`:

- `skunkworks-ui.js?v=2026.08.15.1` — global public navigation runtime
- `skunkworks-footer.js?v=2026.08.15.1` — global public footer runtime
- `skunkworks-design-system.css?v=2026.08.15.1` — canonical public design system

Public pages must load the shared Skunkworks Academy shell exactly once and must not maintain a separate public top menu, logo switcher, burger menu, or legal footer.

Authenticated/application-local navigation remains permitted when it is not the public website shell. Preserve intentionally local chrome with `data-sk-preserve-header` and `data-sk-preserve-footer`.

Current compatibility contract: `v10` / `2026.08.15.1`.
