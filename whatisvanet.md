# What is VANet?

VANet is a Virtual Airline interconnectivity platform. It takes the power of the Infinite Flight Live API as well as data provided by Virtual Airline Crew Centers and creates a platform to provide advanced functions to VAs. Some of these functions include:

- ACARS (Semi-Automatic Flight Logging)
- vFinances (Advanced Virtual Economy)
- Events System
- Route Sharing (for Codeshares)

We plan to add more function in the future.

## How are these Provided?

At it's core, VANet is an [Application Programming Interface](https://www.mulesoft.com/resources/api/what-is-an-api) or API. Crew Centers provide data (such as PIREPs) to VANet and VANet uses this to create more datasets. This data can be retrieved by Crew Centers as well, and shown to the user.

All data is formatted as [JSON](https://www.w3schools.com/whatis/whatis_json.asp). JSON is a standardized format for data transfer on the web, and is both human-readable and machine-readable.

## How Can I Access this Data?

To access this data, applications make HTTP Requests to VANet's API, which has documentation [here](https://vanet.app/docs). Although JSON is human-readable, it's not what you want to be showing to your users. That's where Integrations come in. An integration is simply a name for an application (or part of one) that takes the data from VANet and shows it to users in a format they can understand.

Not a fan of coding? Never fear! The VANet team has pre-made a range of integrations for you, meaning you don't have to get into the code. We currently support these platforms.

- Flare - VANet's Signature Crew Center
- phpVMS 5.x (Simpilot Version)
- phpVMS 7

You are of course welcome to program your own integration if you want to support a platform that isn't listed here.