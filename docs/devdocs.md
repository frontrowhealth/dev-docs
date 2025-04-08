# Horizontal Embedded Badge — Implementation Guide

## 🧠 Overview

Our product allows you to showcase a dynamic widget with a modal that highlights clinicians who have shared your product. This feature builds trust, enhances credibility, and empowers users to make confident, informed decisions when choosing healthcare providers.

**Current Offerings:**
- Embedded badge with dynamic number of clinician shares  
- Unpaid, clinician-authored qualitative reviews  
- Example brand with reviews: [Goodonya Organic Hydration Product](https://goodonyaorganic.com/products/goodonya-organic-hydration?variant=51816287699316&selling_plan=691826753908)

---

## 🏷️ Widget Types & Badge Placement

### Badge Options
- ✅ **Horizontally Embedded Badge** (recommended)
- ⚠️ **Sticker Badge** — *in development*

### Best Practices
- Place the badge **directly below the 5-star review banner** (mobile + desktop)
- Use the **Clinician’s Choice** badge (latest and best-performing)
- Use **landing page popups** for campaigns or new launches

---

## 🚀 Implementation Paths

### Shopify Stores

#### Option 1: Assisted Implementation (Recommended)

1. Grant access via your **Shopify collaborator code**.
2. We complete the setup within **1 hour** (2–3 business days turnaround).
3. Optionally, schedule a **screenshare call** for real-time setup.

**To share your collaborator code:**

- Login to Shopify  
- Go to `Settings > Users > Security > Collaborator Request Code`  
- Copy and share the code with the Frontrow team

---

#### Option 2: Self-Implementation

1. Login to your Shopify admin panel  
2. Navigate to:  
   `Online Store > Themes > Actions > Edit Code`  
3. Create a new snippet:  
   `snippets/frontrow.liquid`  
4. Paste the shared code snippet (contact us if needed)  
5. Locate the relevant product template (e.g., `main-product.liquid`)  
6. Paste the snippet where the badge should appear  
7. Save changes and preview the site  

---

### Custom Websites

1. Locate the HTML file where you’d like the badge or reviews to appear.  
2. Paste the corresponding snippet into the desired section.  
3. Test for correct functionality.  
4. Notify the Frontrow team for QA.

---

## 🧑‍💻 Developer Reference

### Code Snippets

We will provide JavaScript or HTML snippets based on your platform. Contact your Solutions Engineer for access.

### 🔄 Updating the Product URL or ID
1. **Locate the Product URL**  
   In the code snippet, look for the part that comes after `/products/`—this represents the specific product on your site.
2. **Update the Product Path**  
   Replace the existing product name or path with the correct one that matches your current product.
3. **Update the `product_id`**  
   Change the `product_id` value in the snippet to match the correct product. Your Solutions Engineer can provide this ID if you don’t have it.
4. **Save and Preview**  
   After updating the URL and ID, save your changes and preview the page to confirm everything displays correctly.


**Supported platforms:**
- HTML
- Liquid (Shopify)
- React / Next.js

---

## ➕ Adding New Products

1. **Update the Product Upload Sheet**  
   Add the new product(s) in the same format that you did for your other products.
2. **Contact Zeke**  
   He’ll confirm formatting and add the additional products to our library.
3. **Update Snippet**  
   We will provide the updated snippet with correct `product_id`
⚠️ **Please wait for confirmation before going live**  
This ensures QA and optimal badge performance.

---

## ❓ FAQ

**Q: Where should I place the badge?**  
A: Directly below the 5-star review banner on both desktop and mobile

**Q: What about the sticker badge?**  
A: It's in progress—we’ll notify you once it's ready

**Q: Can I customize the badge design or wording?**
A: To maintain the trust and recognition associated with our badge, we do not allow changes to the copy, fonts, or overall design. Consistency is key—when shoppers see the same trusted badge across multiple brands, the impact is significantly stronger.

We also hope you understand that making exceptions for individual brands can lead to inconsistencies across our network, ultimately weakening the credibility and effectiveness of the badge.


**Q: Can I use a PDF version of the badge?**  
A: No. It must be interactive and clickable for trust and transparency.

**Q: Will the badge slow down my site?**  
A: No. The solution is highly optimized and served as cached static HTML.

---

## 📬 Contact & Support

For implementation help, QA requests, or new product uploads, reach out to your Solutions Engineer or the Frontrow team.

