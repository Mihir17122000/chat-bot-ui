# Next.js Chatbot Project

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

### Running Locally

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using npm, yarn, pnpm, or bun:

```bash
npm install
# or
yarn install
# or
pnpm install
# or
bun install
```


# ChatBot README

## Description
This is a simple chatbot script programmed to respond to various user inputs with predefined messages. It uses a set of key-value pairs to match user queries to appropriate responses.

| Dark Chatbot Image | Light Chatbot Image |
|:------------------:|:-------------------:|
| ![Dark Chatbot Image](/public/dark-bot.png) | ![Light Chatbot Image](/public/light-bot.png) |


## Usage
The bot responds to specific user inputs with predefined messages. Here are the supported commands:

- **hello**: Responds with a greeting message: "Hi there! How can I help you?"
- **how are you**: Responds with a default message: "I'm just a bot, but thanks for asking!"
- **goodbye**: Responds with a farewell message: "Goodbye! Have a great day!"
- **thank you**: Responds with a gratitude message: "You're welcome!"
- **how can I help you**: Responds with a question: "What do you need assistance with?"
- **tell me a joke**: Currently unimplemented, will fetch a joke from an API
- **random fact**: Responds with a random fact: "Did you know that the shortest war in history lasted only 38 minutes?"
- **give me a random user data**: Currently unimplemented, will fetch random user data
- **give me a random post**: Currently unimplemented, will fetch a random post
- **quote of the day**: Currently unimplemented, will fetch quote of the day
- **cat fact**: Currently unimplemented, will fetch a cat fact
- **dog fact**: Currently unimplemented, will fetch a dog fact
- **default**: Responds with a default message if the input doesn't match any of the above commands: "Sorry, I didn't understand. Can you please clarify?"

## License
This project is licensed under the MIT License. See the LICENSE file for details.
