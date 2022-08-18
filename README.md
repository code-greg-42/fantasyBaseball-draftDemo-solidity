Smart Contract and scripts for a blockchain-based fantasy baseball site.

All functions have been built into the front-end React app. A lot of the functionality of the React app centers around events.

I chose to have each draft pick send individually to the blockchain due to the RNG nature of the drafting process. Sending each pick to the blockchain ensures that a user will pick up where they left off in the event of a crash or a browser refresh.

This smart contract is currently setup to run with one main owner calling all of the functions, but it could easily be changed to work with each user calling it directly.

The corresponding React app can be found at github.com/grandersson/fantasyBaseball-draftDemo-React
