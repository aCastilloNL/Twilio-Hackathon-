# La Nurserie

## “A bit of help and a lot of love”

# Twilio / WCS Hackaton Project

Front-End repository of our group's submission for the Remote EU 2020 Wild Code School Hackathon, sponsored by Twilio.

![Javascript](https://aleen42.github.io/badges/src/javascript.svg)
![Twilio](https://img.shields.io/badge/API-twilio-red)
![OpenStreetMap](https://img.shields.io/badge/map-OpenStreetMap-green)
![React](https://img.shields.io/badge/React-blue)
![React-Router-Map](https://img.shields.io/badge/React-Router-Map)
![Function-Approach-Only](https://img.shields.io/badge/funcional-approach-only)

## Made by Wilders

### Front-End Members:

- Jacopo Luri https://github.com/JacopoLuri
- Jeanloup Cayuela https://github.com/j-loup30400
- Niko Phalen https://github.com/nphalen29

### Back-End Members:

(Separate repository: https://github.com/aCastilloNL/TwilioHackathonBE)

- Victoria Kulinkovich https://github.com/KulinkovichVA
- Dima Piskun https://github.com/DzmitryPS
- Alfred Castillo https://github.com/aCastilloNL

> WebApp made in 48 hours

## Install

```
$ npm install
$ cp .env.example .env
$ # set values in .env file

```

## List of Contents

- [Install](#install)
- [List of Contents](#list-of-contents)
- [Purpose](#purpose)
- [La Nurserie](#la-nurserie)
- [Wireframes Packages and Softwares used](#wireframes-packages-and-softwares-used)
- [Documentation](#documentation)

## Purpose

The Hackathon groups were each tasked with the challenge of developing a product aimed at providing disaster relief for socially impacted areas of our global economy, i.e. climate change, mental health, equal opportunities, and etcetera, within 48 hours.

Using React, React-router-DOM, React-Icons, Functional Approach Only, Hooks, Context, Styled Components, Figma and Miro as the foundation for which the UI lies upon, we have been able to merge both the Front with the Back through deployment and API calls.


## La Nurserie

La Nurserie

## Wireframes, Packages and Softwares used

- Node.js
- Netlify
- Miro
- React
- React Icons
- React Hooks
- Functional Approach Only
- Styled Components
- Figma

## Documentation

### Maps (OpenStreetMaps)

Project uses OpenStreetMaps as a Geocoding API provider, it can be replaced by updating options variable in app.js

### Deploy (Heroku)

Project is deployed using Netlify. https://lucid-feynman-60c600.netlify.app/

### Twilio

To enable whatsapp communication flow:

- set up twilio whatsapp testing sandbox (https://www.twilio.com/docs/whatsapp/sandbox)
- set up twilio studio flow by importing it from twilio/flow.json file
- update http widgets in flow to use correct endpoint (if creating your own deployment)
- set sandbox inbound webhook to value from trigger widget in flow