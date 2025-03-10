# E-commerce Template for Payload

This is an e-commerce template built with Payload CMS, Next.js, and Stripe. It provides a robust foundation for building an online store with a modern tech stack.

## Features

- **Payload CMS**: Headless CMS for managing content.
- **Next.js**: React framework for server-side rendering and static site generation
- **Stripe**: Payment processing integration.
- **MongoDB**: Database for storing data.
- **SEO**: Built-in SEO features.
- **Cloud Storage**: Integration with cloud storage providers.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- Yarn package manager
- MongoDB instance
- Stripe account

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/ecommerce-template.git
    cd ecommerce-template
    ```

2. Install dependencies:
    ```bash
    yarn install
    ```

3. Create a `.env` file in the root directory and add your environment variables:
    ```env
        Payload vars
        PORT=3000
        DATABASE_URI=mongodb://127.0.0.1/payload-template-ecommerce
        PAYLOAD_SECRET=712kjbkuh87234sflj98713b
        PAYLOAD_PUBLIC_SERVER_URL=http://localhost:3000
        STRIPE_SECRET_KEY=
        PAYLOAD_PUBLIC_STRIPE_IS_TEST_KEY=true
        STRIPE_WEBHOOKS_SIGNING_SECRET=
        PAYLOAD_PUBLIC_DRAFT_SECRET=demo-draft-secret
        REVALIDATION_KEY=demo-revalation-key

        Next.js vars
        NEXT_PUBLIC_SERVER_URL=http://localhost:3000
        NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=
        NEXT_PUBLIC_IS_LIVE=
        NEXT_PRIVATE_DRAFT_SECRET=demo-draft-secret
        NEXT_PRIVATE_REVALIDATION_KEY=demo-revalation-key
    ```

### Development

To start the development server, run:
```bash
yarn dev
```

### Building for Production

To build the application for production, run:
```bash
yarn build
```

To serve the built application, run:
```bash
yarn serve
```

### Seeding the Database

To seed the database with initial data, run:
```bash
yarn seed
```

### Stripe Webhooks

To listen for Stripe webhooks, run:
```bash
yarn stripe:webhooks
```

## Scripts

- `dev`: Start the development server.
- `build`: Build the application for production.
- `serve`: Serve the built application.
- `seed`: Seed the database with initial data.
- `stripe:webhooks`: Listen for Stripe webhooks.
- `lint`: Lint the codebase.
- `lint:fix`: Fix linting issues.

## License

This project is licensed under the MIT License.
