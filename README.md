# Droame UI

## Getting started

1. **Clone this repository**

   ```bash
   git clone https://github.com/drone/drone-ui.git
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Copy .env.example and rename it into .env**

   ```bash
   cp .env.example .env.development.local
   ```

4. **Fill required variables. For example:**

   ```text
   REACT_APP_DRONE_SERVER=https://drone.company.com
   REACT_APP_DRONE_TOKEN=<your_drone_token> // find your token in your Drone account settings (click your Avatar in the UI).
   ```

### Run the app in development mode, with hot reloading

```bash
npm run start
```

### Build the app

```bash
npm run build
```

### Run the built app

```bash
npm run serve
```

### Run linters

```bash
npm run lint
```

### Run linters and fix auto fixable problems

```bash
npm run lint:fix
```

### Run your tests

```bash
npm run test
```

