# PolyPlay

## Introduction

PolyPlay is a full-stack web application designed for managing and listening to song playlists. It leverages the power of React for the client-side interface and connects to a MongoDB database through a NodeJS/Express server for persistent data storage. This application allows users to create, modify, and delete song playlists, as well as listen to songs from a specific list.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Documentation](#documentation)
- [Examples](#examples)

## Features

- Playlist management: Create, edit, and delete playlists.
- Song playback: Listen to songs from playlists.
- Music player controls: Control music playback through the interface or keyboard shortcuts.
- Persistent data storage: Utilize MongoDB for saving playlists and song information.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the root directory of each application (`site-web` and `server`).
3. Run `npm ci` to install the necessary libraries defined in `package-lock.json`.

## Usage

To run the application locally:

1. Execute `npm start` in the root directory of both the `site-web` and `server` applications in separate terminal windows.
2. The ReactJS application will be available at `localhost:5010`, and the NodeJS/Express server will be accessible at `localhost:5020`.

## Dependencies

- React: For building the client-side application.
- NodeJS/Express: For the server-side logic and API.
- MongoDB: For data persistence.
- Other dependencies are listed in the `package-lock.json` files of both the `site-web` and `server` directories.

## Configuration

Before running the application, ensure that your MongoDB instance is properly set up. Update the `env.js` file with the correct connection information for your MongoDB instance.

## Examples

Example usage of the application includes creating new playlists, adding songs to playlists, playing music from a playlist, and exploring the music through the search functionality.
