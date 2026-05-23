# Cyber Threat Intelligence Dashboard

A cybersecurity inspired web application that simulates how security systems analyze URLs and detect potential threats using structured intelligence reporting.

## Project Overview

This project is a simulated Cyber Threat Intelligence Dashboard that analyzes user provided URLs and generates a structured security report.

It is designed to mimic how real world security operations centers (SOC) evaluate and classify potential threats.

## Features

- URL risk analysis using security rules
- Threat classification (Safe / Suspicious / High Risk)
- Structured intelligence report output
- Detection of common phishing indicators:
  - Missing HTTPS
  - Suspicious keywords
  - URL shortening services
  - Suspicious hiding patterns
- Risk scoring system (0–100)

## How It Works

The system evaluates URLs based on multiple security rules and assigns a risk score.

Each detected pattern contributes to the final classification:
- Low risk → Safe browsing behavior
- Medium risk → Suspicious indicators present
- High risk → Potential phishing attempt

## Purpose of This Project

This project was built to understand:
- How cybersecurity systems detect threats
- How phishing analysis works
- How structured security reports are generated in SOC environments

## Technologies Used

- HTML
- CSS
- JavaScript

## What I Learned

- Basic cybersecurity threat modeling
- Risk scoring logic design
- Frontend UI structuring for security tools
- How real-world security dashboards present data

## Future Improvements

- Add real time URL reputation API integration
- Improve scoring algorithm with weighted risk factors
- Add visual charts for threat analysis
- Convert into multi-page cybersecurity dashboard

## Author

Built by a student exploring cybersecurity fundamentals.
