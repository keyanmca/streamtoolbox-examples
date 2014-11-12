wowzatoolbox-examples
=====================

Examples for the various tools on Wowzatoolbox.com that help seamless integration between Wowza Streaming Engine and your own video streaming system.

- [Wrench for Wowza](https://wowzatoolbox.com/wrench): this tools provides flexible authentication, authorization mechanisms for both your stream consumers and producers. Also provides pay-per-minute and pay-per-view solutions and much more.
- [Measure for Wowza](https://wowzatoolbox.com/measure): log player counts per stream, per streaming technology and per Wowza application using your own predefined SQL queries into your database

## Examples for Wrench

1. Simple authentication with PHP frontend and MySQL database (`01-simple-authentication`)

This example shows how to create a minimal video site which uses a MySQL database for storing users. Once the user gets in, a token is dynamically generated for him and stored in the database. This token is then put into video links so that Wrench can authenticate the user. All connections withtout valid token are refused.

![PHP Login Screen](/wrench/01-simple-authentication/screenshot-0.png)
![Protected Video Site](/wrench/01-simple-authentication/screenshot-1.png)
  
  