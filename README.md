# Best Schedule Maker

## Overview

Best Schedule Maker is an AI-powered tool designed to help students create the optimal class schedule based on professor ratings, preferred time slots, and daily course load preferences. Using data scraped from Rate My Professors (RMP) and leveraging AI with Retrieval-Augmented Generation (RAG), this project aims to streamline the scheduling process with automation and intelligent recommendations.

## Features

**Rate My Professors Integration:** Scrapes professor ratings for San Jose State University (SJSU) (expanding to more schools later).

**Schedule Optimization:** Uses NetworkX (Python) or Google OR-Tools to generate the best class schedule.

**User Preferences:** Users can input preferred class times, number of classes per day, and schedule constraints.

**Chatbot Interface:** Basic front-end chatbot for easy interaction.

**Google Calendar Integration:** Sync schedules directly to Google Calendar via API.

**PostgreSQL Database:** Stores scraped data for efficient querying.

**Vector DB for RAG:** Utilizes Retrieval-Augmented Generation (RAG) to enhance scheduling recommendations.


## Tech Stack

Web Scraping: BeautifulSoup, Selenium

Backend: Python, FastAPI

Database: PostgreSQL

AI & Optimization: Vector DB, LLM, NetworkX, Google OR-Tools

Frontend: HTML, CSS (maybe React in the future)

Google Calendar API

Version Control: Git, GitHub

## Development Plan

Scrape Data: Collect professor ratings and store them in a structured database.

Database Setup: Design and integrate a PostgreSQL database to store and retrieve scheduling data.

Schedule Optimization: Implement scheduling logic using NetworkX or Google OR-Tools.

RAG Implementation: Learn and integrate Retrieval-Augmented Generation (RAG) for AI-powered recommendations.

Frontend Development: Build a simple chatbot UI with HTML/CSS.

Google Calendar Integration: Connect scheduling output to Google Calendar API.

Testing & Expansion: Test functionality and expand to more universities.

