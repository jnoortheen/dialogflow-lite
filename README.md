
# Dialogflow Python Library REST Agent

[![Package Version](https://img.shields.io/pypi/v/dialogflow-lite.svg)](https://pypi.python.org/pypi/dialogflow-lite/)
[![Build Status](https://travis-ci.org/vkosuri/dialogflow-lite.svg?branch=master)](https://travis-ci.org/vkosuri/dialogflow-lite)

Dialogflow is an python [requests](http://docs.python-requests.org/en/master/) REST agent to comunicate with [Dialogflow](https://dialogflow.com/)

## Prerequsites
Before execute any [examples](./examples) or source code usage, you need create a [Dialogflow](https://dialogflow.com/) account, More inforamtion how to create account found here https://dialogflow.com/docs/getting-started/create-account

## Features
### Speech recognition
The speech recognition used in this module is done using Anthony Zhang's [SpeechRecognition](https://github.com/Uberi/speech_recognition) library for Python.

### Speech synthesis
Speech synthesis in this project is done using espeak. Note: For Mac users, the adapter will use Mac's built-in say command.

## Installation

``` Bash
pip install dialogflow-lite
```

## Examples

See the [examples](./examples) directory in the GitHub repo.

##  Google conversation design best practices
https://designguidelines.withgoogle.com/conversation/conversation-design/welcome.html

## General Information
Most of the general information can found here https://dialogflow.com/docs/reference/agent/

1. [query](https://dialogflow.com/docs/reference/agent/query)
2. [entities](https://dialogflow.com/docs/reference/agent/entities)
3. [userEntities](https://dialogflow.com/docs/reference/agent/userentities)
4. [intents](https://dialogflow.com/docs/reference/agent/intents)
5. [contexts](https://dialogflow.com/docs/reference/agent/contexts)

## Using Access Tokens

The entire package uses based on User access token, read this documentation about [obtaining access tokens](https://dialogflow.com/docs/reference/agent#obtaining_access_tokens) from Dialogflow.

## Authorization with the value Bearer {access_token}.

For example:

``` Python
Authorization: Bearer YOUR_ACCESS_TOKE
```

## Protocol Version

``20140910`` used as protocol version in this repo

## License
This project licensed under [MIT](./LICENSE)
