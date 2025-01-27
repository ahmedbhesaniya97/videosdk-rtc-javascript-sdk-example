# Video SDK Javascript App

## What is it?

This code sample demonstrates a one-to-one and group video call application built with [Video SDK RTC Javascript SDK](https://docs.videosdk.live/docs/guide/video-and-audio-calling-api-sdk/getting-started)

- Built for serverless video calling experience.
- Scale it upto 5,000 participants with low code.
- 10,000 minutes free on monthly basis

## Features

- [x] Video API with real-time audio, video and data streams
- [x] 5,000+ participants support
- [x] Chat support with rich media.
- [x] Screen sharing with HD and Full HD.
- [x] Play realtime video in meeting
- [x] Connect it with social media such as Facebook, Youtube etc (RTMP out support).
- [x] Intelligent speaker switch
- [x] Record your meetings on cloud
- [x] Customise UI and built other rich features with our new data streams such as whiteboard, poll, Q & A etc.

## Prerequisites

You must have the following installed:

- Node.js v12+
- NPM v6+ (comes pre-installed with newer Node versions)

## Getting started

1. Run the authentication server

   Follow instructions from [videosdk-rtc-nodejs-sdk-example](https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example) to run the authentication server.

2. Clone the repo

   ```sh
   $ git clone https://github.com/videosdk-live/videosdk-rtc-javascript-sdk-example.git
   ```

3. Update the api server url in the `index.js` file that points to the authentication server.

   ```
   API_SERVER_URL="http://localhost:9000"
   ```

4. Run the app

   ```sh
   $ npm install -g live-server
   $ live-server --port=8000
   ```

For more information, visit [official documentation](https://docs.videosdk.live/docs/guide/video-and-audio-calling-api-sdk/getting-started)

Related

- [Video SDK RTC Prebuillt No Code App](https://github.com/videosdk-live/videosdk-rtc-js-prebuilt-embedded-example)
- [Video SDK RTC React Native App](https://github.com/videosdk-live/videosdk-rtc-react-native-sdk-example)
- [Video SDK RTC Node JS API](https://github.com/videosdk-live/videosdk-rtc-nodejs-sdk-example)
