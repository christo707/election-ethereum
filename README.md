
# election-ethereum

Ethereum Dapp for Conduction elections between 4 Default candidates.

## Installation

1. Install Truffle globally.
    ```javascript
    npm install -g truffle
    ```
2. Install Dependencies
    ```javascript
    npm i
    ```

4. Compile and migrate the smart contracts. Note inside the development console we don't preface commands with `truffle`.
    ```javascript
    compile
    migrate
    ```

5. Run the `liteserver` development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.
    ```javascript
    // Serves the front-end on http://localhost:3000
    npm run dev
    ```


