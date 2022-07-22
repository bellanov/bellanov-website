# bellanov-llc

Example of **Vue 3** and **Bootstrap 5** integration. No more **jQuery**!!!

**Environments:**

[Dev](https://bellanov-llc-dev-iuj6vc72wa-uc.a.run.app/)
[QA](https://bellanov-llc-qa-7td3j4wmyq-uc.a.run.app/)
[Prod](https://bellanov-llc-prod-6gpfnq26tq-uc.a.run.app/)

The deployment is managed via Terraform in [bellanov-llc-state](https://github.com/bellanov/bellanov-llc-state).

## Workflow

Project **building**, **testing**, and **deployment** information.

```sh
# Install dependencies
yarn install

# Compiles and hot-reloads for development
yarn serve

# Compiles and minifies for production
yarn build

# Lints and fixes files
yarn lint

# Build and execute Docker container
docker build -t bellanov-llc:local -f Dockerfile .
docker run -it -p 8080:80 bellanov-llc:local
```

Access the application at `localhost:8080`
