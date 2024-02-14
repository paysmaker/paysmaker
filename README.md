# Paysmaker: Integrate Web3 with Telegram

## Overview
**Paysmaker** is an innovative solution designed to seamlessly integrate Web3 functionalities into the Telegram native app. This repository provides the necessary tools and documentation for projects looking to incorporate decentralized finance, smart contracts, and other Web3 components into their Telegram-based applications.

## Features
- **Direct Integration with Telegram**: Enables Web3 functionalities within the Telegram app, enhancing user experience.
- **Smart Contract Interaction**: Facilitates communication with various smart contracts directly from Telegram chats.
- **Crypto Payments**: Supports cryptocurrency transactions, allowing users to send and receive payments through Telegram.
- **User-Friendly Interface**: Designed with simplicity in mind, ensuring ease of use for both developers and end-users.

   ## Installation
   To get started with Paysmaker, follow these steps:

   1. Install the required dependencies:

      ```
      npm i paysmaker
      ```

   ## Usage
   After installation, you can integrate Paysmaker into your project by following  these steps:

   1. Add the Provide to the ```_app.js``` page:

      ```
      import { PaysmakerProvider } from "paysmaker";

      function MyApp({ Component, pageProps }) {
   
      ...
            <PaysmakerProvider paysmakerKey={key} >
                  <Component {...pageProps} />
            </PaysmakerProvider >
      ...

      ```

   2. You can aquire the ```key``` by registering an account on [Paysmaker Website](https://app.paysmaker.com).


   3. In your homepage you can add the button to allow users to access their wallet.

   ```
      import{ Button } from "paysmaker";

      function Page() {
   
      ...
         <Button
            theme={"dark"}
            image="https://app.paysmaker.com/logo-small.png"
         />
      ...

      ```


   Refer to our [documentation](https://doc.paysmaker.com) for detailed usage instructions.

   ## License
   This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

