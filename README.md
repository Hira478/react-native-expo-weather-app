## Setup

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. **Install dependencies:**
   ```
   npm install
   ```
3. **Set up environment variables:**
   ```
   - Copy the .env.example file to .env:
   cp .env.example .env
   - Open the .env file and add your API key and base URL:
   API_KEY=your_api_key_here
   BASE_URL=your_base_url_here
   ```
4. **Run the app:**
   ```
   npm run start
   ```
5. **Using the Environment Variables in Code**

   ```
   // src/constant.js
   import { config } from 'dotenv';
   config();

   export const API_KEY = process.env.API_KEY;
   export const BASE_URL = process.env.BASE_URL;
   ```
