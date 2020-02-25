# blurbs
GA Capstone Project: Sound Snippet Recording Application
###### a tool to create snippets

## Project Description
blurbs is a tool to create small sound snippets to share with others. The core concept around blurbs was to create a tool to allow listeners, performers, and creators from all over the world to record a snippet to provide Better Radio with content.

This content can include anything from a call sign from a listener or musician, a vague weather report, a song introduction, a poem, an encouragement, and so on. These can then be downloaded and submitted to the station to be inserted into the broadcast library and shared with the world.

### Technologies
Built with ReactJS as a single-page application. 

#### Dependencies
- [React](https://github.com/facebook/react)
- [Create React App](https://github.com/facebook/create-react-app)
- [React Router](https://github.com/ReactTraining/react-router)
- [Mic Recorder to Mp3](https://github.com/closeio/mic-recorder-to-mp3)

### User Stories
- As a contributor, I want to record call signs for an internet radio station and submit that file. 
- As a regular listener to the radio station, I want to be able to record a call sign for the station so I can hear myself on air! 
- As an independent musical artist, I want to be able to say hello to station listeners and introduce some of my songs. 

### MVP/PostMVP

#### MVP
##### Bronze
- Microphone
-- records audio
-- allows user to save audio
-- allows user to submit audio
- Audio Player for recorded audio playback

#### Post MVP
##### Silver
- Direct submission from audio player
-- ability to submit without downloading content first
- Blurb generator 
-- Randomly generate blurbs for the user to read and record
- Audio component for sounds effects to record over
-- ability for user to play audio as an underlay to record their blurb over
- Database
-- online database for user submissions to live

##### Gold
- Snippet Library
-- utilize online database for users to opt in to save snippet to library
- User authentication
-- allow different power users to access library for maintenance
- Social Media Shares
-- Users can share snippets and the app via social media

<!-- ## Code Snippet -->

## Issues and Resolutions
**ERROR**
ReferenceError: Can't find variable: AudioContext
![AudioContext Error](https://i.ibb.co/GQvGPWf/Audio-Error.png)

**RESOLUTION**
Pending: Issue manifests on Safari (Mac & iOS)