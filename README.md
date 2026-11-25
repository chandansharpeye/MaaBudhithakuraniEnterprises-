# Maa Budhi Thakurani Enterprises — GitHub Pages Storefront

Static mobile-accessories catalogue and quotation / order-request website for Maa Budhi Thakurani Enterprises, Brahmapur, Odisha.

## Included
- Existing product catalogue, categories, product details and product photos
- Mobile-friendly product browsing and cart
- Customer checkout details and UPI / Cash on Delivery preference
- UPI QR code and UPI ID: `7978137724@upi` (payee shown by the supplied QR: Master Swadhin Kumar Sahu)
- Printable quotation that customers can save as PDF
- WhatsApp order request containing customer details, products, quantities, address and quotation reference
- Owner-facing dispatch checklist included in the WhatsApp order message
- Owner manually confirms the order and sends dispatch / departure / expected delivery dates to the customer through WhatsApp
- Delivery charges confirmed by the owner

## Publish on GitHub Pages
1. Extract this ZIP.
2. Upload **both `index.html` and `upi-qr.jpg`** to the root of your GitHub repository.
3. Open repository Settings → Pages.
4. Choose deployment from your main branch and `/ (root)`, then save.
5. Open the published website and test the product cart, QR image, quotation and WhatsApp links.

## How the order flow works
1. Customer adds products to the cart and fills in delivery/contact details.
2. Website generates a quotation / order-request reference.
3. Customer chooses **Send order request to owner**. WhatsApp opens with the full order details and owner dispatch-list information prefilled; the customer must press Send.
4. Owner checks stock, price, GST, delivery charges and payment, then confirms the order manually.
5. Owner sends the dispatch date, departure date and expected delivery date to the customer in WhatsApp.
6. Customer can save the quotation as PDF and share it through WhatsApp.

## Important limitations
- This is a static website: no backend, database, Supabase, admin login or central order storage.
- Orders reach the owner only when the customer sends the prefilled WhatsApp message. The website cannot silently send WhatsApp messages.
- The owner dispatch list is delivered as a WhatsApp order message, not stored in a central dashboard or spreadsheet.
- A static website cannot automatically send a PDF from the business WhatsApp account to a customer's WhatsApp. The customer can save the quotation PDF and share it, or the owner can manually send it after confirmation.
- The generated document is a quotation / order request, NOT a tax invoice and NOT an accepted order.
- UPI QR is included, but customers must wait for the owner to confirm the final payable amount before paying. The owner verifies UPI payment manually. COD remains subject to owner confirmation.
- GST, delivery charges, stock, MOQ, product prices and policies must be confirmed by the owner before public launch.
- Cart data is stored only in the customer's browser; it is not shared across devices.

## Owner details shown in the source
- Phone / WhatsApp: `7978137724`
- Location: Brahmapur, Odisha, India
- Email: `swadhinkumarsahu1328960@gmail.com`

Confirm all business contact details, catalogue details, prices, GST treatment, stock, MOQ, policies and product photos with the owner before launch.
