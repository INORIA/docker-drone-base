# docker-drone-base

1. Copy .env.example as .env
2. Create github OAuth Apps from https://github.com/settings/developers
3. Fill in .env file
  a. DRONE\_GITHUB\_CLIENT is Client ID
  b. DRONE\_GITHUB\_SECRET is Client Secret
  c. DRONE\_SECRET is a random string
4. Add drone.sqlite (if you have)
5. `docker-compose up -d`

