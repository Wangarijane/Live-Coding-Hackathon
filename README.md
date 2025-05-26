# Loyalty Rewards Management System

A comprehensive loyalty rewards platform designed for local businesses like salons, barbershops, and eateries. Track customer visits, manage rewards, and boost customer retention with automated notifications.

## 🔗 Live Demo 

https://profound-tartufo-44eb4f.netlify.app/

## Prompts Used

"Claude, write a detailed and modular prompt for Bolt.new that will guide it to build a Loyalty Rewards App for local salons, barbershops, and eateries. Here’s what I want it to include:
1️⃣ Database Setup:
* A Customers table with fields: id, phone_number, visit_count, last_visit_date, reward_status.
* A Rewards table with fields: id, customer_id, reward_type, reward_message, issued_date.
2️⃣ Backend Logic:
* Workflow to add a new visit when a customer’s phone number is entered.
* Increment visit_count by 1 and update last_visit_date.
* Check if the visit_count matches a reward threshold (e.g., 5 visits). If yes, create a record in the Rewards table and prepare a reward message.
* Optional: Allow configurable reward tiers (e.g., 5 visits = 10% discount, 10 visits = free service).
3️⃣ Notification Integration:
* Integrate with Twilio or WhatsApp Cloud API to send the reward message (e.g., ‘Congrats! You’ve earned a 10% discount.’).
* Allow fallback to email or in-app notification if phone number is invalid.
4️⃣ Frontend Design:
* Create a simple, mobile-friendly web app interface.
* Include a dashboard for the business owner showing total customers, visit counts, rewards issued.
* Allow searching customers by phone number and viewing their reward history.
* Provide error handling and success confirmations for each action.
5️⃣ Security & Scalability:
* Ensure secure handling of phone numbers and rewards.
* Design with modular workflows for easy updates (e.g., adding new reward types or analytics).
Output a clear, complete prompt I can paste into Bolt.new to automatically build this app, with tables, workflows, and API integrations specified.
Also suggest AI-generated reward messages (e.g., ‘Thank you for your loyalty!’) for the SMS or WhatsApp notifications."

## Features

- 📱 **Customer Management**
  - Track visits and spending
  - Search by phone number
  - View detailed customer profiles
  - Monitor visit history

- 🎁 **Rewards System**
  - Configurable reward tiers
  - Automatic reward triggers
  - Multiple reward types
  - Digital reward tracking

- 📊 **Business Analytics**
  - Real-time dashboard
  - Visit trends
  - Revenue insights
  - Reward redemption tracking

- 📨 **Multi-channel Notifications**
  - SMS notifications
  - WhatsApp messages
  - Email communications
  - Customizable templates

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/loyalty-rewards-system.git
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   ```bash
   cp .env.example .env
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a `.env` file with the following variables:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **State Management**: React Context
- **Database**: Supabase
- **Charts**: Recharts
- **Forms**: React Hook Form
- **Icons**: Lucide React
- **Notifications**: React Hot Toast

## Core Features

### Visit Recording
- Quick customer lookup by phone number
- Automatic new customer registration
- Visit amount tracking
- Instant reward notifications

### Reward Management
- Configurable reward tiers
- Multiple reward types:
  - Percentage discounts
  - Free services
  - Milestone celebrations
  - Return encouragement rewards
- Digital reward tracking and redemption

### Customer Insights
- Visit history timeline
- Spending patterns
- Reward status tracking
- Communication preferences

### Business Analytics
- Daily/weekly/monthly trends
- Revenue tracking
- Customer retention metrics
- Reward program impact

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com)
- [React](https://reactjs.org)
- [Supabase](https://supabase.com)
- [Lucide Icons](https://lucide.dev)
- [Claude AI](https://claude.ai)
- [Bolt.new](https://bolt.new)
