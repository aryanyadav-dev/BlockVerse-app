# Web 3.0 Application

## Overview

This project is a Web 3.0 application developed using Next.js, integrating various technologies for a modern and decentralized user experience. The application utilizes styled-components for styling, Metamask for authentication, Thirdweb SDK for creating and minting cryptocurrency tokens, and Sanity.io with GROQ for data storage and retrieval. It includes functionality for sending and receiving tokens on the blockchain.

## Features

- **User Authentication:** Integrated with Metamask for seamless blockchain authentication.
- **Token Creation and Minting:** Utilizes Thirdweb SDK for creating and minting cryptocurrency tokens.
- **Token Transactions:** Allows users to send and receive tokens on the blockchain.
- **Data Storage:** Uses Sanity.io with GROQ for efficient data storage and retrieval.
- **Responsive Design:** Styled using styled-components to ensure a modern and responsive user interface.

## Technologies Used

- **Next.js:** Framework for building server-side rendered React applications.
- **Styled-Components:** Library for styling React components with tagged template literals.
- **Metamask:** Browser extension for managing blockchain accounts and signing transactions.
- **Thirdweb SDK:** Tools and SDK for interacting with blockchain networks, creating, and minting tokens.
- **Sanity.io:** Headless CMS for structured content management.
- **GROQ:** Query language for querying data from Sanity.io.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Set up environment variables:**

    Create a `.env.local` file in the root of the project and add the following environment variables:

    ```plaintext
    NEXT_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
    NEXT_PUBLIC_SANITY_DATASET=your_sanity_dataset
    NEXT_PUBLIC_THIRDWEB_CONTRACT_ADDRESS=your_thirdweb_contract_address
    ```

4. **Run the development server:**

    ```bash
    npm run dev
    ```

    Navigate to `http://localhost:3000` in your browser to view the application.

## Usage

1. **Authentication:**
   - Ensure you have Metamask installed and set up in your browser.
   - Connect your wallet to the application via the Metamask authentication flow.

2. **Token Functionality:**
   - **Create Token:** Use the provided UI to create and mint new tokens.
   - **Send/Receive Tokens:** Use the token send/receive functionalities to interact with the blockchain.

3. **Data Management:**
   - Data is managed via Sanity.io, allowing for dynamic content retrieval and updates.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Styled-Components](https://styled-components.com/)
- [Metamask](https://metamask.io/)
- [Thirdweb SDK](https://thirdweb.com/)
- [Sanity.io](https://www.sanity.io/)
- [GROQ](https://www.sanity.io/docs/groq)

---

Feel free to customize this README according to your project specifics and personal preferences!
