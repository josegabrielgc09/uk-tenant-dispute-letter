# 🏛️ UK Tenant Legal Dispute Letter Generator (Micro-SaaS)

An AI-powered legal assistance tool designed for international tenants in the United Kingdom facing housing issues (unlawful deposit deductions, unaddressed damp/mould, broken heating, or repair neglect).

Users can describe their dispute in their native language, and the application instantly drafts a formal, legally assertive dispute letter in British English adhering to statutory standards (Housing Act 2004, Section 11 of Landlord and Tenant Act 1985, Tenant Fees Act 2019, and Homes Fitness for Human Habitation Act 2018).

---

## 🚀 Live Demo
🔗 **Try the Application:** [https://josegabrielgc09.github.io/uk-tenant-dispute-letter/](https://josegabrielgc09.github.io/uk-tenant-dispute-letter/)

---

## ✨ Key Features
- **10+ Supported Languages:** Full UI localization and translation support for key tenant communities (Spanish, Polish, Romanian, Portuguese, Italian, French, German, Bulgarian, Lithuanian, and Ukrainian).
- **Domain-Specific Legal Prompting:** Automatically selects statutory references based on the issue category to create court-ready *Letters Before Action*.
- **Client-Side Privacy:** Zero server data retention. The Gemini API key and dispute drafts remain local to the user's browser via secure `localStorage`.
- **Integrated Micro-SaaS Monetization:** Built-in Stripe Checkout integration (£2.99) with automatic client-side PDF document generation (`html2pdf.js`).

---

## 🛠️ Tech Stack & Architecture
- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6+)
- **LLM Engine:** Google Gemini API (`gemini-3.8-flash`)
- **Payments:** Stripe Payment Links & Checkout
- **Document Rendering:** `html2pdf.js` client-side A4 compilation
- **Hosting:** GitHub Pages (Serverless static deployment)

---

## 💻 Local Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/josegabrielgc09/uk-tenant-dispute-letter.git](https://github.com/josegabrielgc09/uk-tenant-dispute-letter.git)