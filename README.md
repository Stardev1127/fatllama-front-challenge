# Fat Lama Frontend Challenge

## Challenge:
To keep the Fat Lama business moving, our Operations team reviews transactions, verifies user identities and deals with many other user support issues.

In this challenge, we would like you to build a feed for our ops team to monitor the most recent transactions and view information about that transaction and that user, and approve transactions if it is all correct. They should also be able to make notes on transactions for other members of the team to read.

## Requirements:
**Feed view**: where ops team can see all most recent transactions, ordered either by most recent or by status.

**Transaction view**: where ops team can see information about a transaction, approve the transaction.

## Endpoints:
- `GET /transaction/:id`
- `GET /transactions/:page`
- `PUT /transaction/id`
- `GET /user/:id`

Documentation for the API and instructions for the challenge are deliberately sparse as we want to see how you make decisions based on incomplete data.

## Criteria/Guidance
- The challenge is about your grasp of user experience as well as about your coding ability
- Use of frameworks and libraries is up to you. We suggest you use a boilerplate such as [create-react-app](https://github.com/facebook/create-react-app) to get yourself up and running quickly
- Try to implement appropriate [separation of concerns](https://effectivesoftwaredesign.com/2012/02/05/separation-of-concerns/) & modular code
- Think hard about naming of functions and variables
- Code style & file structure is up to you, but make sure it is consistent and legible
