# 25 + 5 Clock
You can access the live demo here: https://25clock-iota.vercel.app/
A fully functional Pomodoro-style timer app built with **React**, **TypeScript**, and **Vite**, based on the freeCodeCamp Front End Libraries certification project. This app passes all the user stories and tests provided by freeCodeCamp.

## Overview

The 25 + 5 Clock is a Pomodoro-style timer that includes adjustable session and break lengths, start/stop functionality, reset, and an audio alert when sessions or breaks end. The project is built with modern tools and adheres to all 28 specified user stories.

## Features

- Adjustable session and break lengths (1–60 minutes)
- Play/pause toggle
- Reset functionality
- Countdown timer with mm:ss formatting
- Automatic switch between session and break
- Audio beep when time reaches zero
- Clean, responsive UI
- State management for timer logic
- Compatible with freeCodeCamp's testing suite

## Technologies Used

- React 18
- TypeScript
- Vite
- Custom CSS or styling framework of choice
- HTML5 Audio
- FreeCodeCamp test bundle

## Project Requirements

- Proper labels and controls for session and break
- Properly formatted display of time
- Accurate behavior when starting, stopping, or resetting the timer
- Logic for alternating between session and break modes
- A functioning audio element with `id="beep"` that plays on every mode switch
- Constraints to prevent setting durations below 1 or above 60
- Resetting the timer resets all values and stops audio playback

## Setup

To run this project locally:

```bash
# Clone the repository
git clone https://github.com/your-username/25-5-clock.git
cd 25-5-clock

# Install dependencies
npm install

# Start development server
npm run dev
