# Omadica 
Omadica is a GitHub organization that provides open-source solutions for video surveillance. 

Recently, we have been experiencing an increasing demand for smart cameras for homes and small and medium businesses, but what do we know about their privacy policies?
An intelligent IP camera can record our lives continuously, but who can access this data? How is it stored? How is it processed? 

Within the zoo of smart-camera manufacturer companies, the WebRTC connection and video persistency on their devices could have unclear policies. Some of them are pushy about signing a monthly subscription to give access to a "control room" to verify the pictures/audio/videos of the alarms, and in case of a threat, they can call the police.

Considering that alarms are most often activated by false threats, this context clearly has severe privacy leaks. Instead of actual threats, the guards can see our everyday lives, habits, discussions, and much more. Moreover, the cost of the service is definitely overpriced!

Omadica responds to the growing need for freedom and transparency in surveillance services. Our GitHub organization offers suggestions for open-source software that can be installed on a  Raspberry Pi to manage IP cameras and ensure only access to video and audio recorders to the end-users.

We also offer a desktop client for monitoring camera live streams, drawing analytics, record playback, and much more.

## Description of services
* Media Proxy
* Video persistence
* Analytics (ToDo)
* Fine grained users management
* Compatible with any IP camera 
* Playback 
* Live view
* Reactive UserInterface based on (ToDo)
    * WebRTC
    * WebSockets
    * REST
    * GraphQL
## What you need
* Hardware setup suggested
* Backend software
* Client Software

## How to install
* MediaMtx as a daemon
* Encrypted connection
* Keycloak for authentication
    * Internal
    * JWT
* CamView as a client
