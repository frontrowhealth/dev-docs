### 🔧 Troubleshooting – Why Is My Badge Not Appearing on the PDP?

If your badge isn't showing up or doesn't look right, here are a few common issues and fixes:

---

#### 🟡 **Badge Not Appearing**

- **Incorrect URL Matching**  
  Make sure all relevant request paths are included in the snippet.  
  > For example, double-check if it's `/products` vs `/product`, or `/collections/products` vs `/products`.

- **Missing or Incorrect Product Data**  
  The badge will render based on the product’s `product_id`, so please ensure the correct product is associated with the appropriate ID. If you're unsure, your Solutions Engineer can help confirm this for you.

- **Delayed Script Load**  
  If the badge isn’t showing up, it may be because the script is loading too late in the page’s load sequence. Try moving the script higher in the HTML, or make sure it runs once the page has fully loaded to ensure everything displays correctly.

---

#### 🎨 **Styling or Spacing Issues**

- **Badge Overlapping Content**  
  Check for parent containers with `overflow: hidden` or conflicting `z-index` values.

- **Responsive Layout Conflicts**  
  Inspect how the badge behaves on mobile vs desktop. You might need to adjust margins or use media queries for optimal layout.

 - **Custom CSS**  
  While it is technically possible to override or extend our default styles using your own class targeting, we **strongly advise against making custom CSS changes**. Our current badge design is the result of extensive research and testing across dozens of health brands, and we’ve optimized it specifically to maximize visibility, trust, and conversions. 

  That said, if you have a specific use case you’d like to discuss, feel free to [contact our team](mailto:dev-support@frontrowmd.com).


---

#### 🧪 **Script or Integration Errors**

- **JavaScript Not Loading**  
  Confirm the badge script URL is correct and accessible. Test in incognito or a different browser to rule out extensions or blockers.

- **Console Errors**  
  Open your browser’s developer console and look for red error messages. These often point to missing data, blocked resources, or typos in configuration.


---

### 🧵 Still Stuck?

If you've checked all the above and the badge still isn't working, [reach out to our support team](mailto:dev-support@frontrowmd.com) with:

- A link to the PDP
- A screenshot or screen recording
- The code snippet

We’ll get you unblocked ASAP!
