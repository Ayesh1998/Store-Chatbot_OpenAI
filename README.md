# Frontend

## How to run the frontend locally

- First clone the code
- Then open command prompt inside the cloned code
- Run "npm install" in command prompt
- Add reqruired values to .env variables as below in .env variables.
- Then run "npm start"
- Then use http://localhost:3000/

## Hosted URL

- Hosted Link - https://bookstore-chatbot-beryl.vercel.app/

## Project Structure

- This is a NextJs project and used tailwind css for styling and used OpenAI ChatGPT for chat bot..
- And used Atomic Architecture.
- Root directory files
  - .env
  - package.json
  - jest.config.js and jest.setup.js(for jest configuration)
  - next.config.js (next configurations)
  - tailwind.config.js (tailwin configurations)
  - tsconfig.json (types configurations)
  - public (assets which can asses from anywhere in the project)

##

- And all the other project files are inside src directory
  - src/app/api directory has files for backend api calling.
  - src/components directory has all the UI components.
  - src/app directory has all the routings.
  - src/context directory has context configuration.
  - src/lib directory has validation files and other util files.

## .env Variables

- OPENAI_API_KEY - OpenAI API key
- REDIS_URL - Redis database URL
- REDIS_SECRET - Redis secrete key
