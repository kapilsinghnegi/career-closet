# Career Closet

Career Closet is a community-driven platform where professionals can **lend and borrow interview outfits**, helping job seekers feel confident without the financial burden of buying formal clothing.

Originally built during the [**Spring 2026 cohort project**](https://github.com/NHCarrigan-Spring-Cohort-2026-Archive/mint-narcissus), this repository is now being actively maintained and improved.

![GitHub contributors](https://img.shields.io/github/contributors/kapilsinghnegi/career-closet)
![GitHub stars](https://img.shields.io/github/stars/kapilsinghnegi/career-closet)
![GitHub forks](https://img.shields.io/github/forks/kapilsinghnegi/career-closet)

---

## Project Vision

Job interviews are stressful enough without worrying about whether you have the right clothes.

Career Closet connects:

- People who need interview outfits
- Professionals willing to lend or donate clothing
- The focus is dignity and confidence — not charity.

Think of it as: “Borrow my lucky blazer.”

## Features

### Borrower

- Browse available interview outfits
- Filter by category, size, fit, and interview type)
- Save outfits
- View detailed outfit information
- Send borrow requests
- Track request status in My Requests

### Lender

- List outfits to share
- Manage listed outfits
- Update outfit availability
- Approve or decline borrow requests
- Track borrowed outfits

---

## Tech Stack

### Frontend

- React
- Redux Toolkit
- React Router
- Tailwind CSS
- ShadCN UI

### Backend

Microservice architecture using Node.js.

Current services include:

- Auth Service
- User Service
- Outfit Service
- Request Service

### Tools

- Docker
- Node.js
- REST APIs

---

## Repository Structure

```bash
career-closet
│
├── Backend
│ └── services
│ │ ├── auth-service
│ │ ├── gateway
│ │ ├── items-service
│ │ ├── messaging-service
│ │ └── requests-service
│ │
│ └── shared
│ │ └── logger
│ │
│ └── docker-compose.yml
│
├── Frontend
│ ├── src
│ │ ├── api
│ │ ├── components
│ │ ├── pages
│ │ ├── layouts
│ │ ├── store
│ │ └── utils
│ │
│ └── public
│
├── .github
│ └── PULL_REQUEST_TEMPLATE.md
│
└── README.md
```

---

## Getting Started

### Clone the repository

```bash
git clone https://github.com/kapilsinghnegi/career-closet.git
cd career-closet
```

### Install frontend dependencies and run frontend

```bash
cd Frontend
npm install
npm run dev
```

### Run Backend Services

```bash
cd Backend
docker compose up
```

## Contributing

All contributors must follow the agreed workflow.

Before making changes, please read: [**CONTRIBUTING.md**](CONTRIBUTING.md)

---

## Contributors

Thanks to everyone who contributed to this project.

[![Contributors](https://contrib.rocks/image?repo=kapilsinghnegi/career-closet)](https://github.com/kapilsinghnegi/career-closet/graphs/contributors)

---

## Code of Conduct

We are a global, collaborative team and expect respectful, inclusive behavior from everyone.

Please read: [**CODE_OF_CONDUCT.md**](CODE_OF_CONDUCT.md)
