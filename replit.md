# Truth or Dare Game

## Overview
A simple browser-based Truth or Dare game with two modes: "Everyone" (family-friendly) and "18+" (adult content). The game fetches truth and dare questions from the Truth or Dare Bot API.

## Project Structure
- `index.html` - Single-page application containing all HTML, CSS, and JavaScript

## Technical Details
- **Type**: Static HTML website (no build system)
- **Server**: Python HTTP server for development
- **Port**: 5000
- **External API**: https://api.truthordarebot.xyz

## Running the Project
The project runs using Python's built-in HTTP server:
```
python3 -m http.server 5000 --bind 0.0.0.0
```

## Features
- Two game modes: "Everyone" and "18+"
- Animated UI with gradient backgrounds
- Truth and Dare buttons that fetch questions from external API
- Mobile-responsive design
