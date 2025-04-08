# Verified Clinician Reviews — Implementation Guide

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

1. Grant access via your **Shopify collaborator code**
2. We complete the setup within **1 hour** (2–3 business days turnaround)
3. Optionally, schedule a **screenshare call** for real-time setup

**To share your collaborator code:**

- Login to Shopify  
- Go to `Settings > Users > Collaborator Request Code`  
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

1. Locate the HTML file where you’d like the badge or reviews to appear  
2. Paste the corresponding snippet into the desired section  
3. Test for correct functionality  
4. Notify the Frontrow team for QA

---

## 🧑‍💻 Developer Reference

### Code Snippets

We will provide JavaScript or HTML snippets based on your platform. Contact your Solutions Engineer for access.

### Updating Product URL or ID

1. **Find the URL Path** in the snippet (usually after `/products/`)
2. Update to the correct product identifier  
3. Modify the `product_id` in the script or iframe URL  
4. Save changes and preview the site  

**Supported platforms:**
- HTML
- Liquid (Shopify)
- React / Next.js

---

## ➕ Adding New Products

1. **Update the Upload Sheet**  
   Add the new product(s) in the same format

2. **Contact Zeke**  
   He’ll confirm formatting and receive the update

3. **Wait for Confirmation**  
   We will provide the updated snippet with correct `product_id`

> ⚠️ **Please wait for confirmation before going live**  
> This ensures QA and optimal badge performance

---

## ❓ FAQ

**Q: Where should I place the badge?**  
A: Directly below the 5-star review banner on both desktop and mobile

**Q: What about the sticker badge?**  
A: It's in progress—we’ll notify you once it's ready

**Q: Can I customize the badge?**  
A: Yes, you can use your brand name and colors. Fonts and copy are fixed.

**Q: Can I use a PDF version of the badge?**  
A: No. It must be interactive and clickable for trust and transparency.

**Q: Will the badge slow down my site?**  
A: No. The solution is highly optimized and served as cached static HTML

---

## 📬 Contact & Support

For implementation help, QA requests, or new product uploads, reach out to your Solutions Engineer or the Frontrow team.

