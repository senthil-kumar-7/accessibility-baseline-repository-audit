# Accessibility Audit Report

## 1. Website audited

- Website name:
- URL:
- Date:
- Browser:
- Device:
- Lighthouse version/mode:
- Scope/pages tested:

## 2. Lighthouse baseline

Record the Accessibility score and the important failed/flagged audits.

| Metric | Result |
|---|---|
| Accessibility score | |
| Best Practices score | |
| Performance score | |
| SEO score | |

## 3. Keyboard-only navigation

Test using only:
- Tab
- Shift + Tab
- Enter
- Space
- Arrow keys where appropriate
- Esc where appropriate

Record observations such as:
- Can the main navigation be reached?
- Is focus visible?
- Is focus order logical?
- Can forms be completed without a mouse?
- Can menus/dialogs be opened and closed?
- Is there a keyboard trap?

## 4. Five issues

Enter exactly five issues in `accessibility-audit-template.csv`.

For every issue include:
- concrete page/component
- WCAG reference when applicable
- evidence
- severity
- user impact
- recommended fix
- owner
- status

## 5. Remediation priority

Use the severity field consistently:
- Critical — blocks a major task for some users
- High — significant barrier
- Medium — meaningful but workaround exists
- Low — minor issue

## 6. Screenshots

Save evidence images in `/screenshots` and use clear names:

```text
01-lighthouse-baseline.png
02-keyboard-focus.png
03-issue-1.png
04-issue-2.png
05-issue-3.png
06-issue-4.png
07-issue-5.png
```

## 7. Architecture findings

Document:
- client responsibilities
- server responsibilities
- API boundary
- documentation location
- test location
- first vertical feature slice
