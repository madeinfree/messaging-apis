# messaging-api-viber

> Messaging API client for Viber

<img src="https://www.viber.com/app/uploads/Icon_1024.png" alt="Viber" width="150" />

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Reference](#api-reference)


## Installation

```sh
npm i --save messaging-api-viber
```
or
```sh
yarn add messaging-api-viber
```

<br />

## Usage

### Initialize

```js
const { ViberClient } = require('messaging-api-viber');

// get authToken from ...
const client = ViberClient.connect(authToken);
```

<br />

## API Reference

All methods return a Promise.

<br />


## `setWebhook(url [, eventTypes])`

Example:
```js
client.setWebhook('https://4a16faff.ngrok.io/');
```

```js
client.setWebhook('https://4a16faff.ngrok.io/', []);
```

## `removeWebhook`

Example:
```js
client.removeWebhook();
```

## `sendMessage()`

## `sendText()`

## `sendPicture`

## `sendVideo`

## `sendFile`

## `sendContact`

## `sendLocation`

## `sendURL`

## `sendSticker`

## `sendCarouselContent`
