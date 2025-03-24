### 🔧 Troubleshooting – Why Is My Badge Not Appearing on the PDP?

If your badge isn't showing up or doesn't look right, here are a few common issues and fixes:

---

#### 🟡 **Badge Not Appearing**

- **Incorrect URL Matching**  
  Make sure all relevant PDP or landing page paths are included in the snippet’s `pageRules`.  
  > For example, double-check if it's `/products` vs `/product`, or `/collections/products` vs `/products`.

- **Missing Product Data**  
  The badge will only render if the product has associated clinician share data. Ensure the product is correctly registered in our system.

- **Delayed Script Load**  
  If the badge script is placed too low in the DOM or loaded asynchronously, try moving it higher or wrapping it in a `DOMContentLoaded` or `window.onload` event.

---

#### 🎨 **Styling or Spacing Issues**

- **Badge Overlapping Content**  
  Check for parent containers with `overflow: hidden` or conflicting `z-index` values.

- **Responsive Layout Conflicts**  
  Inspect how the badge behaves on mobile vs desktop. You might need to adjust margins or use media queries for optimal layout.

- **Custom CSS**  
  You can override or extend our default styles with your own class targeting. If needed, [contact our team](mailto:dev-support@frontrowmd.com) for help with custom styling.

---

#### 🧪 **Script or Integration Errors**

- **JavaScript Not Loading**  
  Confirm the badge script URL is correct and accessible. Test in incognito or a different browser to rule out extensions or blockers.

- **Console Errors**  
  Open your browser’s developer console and look for red error messages. These often point to missing data, blocked resources, or typos in configuration.

- **Multiple Snippet Loads**  
  Ensure the script is only loaded once per page. Duplicates can lead to inconsistent behavior.

---

### 🧵 Still Stuck?

If you've checked all the above and the badge still isn't working, [reach out to our support team](mailto:dev-support@frontrowmd.com) with:

- A link to the PDP
- A screenshot or screen recording
- Your integration snippet

We’ll get you unblocked ASAP!
