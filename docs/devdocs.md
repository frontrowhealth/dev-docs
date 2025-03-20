\[WIP\] Dev docs
================

### **Introduction**

*   **Overview**: Our product allows you to showcase a dynamic widget with a modal that highlights the clinicians who have shared your product. This feature builds trust, enhances credibility, and empowers users to make confident, informed decisions when choosing healthcare providers. Whether you’re implementing this on a Shopify store or a custom platform, this guide will walk you through the necessary steps and resources to seamlessly integrate these features.
    

Current Offerings: embedded badge + doctor reviews, quantitative data + qualitative doctor reviews, link to goodonya

**Product Page Badges**: To ensure maximum visibility and credibility, the **Award (Sticker)** and the **Horizontally Embedded Badge** must be used together. The sticker serves as a prominent trust signal on top of product image carousels, while the horizontal badge reinforces credibility within the product details. Additionally, a **landing page popup** can be used to further highlight clinician endorsements and showcases the data at the start of or early on in the customer journey..

Doctor Reviews: Clinician-authored qualitative reviews w/o compensation that add depth and authenticity to product endorsements.

Best Practices - maybe results after project falcon + research
==============================================================

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

Our Verified Clinician Reviews widget can be seamlessly integrated into your website using code snippets that we’ll provide. These snippets are designed to display clinician badges and verified reviews in high visibility locations on your site. if youre unsure about placement, check in with frontrow team - but also we will give them our suggestion so they can reference already

We will share the required snippets directly with you or your developement team,r, along with detailed instructions on where and how to implement them. If you prefer, our team can implement for you by utilizing your Shopify collaborator code.

samples of high level codesnippets - doctor reviews + badge embedded

### Adding to a bundle page

### My PDP request path changed or product name changed

### Adding the badge to a landing page

### Adding a new product

*   reach out to Frontrow team - Zeke
    
*   ask Frontrow team for new product ids or new snippet to add into your snippet
    

Just modify this section for use cases above and include syntax for next js, html, and liquid

If you need to modify the product URL in the provided code snippets, follow these steps:

1.  **Locate the URL Field:** In the code snippet, look for the section where the product URL is defined. This is typically found after /products/ in the request.path condition.
    
2.  **Update the Product Path:** Replace the existing product path with the correct product identifier. Ensure that the format remains consistent, using single quotes around the path.
    
3.  **Update the Product ID:** Modify the product\_id in the script and iframe source URL to match the correct product. This can be verified with your solutions engineer.
    
4.  **Save and Preview:** Once updated, save your changes and preview your site.
    

### **Implementation Guide**

*   If you decide to self implement, pls let us know when the badge is live so we can QA…
    
    *   **Assisted Implementation**:
        
        *   Grant us access to your Shopify store, send FRH team your collaborator code
            
        *   Our team will complete the implementation and provide a QA review within 2–3 business days. - we can mention it takes us about 1 hour maximum
            
        *   Can also be done on a call while we screenshare
            
    *   **How do I share my Shopify collaborator code?**
        
        1.  Login to Shopify
            
        2.  Go to Settings > Users > Security > collab code
            
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
        

### **QA and Verification Process**

### **Troubleshooting - Why is my badge not appearing on the PDP?**

### Why is the spacing off?

*   **Badge Not Appearing**: Ensure the all your PDP/landing page request paths are included in the snippet. Sometimes it could be simple like “/product**s**” vs “/product” or “/collections/products” vs “/products”
    
*   **Styling Issues**: Adjust the CSS or contact our team for assistance with custom styling.
    
*   **Script Errors**: Verify the JavaScript file URL is accessible and not blocked by browser or security settings.
    

### **FAQ**

*   Snippets should be added to the section of your website where the badge or reviews will appear (e.g., product or provider pages). The best implementation strategy is to add both the sticker and the horizontal badge to your product pages. The sticker badge will live in your product’s image carousel, while the horizontal badge appears within the product details to reinforce credibility.
    
*   For legal and design reasons, we can not change the copy, font-sizes, etc. besides using your brand name instead of “this product”.However, we can use your branding colors. Email us with the hex codes and our eng team will update it on our end.**Can I add a pdf version to my site?**No, we cannot add a PDF version because the badge needs to be interactive and clickable. This allows shoppers to verify its authenticity in real-time, ensuring they can see up-to-date, verified information. A static PDF would not provide the same level of trust and transparency, which are key factors in driving higher engagement and conversion rates.**Will the badge slow down my site?**No, our solution is highly optimized for load speed. Content is cached and served as static HTML files, ensuring the fastest possible performance without adding significant load time to your site.
    

Ad Creatives + Marketing assets
-------------------------------

*   mention doveras
    
*   ads used in amazon listings + product image carousel