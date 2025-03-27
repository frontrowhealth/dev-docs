# 🩺 Adding Doctor Reviews to Your Shopify Store

Follow the steps below to embed doctor reviews on your storefront using our custom Shopify snippet.

---

## 1. Access Your Shopify Theme Code

1. Log in to your [Shopify Admin](https://shopify.com).
2. Navigate to **Online Store > Themes**.
3. Find your **staging theme**, click the **three-dot icon**, and select **Edit Code**.

---

## 2. Create the Snippet File

1. In the **code editor**, go to the **Snippets** folder.
2. Click **Add a new snippet** and name it:

   ```
   frontrow-doctor-reviews.liquid
   ```

---

## 3. Add the Doctor Reviews Code

1. Open the provided `doctor-reviews.liquid` file. Contact your Solutions Engineer if you do not have this file.
2. Copy its contents.
3. Paste the content into your newly created `frontrow-doctor-reviews.liquid` snippet.

---

## 4. Insert the Snippet Into Your Theme

To render the doctor reviews on your product page:

1. Open the Liquid file where your **customer reviews section** appears (e.g., `product.liquid` or `main-product.liquid`).
2. Add the following line **above** your existing customer reviews section:


   {% render 'frontrow-doctor-reviews' %}
   ```

---

## 💡 Alternative: Using the Visual Editor

If your theme supports **custom Liquid blocks** in the Shopify visual editor:

1. Open the product page template in the **theme customizer**.
2. Add a **custom Liquid block** where you want the doctor reviews to appear.
3. Paste the same line:


   {% render 'frontrow-doctor-reviews' %}
   ```

---

## 5. Save and Preview

- Save all changes.
- Use the **Preview** button to confirm the doctor reviews appear correctly on your product page.
