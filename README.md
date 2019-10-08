## Token CBPII Sample: Java

Simple CBPII app that illustrates Token's Confirmation of Funds flow. It shows how to
request a CAF access token, which is used to confirm if a given account has sufficient
funds for a payment.

To build this code, you need Java Development Kit (JDK) version 8 or later.

To build, `./gradlew build`.

To run, `./gradlew run`

This starts up a server.

The server operates against Token's Sandbox environment by default.
This testing environment lets you try out UI and account flows without
exposing real bank accounts.

The server shows a web page at `localhost:3000`. The page has a Link with Token button.
Clicking the button displays Token UI that requests an Access Token.
When the app has an Access Token, it uses that Access Token to get account balances.
