1. Check if `/dev/index.html` is pointing to the current date folder  
1. Open `mas-menu-app-switch.js` in current date folder
1. Check that the URLs that have a date, have the correct date
    - Note: We want to fix this in the future, so we don't have to do it manually (maybe realtive links?) 
1. Open `/stable` folder, and clear everything inside the `tmp` 
1. Copy everything from the current date `dev` folder, except `0-templates` and `ch-daenuprobst`
1. Open `/stable/main.js` and remove one level (`../`) from the `pathAssets` variable (around line 7)
1. Check that message of the day is topical, relevant and up-to-date (around line 9).
1. Open `mas-menu-app-switch.js`, remove the dates from the URLs and replace `dev` with `stable`
1. Commit changes
1. Push to Github
