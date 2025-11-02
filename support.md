# Support for Bloomreach Analytics Studio

## Getting Help

Need assistance with the Bloomreach Analytics Studio extension? We're here to help!

## Contact Information

**Email:** isekai.nextgen.apps@gmail.com

For support requests, bug reports, feature suggestions, or general questions about Bloomreach Analytics Studio, please email us directly. We typically respond within 24-48 hours.

## Reporting Issues

When reporting a bug or issue, please include:

1. **Browser and Version**: Chrome, Edge, or Firefox version
2. **Extension Version**: Found in Chrome Extensions page (`chrome://extensions/`)
3. **Steps to Reproduce**: What were you doing when the issue occurred?
4. **Expected Behavior**: What should have happened?
5. **Actual Behavior**: What actually happened?
6. **Screenshots**: If applicable, please include screenshots
7. **Console Errors**: Any errors in Chrome DevTools Console (F12 → Console tab)

### Example Bug Report Format:

```
Browser: Chrome 120.0.0.0
Extension Version: 1.0.0
Description: Timeline events not showing

Steps to Reproduce:
1. Open DevTools
2. Navigate to Bloomreach Analytics Studio tab
3. Visit a website with Bloomreach

Expected: Events should appear in timeline
Actual: Timeline shows "No Events Detected" despite Bloomreach being present

Console Errors: [paste any errors here]
```

## Feature Requests

Have an idea to improve the extension? We'd love to hear it! Please email us with:

- Description of the feature
- Why it would be useful
- How you envision it working

## Common Questions

### The extension shows "No Bloomreach data detected"

**Possible causes:**
- Bloomreach/Exponea SDK is not loaded on the page
- The page uses a different analytics platform
- The SDK is loaded asynchronously (try clicking "Force Capture" button)
- Cookie consent is denied (extension shows "No Tracking" in this case)

**Solutions:**
- Wait a few seconds after page load and click "Refresh"
- Try clicking "Force Capture" to manually trigger data capture
- Check browser console for any Bloomreach SDK errors
- Verify Bloomreach is actually implemented on the website

### Events are not appearing in timeline

**Check these:**
- Cookie consent status (if denied, no events will show)
- Bloomreach SDK is actually firing events
- Try clicking "Force Capture" button
- Check if events are being filtered (use the filter input field)

### Configuration data is missing

**Possible reasons:**
- Configuration is set dynamically after page load
- Configuration is in a nested object we don't detect
- Try "Force Capture" to refresh data
- Configuration might only be available on specific pages

### Extension not working on a specific website

**Troubleshooting:**
- Ensure the website actually uses Bloomreach/Exponea
- Check if the page is a restricted URL (chrome://, edge://, about:, etc.)
- Try refreshing the page
- Clear browser cache and reload
- Check browser console for errors

### DevTools panel is blank or not loading

**Solutions:**
- Reload the DevTools panel (close and reopen)
- Refresh the page and try again
- Check browser console for extension errors
- Try disabling and re-enabling the extension
- Ensure you have the latest version of the extension

## Technical Support

For technical integration help with Bloomreach/Exponea:

- **Email**: isekai.nextgen.apps@gmail.com
- **Subject**: "Bloomreach Technical Support - [Your Topic]"

I am a Bloomreach consultant and can help with:
- Bloomreach SDK integration issues
- Configuration troubleshooting
- Event tracking debugging
- Custom implementation guidance

## Feedback

Your feedback helps us improve! We welcome:
- ✅ Bug reports
- ✅ Feature suggestions
- ✅ UI/UX improvements
- ✅ Documentation improvements
- ✅ General feedback

## Browser Compatibility

**Supported Browsers:**
- Google Chrome (version 88+)
- Microsoft Edge (Chromium-based, version 88+)
- Mozilla Firefox (version 78+)

**Known Limitations:**
- Some features may vary slightly between browsers
- Firefox requires Manifest V2 (separate build)

## Privacy and Data

For questions about privacy and data handling, please see our [Privacy Policy](privacy_policy.md).

## Version History

Current version and updates are documented in the extension's manifest and Chrome Web Store listing.

---

**Developer:** Isekai NextGen  
**Email:** isekai.nextgen.apps@gmail.com  
**Extension:** Bloomreach Analytics Studio

Thank you for using Bloomreach Analytics Studio!

