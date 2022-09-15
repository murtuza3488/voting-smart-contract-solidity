# Voting Contract
This voting contract allows the owner to create limited time polls. Users can  give votes as True or False for the respective options and can periodically check the winners using the contract provided methods.

### Basic Functions
These are the basic function provided by the contract
| Function | Description | Accessibility |
| ---------- | ---------- |----------|
| createPoll | This function is used to create a new poll | Owner-only |
| resetPoll | This function is used to reset all the previous poll information. This can also forcefully end a Poll. | Owner-only |
| castVote | This function is used to cast a vote to the preferred choice | Public |
| getWinner | This function will return the winning choice | Public |
| getPollStatus | This will return the status of the ongoing poll | Public |