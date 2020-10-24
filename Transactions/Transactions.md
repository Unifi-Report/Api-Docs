#Transactions
You can get the transactions by using the following API call:

/api/latest-token-transactions/

####This will return the last 5 transactions.

####You can also specify the following parameters:
contract=(smart contract)
page_size=(up to 20)
page=(page)

####So for example an API call may look like:
/api/latest-token-transactions/?token=TBwoSTyywvLrgjSgaatxrBhxt3DGpVuENh&page_size=10&page=1