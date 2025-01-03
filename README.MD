
# Kickstart Smart Contract 

## Installation

run the following command on  root directory to install the node packages

```node
    npm run install
```

Run the following command to compile the contracts 

    npm run compile

# Basic commands
For testing the contracts run the following command to see if everything is fine!

```node
    npm run test
```
I guess your are ready to go.

# Deploying the contract

```node
    npm run deploy
```
To deploy the contract on the local network run the following command
you also need to have the metamask extension installed on your browser
you also need to make sure you have your network api EP and your secret phrase for your account are set in the .env file

```node
    API_URL="https://sepolia.infura.io/v3/your-api-key"
    SECRTET_PHRASE="one two ...."
```
