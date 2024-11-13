Eco Mint - NFT Art Marketplace


Eco Mint is a blockchain-powered NFT marketplace dedicated to showcasing unique, curated digital art. Designed to empower artists, Eco Mint provides a transparent, secure platform where artists can sell their work, retain ownership rights, and receive fair compensation, including royalties on secondary sales.


Features
NFT Minting and Sales: Artists can mint unique NFTs of their artwork and list them for sale, receiving full payment directly.
Royalties on Secondary Sales: Smart contracts enforce royalty payments on all resales, providing continuous revenue to the artist.
Transparent Ownership History: Blockchain technology ensures a secure and transparent transaction record, allowing buyers to verify the origin and ownership of each NFT.
Decentralized Storage: Art metadata and assets are stored on IPFS, preserving the integrity of the artwork.


echnologies Used
Frontend
React 18 with TypeScript for a robust, responsive user interface.
Vite as the build tool for fast development and optimized builds.
Tailwind CSS for styling, creating a clean, modern look.
React Router for seamless client-side navigation.
Web3 Integration
Web3-React v8 for wallet connection, enabling users to interact with their crypto wallets.
MetaMask as the primary wallet connector.
Ethers.js v6 for Ethereum blockchain interaction, including transactions and smart contract functions.
Storage
IPFS HTTP Client for decentralized storage, ensuring artwork and metadata are secure and accessible.
UI Components
Lucide React for icons, providing a cohesive visual style.
Custom Glass-morphism Design System to create a visually appealing, modern UI.
Responsive Grid Layouts for an adaptive experience across all devices.
Animated Transitions and Loading States for a seamless user experience.
Development Tools
TypeScript for type safety.
ESLint for code quality.
PostCSS and Autoprefixer for CSS processing and cross-browser compatibility.
Architecture
Frontend: Built with React and TypeScript, the frontend handles user interactions and displays content dynamically based on blockchain data.
Blockchain: Smart contracts on the Ethereum blockchain manage NFTs and enforce royalties, utilizing Ethers.js for communication between the application and Ethereum.
Decentralized Storage: IPFS stores art assets and metadata, ensuring permanence and security.
Wallet Integration: Web3-React and MetaMask provide seamless wallet connections, allowing users to securely interact with the marketplace.

Folder Structure

eco-mint/
├── public/                # Static files
├── src/
│   ├── assets/            # Images, fonts, etc.
│   ├── components/        # Reusable React components
│   ├── contexts/          # Context API for managing global state
│   ├── hooks/             # Custom hooks
│   ├── pages/             # Pages in the application
│   ├── services/          # API and blockchain interaction logic
│   ├── styles/            # Global styles, Tailwind configurations
│   ├── App.tsx            # Main app component
│   └── index.tsx          # Application entry point
└── .env                   # Environment variables
└── README.md

