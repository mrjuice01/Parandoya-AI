<p align="center">
  <img alt="Web client demo" src="./demos/client.png?v=3">
</p>

# PandoraAI

PandoraAI is a web chat client powered by [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api), allowing users to easily chat with multiple AI systems while also offering support for custom presets. With its seamless and convenient design, PandoraAI provides an engaging conversational AI experience.

Built using [Nuxt 3](https://v3.nuxtjs.org/), a Vue 3 framework.  
You may also use PandoraAI with other API server implementations as long as the endpoints are compatible.

## Features

- Chat with all the AI that `node-chatgpt-api` supports, including `gpt-3.5-turbo`, `text-davinci-003`, ChatGPT, and Bing.
- Supports creating multiple presets for each client.  
![Client Settings](demos/client-settings.png) 
- Choose between different clients or custom presets.  
![Client Dropdown](demos/client-dropdown.png)
- Everything is stored in local storage, so you can use this client without an account, and it can be imported or exported to other devices.

<details>
<summary><strong>Nuxt 3 Setup</strong></summary>

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

## Setup

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.
</details>

## Setup

1. Follow the Nuxt 3 setup instructions above.
2. Run the API server from [node-chatgpt-api](https://github.com/waylaidwanderer/node-chatgpt-api#api-server).
3. Copy `.env.example` to `.env` and fill in the `API_BASE_URL` variable with the URL of the API server.
4. Run `npm run dev` to start the development server, or `npm run build` to build the application for production.
   1. If you see an empty white page after pulling the latest changes, run `nuxi upgrade --force` first and then `npm run dev`.

## Contributing
If you'd like to contribute to this project, please create a pull request with a detailed description of your changes.

## License
This project is licensed under the MIT License.


 ***
## Support <img src="https://user-images.githubusercontent.com/64035221/113476039-61b21c80-9496-11eb-93d1-97a97f6acaa6.png" width="30" height="30">

<table align="center" style="border:1px solid black;margin-left:auto;margin-right:auto;">
  <tr>
    <th><img src="https://user-images.githubusercontent.com/100421286/272568945-0cb5c1cb-b544-4287-962b-cf5ebab61d3d.jpg" width="100%" height="100%"></th>
  </tr>
  <tr>
    <td><a href="https://github.com/mrjuice01/"><p align='center'><b>Mr Juice</b></td>
  </tr>
  <tr>
    <td><p align='center'><b>Author</b></td>
  </tr>
</table>

<p align="center"><a href="https://github.com/mrjuice01"><img src="https://user-images.githubusercontent.com/64035221/96459220-834c7e00-123f-11eb-8417-534058a7ba62.png" alt="GitHub" width="80" height="80">
<a href="https://www.youtube.com/@mrjuiceofc"><img src="https://user-images.githubusercontent.com/64035221/96456596-4f238e00-123c-11eb-821e-85e9aaa3faec.png" alt="YouTube" width="80" height="80">
<a href="https://t.me/DeveloperJuice"><img src="https://user-images.githubusercontent.com/64035221/113977119-b91e0700-985f-11eb-9418-eab91ff1540e.png" alt="Telegram" width="80" height="">
<a href="https://www.instagram.com/mr_juice7/"><img src="https://user-images.githubusercontent.com/64035221/113977904-e61ee980-9860-11eb-82d1-9ebd795c8138.png" alt="Instagram" width="80" height="">
