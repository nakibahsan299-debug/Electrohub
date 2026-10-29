# ⚡ ElectroHub

**An electronic product selling website**

ElectroHub is an e-commerce web application for buying and selling electronic products such as laptops, smartphones, cameras, gadgets and accessories. Customers can browse products, add them to a cart and pay securely online, while admins manage the catalog, orders and customer communication from a dedicated dashboard.

> Developed as the **CSE 3200 – System Development Project** at the Department of Computer Science and Engineering, **Khulna University of Engineering & Technology (KUET)**.

---

## 🎯 Objectives

- Enable online sales of electronic products
- Reach a wider customer base beyond physical locations
- Increase brand awareness and recognition
- Provide 24/7 shopping convenience
- Offer detailed product information

## ✨ Features

### 🛍️ Customer side
- Homepage with product highlights
- User registration, login and authentication
- Browse all products and all categories
- Product details page
- Add to cart and manage the cart
- Order summary with **secure Stripe payment**
- Order details and order history
- **Live chat with admin**

### 🛠️ Admin side
- Admin dashboard
- Add and manage categories
- Add, view, update and delete products
- Manage orders
- Send **order confirmation SMS** to customers

## 🧰 Tech Stack and Integrations

| Purpose | Technology |
|---|---|
| Backend framework | Laravel 10 |
| Payments | Stripe payment gateway |
| Live chat | Tawk.to |
| SMS notifications | Twilio |
| Development model | Waterfall |

## 🚀 Getting Started

```bash
# 1. Clone the repository
git clone <your-repository-url>
cd electrohub

# 2. Install dependencies
composer install

# 3. Configure the environment
cp .env.example .env
php artisan key:generate

# 4. Set your database, Stripe, Twilio and Tawk.to credentials in .env

# 5. Run migrations and start the server
php artisan migrate
php artisan serve
```

## 🔮 Future Scope

- Precise order tracking system
- Own payment gateway
- Product recommendation system using machine learning
- Product reviews

## 👥 Team

| Name | Roll |
|---|---|
| Syed Nafisur Rahman Shuvro | 1907064 |
| Nakib Ahsan | 1907086 |

**Supervised by:** Md. Abdus Salim Mollah, Assistant Professor, Department of CSE, KUET

## 📚 References

- [Stripe Dashboard](https://dashboard.stripe.com/test/payments)
- [Tawk.to Dashboard](https://dashboard.tawk.to/#/chat)
- [Twilio](https://www.twilio.com/en-us)
- [Laravel 10.x Documentation](https://laravel.com/docs/10.x/installation)
