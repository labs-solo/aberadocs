# Specific Liquidity Provision Challenges on Berachain and Kodiak

## 1. The BEX is Not Capital Efficient

**Overview**: The Berachain Exchange (BEX) operates using a full range (Uniswap V2) style system, which leads to significant capital inefficiencies.

**Challenges**:
- **Inefficient Capital Utilization**: In a full range system like Uniswap V2, liquidity is distributed across all price ranges, regardless of where trading activity occurs. This results in a large portion of the capital being underutilized as it remains outside the active trading range.
- **Low Return on Investment**: Due to the broad distribution of liquidity, only a small fraction of the liquidity actually earns fees from trades, leading to lower returns for liquidity providers.
- **High Collateral Requirements**: To provide meaningful liquidity and earn significant returns, users need to lock up substantial amounts of capital, which could otherwise be used more efficiently in more targeted liquidity provision strategies.

## 2. $BGT Participation on Kodiak Requires an Automated Liquidity Manager (ALM)

**Overview**: Earning Berachain Governance Tokens ($BGT) through liquidity provision on Kodiak necessitates using an Automated Liquidity Manager (ALM). Validators distribute $BGT emissions to liquidity providers through gauges, which requires active and automated management.

**Challenges**:
- **Manual Concentrated Liquidity Positions**: These positions are represented by NFTs, which are ineligible for a gauge. This means a system is required to hold these concentrated positions while distributing LP tokens to users.
- **Asset Mix Requirements**: Most ALMs require depositors to bring in assets at the current mix in the ALM. This works against adoption, as depositors may not have the current mix of assets.
- **Swapping to a Certain Mix**: Most ALMs need to swap back to a certain mix of assets, necessitating significant non-ALM liquidity in the pool. This dependency on external liquidity can limit the efficiency and scalability of the ALM.

## 3. ‘Follow the Price’ ALMs are Designed for Market Makers, not Asset Owners

**Overview**: Traditional ALMs on Kodiak operate on ‘follow the price’ algorithms, which are optimized for market-neutral strategies suited to market makers.

**Challenges**:
- **Misalignment with Asset Owners**: These ALMs do not cater to the needs of asset owners who seek to align their strategies with specific market trends, focusing instead on market neutrality.
- **Risk of Unwanted Liquidations**: Asset owners may experience unwanted liquidations due to market volatility, compromising their asset value and growth objectives. Traditional ‘follow the price’ strategies can exacerbate these risks, as they frequently adjust positions based on price movements, potentially selling assets at unfavorable times.

### Conclusion
The liquidity provision challenges on Berachain and Kodiak underscore the need for more adaptable and user-friendly solutions. AquaBera addresses these challenges by:
- **Enhancing Capital Efficiency**: By adopting more strategic and targeted liquidity provision approaches, AquaBera avoids the inefficiencies of a full range system, ensuring that liquidity is concentrated where it is most needed, thus optimizing capital use and increasing returns.
- **Simplifying $BGT Participation**: AquaBera addresses the issues with current ALM setups by managing concentrated liquidity positions and distributing LP tokens to users, making it easier to participate in $BGT emissions without requiring specific asset mixes.
- **Aligning with Asset Owners' Goals**: Offering directional liquidity solutions that cater to asset owners, AquaBera minimizes the risk of unwanted liquidations and aligns liquidity strategies with market trends, ensuring better asset value preservation and growth.