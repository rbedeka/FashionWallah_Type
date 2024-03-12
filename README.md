# Fashionwallah.in

## How to start?

### Step 1: Installing Required packages

#### Visit the [official site of nodejs](__https://nodejs.org/en/download__) and install latest Node recommended version above 18.0.0

### Step 2: Installing required node packages\*\*

#### Run the following command in the root directory of your project, this will install all the required dependencies.

```bash
npm i
```

### Step 3: Running the project in the developer mode

#### Run the following command in the root directory of your project to run the project in the developer mode or test mode to see the preview of your project

```bash
npm run dev
```

### Step 4: Running the project in the production mode

#### Run the following command in the root directory of your project to run the project in the production mode that means instead of above command you will use this command to run your project on the server

```bash
npm run build
```

### after running your project it will give you the localhost url where your project is running like

### http://localhost:3000

### Go to the url and run your project.

####

## Following is the directory structure of the project

```plaintext
.
├── public/              # Public assets (images, fonts, etc.)
├── app/                 # Source code
│   ├── components/      # React components
│   ├── routes/          # Remix routes
│   ├── styles/          # CSS or styling files
│   ├── utils/           # Utility functions
│   ├── graphql/         # GraphQl Queries
│   ├── hooks/           # Custom react hooks
│   ├── lib/             # Custom libraries for general purposes
│   ├── root.tsx         # Entry point for the app
├── .gitignore           # Git ignore file
├── package.json         # Project configuration contains dependencies (react/scripts, shopify/hydrogen, etc.)
├── README.md            # Project documentation
├── tsconfig.json        # TypeScript configuration
├── package.json         # Project configuration
└── tailwind.config.json # Tailwind configuration
```

# .env

### .env file contains the credentials for shopify api like

### SESSION_SECRET

### PUBLIC_STOREFRONT_API_TOKEN

### PRIVATE_STOREFRONT_API_TOKEN

### PUBLIC_CUSTOMER_ACCOUNT_API_CLIENT_ID

### PUBLIC_CUSTOMER_ACCOUNT_API_URL

## How to check if there are errors in the files

You can run the following command which lists the errors in the project files and the total number of errors in the project.

```bash
npm run typecheck
```
