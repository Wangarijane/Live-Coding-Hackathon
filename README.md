# Loyalty Rewards Management System

A comprehensive loyalty rewards platform designed for local businesses like salons, barbershops, and eateries. Track customer visits, manage rewards, and boost customer retention with automated notifications.

![Dashboard Preview](https://images.pexels.com/photos/7681078/pexels-photo-7681078.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2)

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

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

For support, email support@example.com or join our Slack channel.

## Acknowledgments

- [Tailwind CSS](https://tailwindcss.com)
- [React](https://reactjs.org)
- [Supabase](https://supabase.com)
- [Lucide Icons](https://lucide.dev)