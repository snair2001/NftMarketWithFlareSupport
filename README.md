# NftMarketWithFlareSupport

We are building a platform for tokenization of music and other content into NFTs and the usage of smart contracts to pay for the content. The payment is transferred from the user's wallet to the creator by the execution of this smart contract without any intermediaries.

As the same NFT cannot be minted on multiple blockchain networks, we want the users to be able to pay for the NFT with whatever token they own; instead of being forced to use the same token in which the NFT was minted. As an example, we have chosen to mint the NFT with ETH but the same should be payable with POL on the Polygon Network. We use Flare FTSO service to convert the ETH amount to POL and display this amount in the shopping cart. 

Due to resource constraints, we have implemented only upto the part where the value of the NFT is calculated in POL and displayed in the shopping cart. The actual transfer of the NFT is yet to be implemented. We would like to extend this to XRP and FLR also. 

Also, the same Metamask wallet address should have both ETH and POL coins in their testnets to test the website. 
