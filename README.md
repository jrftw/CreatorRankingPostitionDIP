# Creator Ranking Data Repository

This repository contains the data for the Creator Ranking Dashboard, automatically synced from Google Sheets.

## Structure

- `/data/creators.json` - Combined data from all sheets
- `/data/sheets/` - Individual sheet data files
- `/data/sync-status.json` - Sync status and metadata

## Auto-Sync

Data is automatically synced every 30 minutes from the Google Sheet via Google Apps Script.

## Access

- **Dashboard**: https://infinitumcreatorrankui.web.app
- **Raw Data**: https://raw.githubusercontent.com/jrftw/CreatorRankingPostitionDIP/main/data/creators.json

## Last Sync

Check `/data/sync-status.json` for the latest sync information.
