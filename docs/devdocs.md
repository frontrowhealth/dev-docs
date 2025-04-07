Implementation
================

### **Introduction**

*   **Overview**: Our product allows you to showcase a dynamic widget with a modal that highlights the clinicians who have shared your product. This feature builds trust, enhances credibility, and empowers users to make confident, informed decisions when choosing healthcare providers. Whether you’re implementing this on a Shopify store or a custom platform, this guide will walk you through the necessary steps and resources to seamlessly integrate these features.
    

**Current Offerings**:  
- Embedded badge with dynamic number of clinician shares  
- Quantitative and qualitative doctor reviews (unpaid, clinician-authored)  
  - Here is [an example brand with doctor reviews](https://goodonyaorganic.com/products/goodonya-organic-hydration?variant=51816287699316&selling_plan=691826753908) 


### **Product Page Badges**

To ensure maximum visibility and credibility, we recommend using the **Horizontally Embedded Badge** within the product details. Additionally, a **landing page popup** can be used to highlight clinician endorsements earlier in the customer journey.

> ⚠️ **Note**: While we previously offered a **sticker badge** (typically placed in the image carousel), we are currently working on a **new and improved version** of this sticker. We'll share updates as soon as it becomes available. In the meantime, the **Clinician’s Choice embedded badge** remains the recommended option for performance and trust.


### **Doctor Reviews**
Clinician-authored qualitative reviews—unpaid and independently written—add authenticity and depth to product endorsements. If you're interested in featuring these reviews, please reach out to your sales representative for more information.

## **Best Practices**

To ensure optimal performance and credibility, follow these implementation guidelines:

- **Badge Placement**  
  Place the badge **directly underneath the 5-star review banner** on both **mobile and desktop**.  
  This placement yields the highest engagement and reinforces trust by pairing customer ratings with verified clinician endorsements.

- **Use the Latest Badge Version**  
  Always use the **Clinician’s Choice** badge design. This is the **most up-to-date and best-performing** version of the badge.  
  > If you've seen other versions of the badge, they are outdated. The Clinician’s Choice version has been proven to outperform older designs in user engagement and credibility impact.

- **Landing Page Popups**  
  Use a landing page popup to highlight clinician endorsements early in the customer journey. This is especially effective for campaign-specific pages or new product launches.

- **Authentic, Unpaid Reviews**  
  Clinician reviews should be displayed prominently. These are **non-compensated, qualitative reviews** and play a key role in establishing authenticity and trust.


### **Getting Started**

**Key Requirements**:

To integrate our Verified Clinician Reviews widget, you’ll need one of the following:

*   **For Custom Website Implementation**:
    
    *   Access to your site’s codebase with the ability to add and test JavaScript snippets.
        
    *   Permissions to update the relevant sections of your website where the widget will be embedded.
        
*   **Implementation Options**:
    
    *   **Assisted Implementation (recommended)**: Grant us Shopify access, and our team will complete the setup for you within 2–3 business days.
        
    *   **Self-Implementation**: Follow this guide to embed snippets directly into your website or Shopify store.
        

*   Wordpress or drag and drop editors? - drag code block + paste code snippet from Frontrow team
    

### **Code Snippets**

Our Verified Clinician shares widget can be seamlessly integrated into your website using code snippets that we’ll provide. These snippets are designed to display clinician badges and verified reviews in high visibility locations on your site. if youre unsure about placement, check in with frontrow team - but also we will give them our suggestion so they can reference already

We will share the required snippets directly with you or your developement team,r, along with detailed instructions on where and how to implement them. If you prefer, our team can implement for you by utilizing your Shopify collaborator code.

samples of high level codesnippets - doctor reviews + badge embedded

### **Adding a New Product**

To add a new product and ensure the badge is implemented correctly:

1. **Add the Product to the Upload Sheet**  
   Locate the product upload spreadsheet you were initially provided. Add your new product(s) following the same format.

2. **Contact Zeke**  
   Once you've updated the sheet, reach out to **Zeke**—your original point of contact for product uploads. He’ll confirm receipt and ensure everything is formatted correctly.

3. **Approval & Badge Setup**  
   We’ll review your submission to ensure the product has been **approved and added to our internal library**. Once that’s confirmed, we’ll provide you with the updated code snippet that includes the correct `product_id` and implementation guidance.

> ⚠️ **Please wait for our confirmation before adding the badge to your site.**  
> This ensures the product has been **QA’d and properly set up for success** and optimal performance.


Just modify this section for use cases above and include syntax for next js, html, and liquid

If you need to modify the product URL in the provided code snippets, follow these steps:

1.  **Locate the URL Field:** In the code snippet, look for the section where the product URL is defined. This is typically found after /products/ in the request.path condition.
    
2.  **Update the Product Path:** Replace the existing product path with the correct product identifier. Ensure that the format remains consistent, using single quotes around the path.
    
3.  **Update the Product ID:** Modify the product\_id in the script and iframe source URL to match the correct product. This can be verified with your solutions engineer.
    
4.  **Save and Preview:** Once updated, save your changes and preview your site.
    

### **Implementation Guide**

*   If you decide to self implement, please let us know when the badge is live so we can QA…
    
    *   **Assisted Implementation**:
        
        *   Grant us access to your Shopify store, send FRH team your collaborator code
            
        *   Our team will complete the implementation and provide a QA review within 2–3 business days. - we can mention it takes us about 1 hour maximum
            
        *   Can also be done on a call while we screenshare
            
    *   **How do I share my Shopify collaborator code?**
        
        1.  Login to Shopify
            
        2.  Go to Settings > Users > Security > collaborator code
            
        3.  Copy and share that code with Frontrow
            
    
    *   **Self-Implementation Steps**:
        
        1.  Log in to your Shopify admin panel.
            
        2.  Navigate to **Online Store > Themes > Actions > Edit Code**.
            
        3.  In the snippets folder, create a new file called frontrow.liquid
            
        4.  Paste the contents of the gist file that was shared with you. If you do not have this, reach out to your solutions engineer.
            
        5.  Identify the appropriate template file (product.liquid, collection.liquid, etc.) where the badge or reviews should appear. Usually this is called main-product or main-pdp
            
        6.  Drag and drop custom code block can be used as well on each individual pdp
            
        7.  Paste the provided snippet into the desired location within the file.
            
        8.  Save your changes and preview the site to ensure the badge or widget displays correctly.
            
*   **For Custom Websites**:
    
    *   Locate the HTML file where you’d like to display the badge or reviews.
        
    *   Insert the corresponding snippet into the desired section of your code.
        
    *   Test the changes to confirm proper functionality.
        
    *   Let FRH team know when badge is live - mostly for us so we can QA
        
    

### **FAQ**

- **Where should I place the badge?**  
  Snippets should be added to product or provider pages. The **best implementation strategy** is to place the badge **directly underneath the 5-star review banner** on both desktop and mobile.

- **What about the sticker badge?**  
  We're actively working on a **new version** of the sticker badge. While it's not currently required, we’ll provide guidance and assets when the updated version is ready.

- **Can I customize the badge?**  
  For legal and design reasons, we can’t change the copy or font sizes. However, we can use your **brand name** instead of “this product” and match your **brand colors**—just send us your hex codes and we’ll update it on our end.

- **Can I add a PDF version to my site?**  
  No. The badge is meant to be **interactive and clickable** so shoppers can verify its authenticity in real-time. A PDF wouldn’t provide the same level of trust and transparency.

- **Will the badge slow down my site?**  
  No. The solution is **highly optimized**. Content is cached and served as static HTML for fast performance without significant load time.
