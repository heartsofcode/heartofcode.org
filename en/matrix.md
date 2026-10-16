# Join our Matrix Space

Heart of Code has a community space on Matrix. Follow this link to join it: https://matrix.to/#/#community:matrix.heartofcode.org.

If you don't know what Matrix is, follow this guide to get setup.

## About Matrix
We use [Matrix](https://matrix.org), a secure and decentralized communication platform, to collaborate and communicate. We encourage you to join our Matrix space if you want to stay informed and chat with fellow Heart of Code folks. 

This guide will help you get started with our Matrix space.

## Setup

**Step 1: Install a Matrix Client**

To use Matrix you need an app, called a *client*. There are many to choose from, but we recommend **Element**, the most widely used one. It's free and available everywhere:

* **In your browser:** open https://app.element.io. Nothing to install.
* **On your computer:** download Element Desktop from https://element.io/download.
* **On your phone:** install **Element X** from the App Store or Google Play. If Element X can't connect to your homeserver (see Step 2), use the classic **Element** app instead.

Element is just the app, it is not where your account lives. You can sign in to any Element with an account from any homeserver, and use the same account on several devices at once. If you're curious about alternatives, see https://matrix.org/ecosystem/clients/ for a comparison.

**Step 2: Register an Account**

After launching a Matrix client, if you don't already have a Matrix account, register a new one. You can use your email address or phone number for registration. 

Heart of Code only runs a community space on Matrix, so you can't sign up with us. You will need to register with a homeserver run by someone else.

If you are trying Matrix for the first time, you could choose the matrix.org homeserver. However, please take a look at the following guides to understand the tradeoffs/advice on choosing a homeserver: 

* [“Join Matrix!” Guide: Basics](https://joinmatrix.org/guide/#set-up-your-own-homeserver-or-join-an-existing-homeserver). 
* https://servers.joinmatrix.org/users.html

In Element, click "Create account". The homeserver is preset to matrix.org. Click "Edit" next to it if you want to use a different one.

**Step 3: Save Your Recovery Key**

When you first sign in, Element will ask you to set up *recovery* (sometimes called *secure backup*). Do it, and keep the recovery key somewhere safe, like a password manager. You'll need it to read your encrypted messages on new devices. See [About Encryption](#about-encryption) below for why.

**Step 4: Join Our Organization's Matrix Room**

Once you've set up your account, find and join our organization's main room by searching for its ID or name in the client's search bar. Our room ID is: [`#community:matrix.heartofcode.org`](https://matrix.to/#/#community:matrix.heartofcode.org).

**Step 5: Set up Notifications**

Adjust your notification settings to ensure you receive important updates and messages from the team.

**Step 6: Start Chatting**

Feel free to introduce yourself, ask questions, and participate in discussions with your fellow Heart of Coders!

Happy collaborating, and welcome to our Matrix space!

## About Encryption

Matrix can *end-to-end encrypt* messages, so only the people in a conversation can read them, not even the servers in between.

**Encryption is set per room.** You don't need to do anything yourself: in an encrypted room, your app encrypts every message automatically. Direct messages and private rooms are usually encrypted. Public rooms often are not. Your client will usually show a badge or icon, such as a shield or lock, to tell you whether a room is encrypted.

**Your recovery key keeps your history readable.** The keys to read encrypted messages are stored on your devices, not on the server. When you sign in on a new device, or sign back in after signing out, you'll need your recovery key (from Step 3) to read your older messages. If you lose it and aren't signed in anywhere else, those messages can't be recovered.

If you see "Unable to decrypt", make sure recovery is set up and that you've verified your device when Element asked you to.
