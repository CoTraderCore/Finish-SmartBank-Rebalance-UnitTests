# SmartBank-UnitTests

# Replace
1) smartFund.totalShares() to smartBank.totalShares()
2) getBalance(smartFund.address) to getBalance(smartBank.address), because fund NOT holding any assets


# Fails
1) should accurately calculate profit and shares with multiple trades to and from eth:
2) Fund Manager profit cut with deposit/withdraw scenarios should accurately calculate shares when the manager makes a profit:
3) Fund Manager profit cut with deposit/withdraw scenarios should accurately calculate shares when FM makes a loss then breaks even:
