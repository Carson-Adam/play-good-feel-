# Golf Ball Store Website

This is a simple 3-page static website to sell golf balls from brands Titleist, TaylorMade, Callaway, and Titleist Pro V1.

---

## Features

- **Product page** (`index.html`):  
  Displays golf ball products with quantity options (12 or 24 packs) and prices. Users can add items to the cart.

- **Cart page** (`cart.html`):  
  Shows all added items with quantity, price per pack, subtotal, and total price. Users can remove items and proceed to checkout.

- **Checkout page** (`checkout.html`):  
  Shows order summary and redirects users to PayPal for payment with the total amount charged to the PayPal account `adamtfig54@icloud.com`.

---

## How to use

1. Open `index.html` in a modern browser.
2. Select product quantities and click **Add to Cart**.
3. Click **View Cart** to review your items.
4. Remove items if needed or proceed to checkout.
5. On checkout, click the PayPal button to pay securely.

---

## Technical Details

- Cart data is saved in `localStorage` on the browser.
- Uses basic HTML, CSS, and JavaScript — no backend required.
- PayPal integration uses simple redirect to PayPal payment URL with your PayPal email.
- Product images use free stock photos from Pixabay.

---

## Notes

- This site does **not** have a backend or database — all cart and order data is stored locally.
- After payment, cart is **not** automatically cleared (requires backend/webhook for full flow).
- For real-world use, consider adding server-side order management and security.

---

## Author

Developed for [Your Name] by ChatGPT on OpenAI.

---

## License

MIT License (free to use and modify)
