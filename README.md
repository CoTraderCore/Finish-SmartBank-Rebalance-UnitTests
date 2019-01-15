# SmartBank-Rebalance-UnitTests-Finish
 
# Start test
1) yarn install
2) yarn truffle:test:full

# Replace in test
1) smartFund.totalShares() to smartBank.totalShares()
2) getBalance(smartFund.address) to getBalance(smartBank.address), because fund NOT holding any assets

# Add in test
1) add function tradeForDest to ExchangePortalMock contract

# New describe
1) SmartBank concept
2) Rebalance
3) SmartBank access permissions

# Total
1) 66 passing

# Add in contracts

1) ISmartBank and SmartBank
2) rebalanceToggle() for Rebalance
