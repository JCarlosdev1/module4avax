
## Assessment Smart Contract

### Overview

This is a Solidity smart contract named `Assessment` designed for financial assessments. It allows the owner to deposit and withdraw funds, check the balance, and buy items. The contract emits events for deposit, withdrawal, and item purchases.

### License

This project is licensed under the terms of the MIT license.

### Prerequisites

- [Solidity](https://docs.soliditylang.org/en/latest/)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd Assessment
   ```

### Usage

1. Deploy the contract to your preferred Ethereum network.
2. Interact with the deployed contract using a tool like [Remix](https://remix.ethereum.org/) or your preferred Ethereum development environment.

### Contract Details

- **Name:** Assessment
- **Version:** 1.0.0
- **Solidity Version:** ^0.8.9
- **License:** MIT

### Functions

- `getBalance()`: Retrieves the balance of the caller's account.
- `deposit(uint256 _amount)`: Allows the owner to deposit funds into the contract.
- `withdraw(uint256 _withdrawAmount)`: Allows the owner to withdraw funds from the contract.
- `buy(string memory _item)`: Allows anyone to buy items with sufficient balance.

### Events

- `Deposit(uint256 amount)`: Emitted when funds are deposited into the contract.
- `Withdraw(uint256 amount)`: Emitted when funds are withdrawn from the contract.
- `ItemBought(string item, uint256 price)`: Emitted when an item is successfully bought.

## DegenToken Smart Contract

### Overview

This is a Solidity smart contract named `DegenToken` that implements an ERC20 token called "Degen". It provides functionalities for minting, burning, transferring tokens, selling items, and buying items. The contract emits an event when an item is purchased.

### License

This project is licensed under the terms of the MIT license.

### Prerequisites

- [Solidity](https://docs.soliditylang.org/en/latest/)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd DegenToken
   ```

### Usage

1. Deploy the contract to your preferred Ethereum network.
2. Interact with the deployed contract using a tool like [Remix](https://remix.ethereum.org/) or your preferred Ethereum development environment.

### Contract Details

- **Name:** DegenToken
- **Version:** 1.0.0
- **Solidity Version:** ^0.8.18
- **License:** MIT

### Functions

- `mint(address to, uint256 amount)`: Allows the owner to mint tokens.
- `burn(uint256 amount)`: Allows token holders to burn their tokens.
- `transfer(address to, uint256 amount)`: Allows token holders to transfer tokens.
- `sellItem(string memory itemName, uint256 price, uint256 quantity)`: Allows the owner to sell items.
- `buyItem(string memory itemName, uint256 quantity)`: Allows users to buy items.

### Events

- `ItemPurchased(address indexed buyer, string item, uint256 price, uint256 quantity)`: Emitted when an item is purchased.

### Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

### Support

For support, contact [Your Email Address].

