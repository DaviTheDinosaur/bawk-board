# Bawk Board

This is the repository for the BunnyBots 2022 scoring system: Bawk Board

Make a data folder, containing a teams.json and matches.json files with: [] in them.

You also need to create a event.json file inside your data foler, containing: {currentMatchID:"qm1"}.

Make a secrests.js file, containing:

    export const origin_url = "";
    export const auth_secret = "";
    export const tba_secret_id = "";
    export const tba_secret = "";


Make sure to install all dependencies, then run:

    npm run dev
