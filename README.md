# Project Title
Files Renamer (FMProj_FilesRenamer)

## Features
- Automatically renames photo and PDF files based on their contents.
- Extracts readable text from files.
- Saves extracted text as Markdown (.md) files.
- Supports both photo and PDF files.
- Lightweight (lite) version with support for a limited number of files.
- Maximum file size of 3 MB per file.

## What It Does
- Analyses the contents of photos and PDF files.
- Renames files using meaningful names rather than generic ones.
- Converts readable text within files into Markdown (.md) format.
- Does not store uploaded files, reducing the risk of data leakage, unauthorised access, or server-side caching.

## Intended Purpose
- Reduces manual administrative work.
- Automates repetitive tasks such as file renaming and data entry.
- Prepares extracted text for translation or further editing.
- Improves file organisation, making documents easier to identify and manage.
- Designed for anonymous use, with no requirement to create an account.

## Reflections (Why I created this app)
Much of my work, both past and present, involves unglamorous but necessary administrative tasks, such as sorting through images and documents. In today's digital world, creating files is effortless—a single tap of a phone camera can generate dozens of photos. The real work begins afterwards: organising, renaming, and extracting useful information from them. A folder full of randomly named files is difficult to navigate and adds unnecessary administrative overhead.
Many of these files also contain information that needs to be entered into ERP systems or other business applications. Before that can happen, someone has to manually read the files, extract the relevant data, and prepare it for use.
I created this app to automate those repetitive tasks. Its goal is to help the often-unsung administrator work more efficiently, reduce repetitive manual effort, and spend more time on work that adds real value.


## Technical Challenge
- Frustration level: 8.5/10.
- The project was split roughly 50% frontend development and 50% AI/backend integration.
- One of the biggest challenges was getting the AI to reliably read and interpret uploaded files.
- Integrating and communicating with the AI agent required considerable experimentation and troubleshooting.
- Balancing AI capability against token usage was another challenge—more capable models generally produce better results but are also more expensive and have stricter usage limits.

## Current Status
Approximately 98% of known bugs have been resolved. The application is now largely stable, but it has yet to undergo comprehensive stress testing to validate its reliability, consistency, and performance under heavier workloads.
