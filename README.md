# A LOYALTY PLATFORM APPLICATION USING HYPERLEDGER FABRIC

This platform is to allow manufacturer(P&G here) directly award their customer for being a loyal customers and customers can redeem those tokens at any of the retailer's store associated with the manufacturer.

## Use Case digram

![Use  case diagram](https://user-images.githubusercontent.com/24249646/82753965-8570f480-9de7-11ea-9e11-e1f6b3ed5dd3.jpg)

## Flow diagram

![FLOW DIAGRAM COMPONENTS](https://user-images.githubusercontent.com/24249646/82753974-91f54d00-9de7-11ea-90d5-8547da772015.jpg)

1. Blockchain operator setup the private blockchain network having 3 organizations, 3 certificate authorities and 1 channel.
2. The end user ( admin, user, consumer ) interacts with ReactJS UI for register, update , grant tokens and reedem tokens.
3. The ReactJS platforms uses API gateway to interact with the blockchain network.
4. The ExpressJS API application uses fabric SDK to interact with the nwtwork.

## Technologies used

1. Hyperledger Fabric 1.4.6
2. Node.js
3. React.js

## Software versions


| System | Driver | Version
| --- | --- | --- |
| Platform 						 | Hyperledger Fabric | 1.4.6
| Docker | Docker	| 18.09.09
| Language				 | Go		| 1.11
| Node 					 | node		| 10.20
| UI 					 | React			| latest

_____________________________________________________________________________________________________________________________
## Steps to replicate locally

1. Clone this repository
2. Install required softwares for this app
3. Start the fabric network using shell script
4. Start the API server
5. Start the Client APP




### Network and channel architecture

![Network    Channel Architecture(1)](https://user-images.githubusercontent.com/24249646/82753981-9cafe200-9de7-11ea-835c-3e78b3dd8c2c.jpg)

### Ledger Structs Relationship

![Blockchain  Components Structure(1)](https://user-images.githubusercontent.com/24249646/82754010-c10bbe80-9de7-11ea-9b85-9864315eb395.jpg)
