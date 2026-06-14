# GitHub Notebook Uploader

## Overview
This notebook automates the process of creating and managing GitHub repositories directly from Google Colab. It sanitizes secrets in notebooks before upload, handles repository privacy settings, and supports mounting Google Drive to access notebooks.

## Features
- Google Drive integration for easy notebook access.
- Automatic secret detection and sanitization in notebooks.
- Create new GitHub repositories or update existing ones.
- Option to make private repos public and vice versa.
- Clean notebook outputs before upload.
- Repository metadata management via GitHub API.

## Tech Stack
- Python
- Jupyter Notebook / Google Colab
- Libraries: os, re, csv, json, time, base64, requests, getpass, pathlib

## How to Use
1. Mount your Google Drive via the notebook.
2. Set your GitHub username and token.
3. Configure settings such as repository privacy and dry-run mode.
4. Run the notebook to create or update GitHub repositories with sanitized notebooks.

## Status
This notebook is organized for GitHub presentation.