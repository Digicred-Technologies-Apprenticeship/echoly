# Echoly — API Endpoints

## Auth
- `POST /api/auth/register` — Register a new user
- `POST /api/auth/login` — Log in an existing user

## Companies
- `POST /api/companies` — Add a company
- `GET /api/companies/:id` — Get a company's details
- `GET /api/companies/:id/geo-score` — Get the company's GEO score

## Competitors
- `POST /api/companies/:id/competitors` — Add a competitor
- `GET /api/companies/:id/competitors` — List a company's competitors

## Prompts
- `POST /api/prompts` — Add a new prompt
- `GET /api/prompts` — List prompts
- `POST /api/prompts/:id/run` — Run a prompt across AI engines

## Echoes (Results)
- `GET /api/prompts/:id/echoes` — Get all echoes for a prompt
- `GET /api/echoes/:id` — Get a single echo
