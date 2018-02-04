# ClinicalTrials

## Summary
This project is aimed to implement a tool to scrape, analyze and present clinical trials data. The data will be collected from https://clinicaltrials.gov/. 

## Project Design
User Interface  <-->  Web Server  <-->  Database   <--  Scrape Server
   (React)           (Node.js)       (MongoDB)          (Python)

The scrape server will scrape cancer related clinical trials data and persisted in MongoDB. The client can query web server with key words, for example "lung". The web server will retrive correspondeing trials from database and return to frontend. The frontend will display the results in an organized way.
