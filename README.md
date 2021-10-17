# Euler.io
-Permissionless Lending-
   Borrow any token


Abstract  

Euler is a capital-efficient permissionless lending protocol that helps users to earn interest on their crypto assets or hedge against volatile markets without the need for a trusted third party.
Lenders supply assets into any of the lending pairs to earn interest. Borrowers pay interest to borrow while collateralizing their loans. The protocol earns an interest rate spread.
 

-Isolated lending pairs-

With traditional “basket-based” lending protocols such as Compound, the ability to add new assets is tightly controlled. If a single asset is exploited, it can potentially compromise all users of the protocol. This creates the incentive for these basket-based protocols to focus on the most popular low-risk assets and leave out everything else.
Using isolated lending pairs, lenders can decide which pairs they are comfortable with and provide liquidity only to those. Just like on Uniswap, users of Euler.credit are also free to create lending pairs for any asset permissionlessly.

For example, providing DAI on DAI-MIR may have a higher interest rate than providing DAI on DAI-ETH due to a higher risk. It’s up to the LPs to make their own choices. 
 
 -Dynamic interest rates-
 
 During the time of high utilization, the system gradually starts increasing the interest rate. The system is initially set to target a 75% utilization rate.
The higher the rate, the more there is an incentive for other LPs to deposit the asset and for the borrowers to repay their debt.

-Single-sided LP tokens-

To allow better composability, Euler introduces single-sided LP tokens. Instead of giving you a single combined LP token, each lending pair has two LP tokens, representing a claim over their respective underlying assets. These are standard ERC20 tokens that can be used, transferred, or sold anywhere else.
For example, if you deposit 10 DAI in DAI-ETH pair, you’ll get 10 DAI LP tokens in DAI-ETH pair. If you deposit another 5 DAI in DAI-YFI pair and you’ll get 5 DAI LP tokens in DAI-YFI pair. Both LP tokens are unique and can only be used in their respective pairs.

-Say goodbye to impermanent loss-

For each lending pair, LPs are able to deposit just one asset and withdraw the same amount in the same asset later on + any accumulated interest.
While there is no risk of IL, there is another risk to be aware of. Just like with Compound, Aave, or Cream, the risk in Euler is that during periods of high utilization, you may have to wait a bit until there is more liquidity for you to withdraw all your funds.

-Euler (E) token-
Euler is the governance token of the Euler permissionless lending protocol.
The protocol will earn fees, coming from the interest rate spread and liquidations.

More info on the governance token will be released.


