# CFD Pediatric Readiness Training

Interactive training module for Centerville Fire Department (CFD) focused on pediatric emergency response and readiness.

## Overview

This is a comprehensive 23-module training application covering:
- Pediatric anatomy and physiology
- Assessment techniques (PAT, vitals, lung/heart sounds)
- Communication with pediatric patients and families
- Pediatric maltreatment recognition
- Scenario-based learning
- SBAR reporting
- Equipment and protocols
- Final assessment (80% passing required)

## Features

- Interactive modules with audio synthesis (heart and lung sounds)
- Real-time vital signs monitoring displays
- Scenario-based learning exercises
- Progress tracking and module completion
- Final assessment with immediate feedback
- Light theme with professional dark sidebar

## Structure

- `index.html` - Entry point and HTML structure
- `app.jsx` - React application (all modules and components)

## Deployment

This application is hosted on GitHub Pages and renders directly in the browser using:
- React 18 (via CDN)
- Babel standalone (for JSX compilation)
- Pure CSS styling (no external dependencies)

## Usage

1. Clone the repository
2. Enable GitHub Pages in repository settings
3. Application will be available at `https://ddorm106.github.io/cfd-pediatric-training/`

No build process required — the app runs directly in the browser.

## Development

All code is contained in `app.jsx`. The structure includes:
- Theme definitions and constants
- Audio synthesis functions for clinical sounds
- Reusable UI components (Bar, Quiz, DangerBox, etc.)
- Module components for each training section
- Main App component with navigation and state management

## Training Requirements

- Complete all 23 modules
- Score 80% (16/20) on final assessment to pass
- Fulfills CFD pediatric readiness CE requirements
