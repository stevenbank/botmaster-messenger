# Snapshot report for `tests/incoming_update.js`

The actual snapshot is saved in `incoming_update.js.snap`.

Generated by [AVA](https://ava.li).

## using sendMessage after receiving a message defaults to pageId that received update

> Snapshot 1

    {
      recipient_id: '970771109681287',
      sentOutgoingMessage: OutgoingMessage {
        message: {
          text: 'Bye you',
        },
        messaging_type: 'RESPONSE',
        recipient: {
          id: '970771109681287',
        },
      },
      sentRawMessage: OutgoingMessage {
        message: {
          text: 'Bye you',
        },
        messaging_type: 'RESPONSE',
        recipient: {
          id: '970771109681287',
        },
      },
    

## using sendMessage after receiving a message defaults to pageId that received update

> Snapshot 2

    {
      first_name: 'John-David',
      gender: 'male',
      id: '970771109681287',
      last_name: 'Wuarin',
      locale: 'en_US',
      timezone: 1,
    }