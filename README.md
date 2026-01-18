# 🇮🇳 Manufacture India  
## Global Manufacturing Order & Quotation Platform



![Logistics](image-1.png)


> A startup platform that allows global customers to place manufacturing requests and enables Indian manufacturers to competitively bid, accept, and fulfill orders through a transparent digital workflow.

---

## 🚀 One-Line Pitch

**Manufacture India** connects global demand with Indian manufacturing supply using a quotation-based, category-driven dispatch system — similar in intelligence to ride-hailing platforms, but designed for large-scale manufacturing.

---

## 🌍 The Core Idea (Simple Explanation)

A customer (for example, from the USA) wants to manufacture products in India.

Instead of contacting manufacturers manually:

1. The customer posts a manufacturing request  
2. Relevant Indian manufacturers are notified  
3. Manufacturers submit price quotations or reject  
4. The customer selects the best quote  
5. Manufacturing, quality checks, and logistics are tracked digitally  

![Global Trade](https://static.fibre2fashion.com/Newsresource/images/295/adobestock-654811286_306660.jpeg)

---

## 🧵 Manufacturer Grouping Logic

Manufacturers are **intelligently grouped** to avoid spam and improve relevance.

### Level 1: Industry Category
- Textile
- Metal Fabrication
- Plastics
- Electronics
- Furniture

### Level 2: Product Sub-Type (Example: Textile)
- Cotton garments
- Polyester garments
- Industrial fabrics
- Knitted fabrics

Only manufacturers matching **both category and sub-type** receive order notifications.

![Factory Floor](https://images.unsplash.com/photo-1503387762-592deb58ef4e)

---

## 📦 Order Dispatch (Rapido-like Model)

The platform works similarly to ride-hailing apps, but for manufacturing:

- Orders are sent in **waves** to nearby or best-matched manufacturers
- Manufacturers can **Bid** or **Reject**
- Rejection reasons help improve future matching

### Manufacturer Actions
- ✅ Bid with price + delivery time  
- ❌ Reject with reason (capacity, price, timeline)

![Bidding](https://images.unsplash.com/photo-1556761175-5973dc0f32e7)

---

## 🔄 End-to-End Order Flow

```text
Customer Posts Order
        ↓
Relevant Manufacturers Notified
        ↓
Manufacturers Bid / Reject
        ↓
Customer Selects Best Quote
        ↓
Manufacturing Starts
        ↓
Quality Check
        ↓
Logistics & Delivery
```

![Logistics](https://images.unsplash.com/photo-1601584115197-04ecc0da31d7)

---

## 🧠 User Experience Philosophy

Waiting is acceptable for manufacturing — **silence is not**.

### What the Customer Always Sees
- Number of manufacturers notified
- Bids received vs pending
- Expected quotation window
- Clear next step

This turns waiting time into **decision-making time**.

---

## 🛠️ Tech Stack

![Tech Stack](https://skillicons.dev/icons?i=react,nodejs,express,mongodb,docker,aws,graphql)

### Frontend
- React.js
- Tailwind CSS
- GSAP (animations)

### Backend
- Node.js
- Express.js
- GraphQL API

### Infrastructure
- Docker
- AWS (EC2, Load Balancer – planned)

---

## 🧩 Sample GraphQL Schema (Simplified)

```graphql
type OrderRequest {
  id: ID!
  category: String!
  subType: String!
  quantity: Int!
  basePrice: Float!
  status: String!
}

type Quote {
  id: ID!
  manufacturerId: ID!
  quotedPrice: Float!
  deliveryTime: String!
}
```

---

## ☁️ Deployment Overview

- Dockerized frontend and backend
- AWS EC2 for hosting
- Scalable for global usage
- Secure environment management

---

## 📈 Current Status

🟡 MVP in Active Development

- Core dispatch & bidding logic implemented
- Manufacturer and customer dashboards in progress
- Cloud deployment pipeline under setup

---

## 👨‍💻 Founder

**Prashanth**  
Founder & Full-Stack Developer  

- End-to-end product ownership  
- System design, backend architecture, frontend development  

---

## 🏁 Vision


> Build the digital backbone that makes Indian manufacturing globally accessible, competitive, and trusted.

![Manufacturing Banner](![alt text](image-2.png))