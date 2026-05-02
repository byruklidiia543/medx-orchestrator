# MedX - Blockchain Supply Chain Management

A blockchain-based supply chain management system built with Next.js, MongoDB, and Web3 technologies.

## Features

- Role-based Access Control
- Inventory Management
- Supply Chain Tracking
- Real-time Updates
- Blockchain Verification

## Tech Stack

- **Frontend:** Next.js 14, React 18, TailwindCSS
- **Backend:** Next.js API Routes
- **Database:** MongoDB Atlas
- **Blockchain:** Ethereum (Web3)

## Prerequisites

- Node.js 18+ 
- MongoDB Atlas Account
- MetaMask or any Web3 Wallet
- Yarn/NPM

![Screenshot](/theme/images/home.png)
![Screenshot](/theme/images/dash.png)

## Environment Variables

Create a `.env.local` file in the root directory with the following variables:

## Installation

1. Clone the repository:
```bash
git clone https://github.com/byruklidiia543/medx-orchestrator.git
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
```

4. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Deployment

The project is set up to be deployed on Vercel:

1. Push your code to GitHub
2. Import your repository to Vercel
3. Add environment variables in Vercel project settings
4. Deploy!

## Project Structure

```
medx/
├── app/                    # Next.js 14 app directory
│   ├── api/               # API routes
│   ├── auth/              # Authentication pages
│   └── dashboard/         # Dashboard pages
├── components/            # React components
├── context/              # React context providers
├── lib/                  # Utility functions and configurations
└── public/              # Static files
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


