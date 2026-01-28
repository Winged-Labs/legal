# Winged Legal Documentation

Official legal documents for the Winged dating application.

## Documents

- **Privacy Policy**: [View Live](https://winged-labs.github.io/legal/privacy-policy/)
- **Terms of Service**: [View Live](https://winged-labs.github.io/legal/terms-of-service/)

## Purpose

These documents are hosted via GitHub Pages and are referenced in:
- Winged iOS app (during onboarding and in settings)
- Apple App Store submission (required for review)
- User consent flows

## Structure

```
legal/
├── privacy-policy/
│   └── index.html
├── terms-of-service/
│   └── index.html
└── README.md
```

## Setup Instructions

### 1. Clone this repository
```bash
git clone https://github.com/Winged-Labs/legal.git
cd legal
```

### 2. Enable GitHub Pages
1. Go to repository Settings
2. Navigate to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"
6. Wait 2-3 minutes for deployment

### 3. Verify URLs
After deployment, verify these URLs are accessible:
- https://winged-labs.github.io/legal/privacy-policy/
- https://winged-labs.github.io/legal/terms-of-service/

## Updating Documents

To update the legal documents:

1. Edit the HTML files in `privacy-policy/index.html` or `terms-of-service/index.html`
2. Update the "Last Updated" date in the header
3. Commit and push changes
4. GitHub Pages will automatically redeploy (2-3 minutes)

**Important**: After updating, notify users via in-app notification if changes are significant.

## Testing

Before deploying changes:
1. Open HTML files in a browser locally
2. Check all links work
3. Verify mobile responsiveness
4. Test on iOS Safari (this is what App Store reviewers will use)

## Contact

For questions about these legal documents:
- **Email**: support@wingedapp.com
- **Legal inquiries**: support@wingedapp.com

## Related Repositories

- **iOS App**: https://github.com/Itsdarkhere/Winged_3
- **Legal Docs**: https://github.com/Winged-Labs/legal

---

© 2026 Winged. All rights reserved.
