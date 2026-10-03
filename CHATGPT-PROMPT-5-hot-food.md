# Prompt for ChatGPT: batch 5 (Hot food, coming soon)

This batch is one folder, "08 — Hot Food (Coming soon)": the hot food intro, the full-range reel with hot food (14 collections), and the hot food carousel motion. Each project comes with silent copies, storyboards, a caption and its editable source. That's 114 files, about 180 MB. It goes into a new, empty Drive folder I've already created. Batches 1 to 4 are already in Drive, so leave them alone.

Copy everything inside the box below into ChatGPT, with it connected to your computer.

````text
Please download a folder of finished marketing videos from my GitHub repo and put it into my Google Drive.
Nothing needs editing or converting. It's a straight copy of ONE folder (114 files, about 180 MB, including
subfolders) into a Drive folder that ALREADY EXISTS and is currently empty.

SOURCE
- GitHub repo: https://github.com/chathurrsan-aram/cocolocal-motion-files (branch: main)
- If I already have it on my computer from last time, update it: in that folder run  git pull
  Otherwise: git clone https://github.com/chathurrsan-aram/cocolocal-motion-files.git
  (or on the repo page: Code > Download ZIP, then unzip).
- The folder to copy is:  "05 — Brand Motion Kit/08 — Hot Food (Coming soon)"
  It contains: "01 — Hot food intro", "02 — Full range with hot food (14 collections)",
  "04 — Hot food carousel motion", plus "README — outstanding inputs.md" and "captions.md".
  (There is no 03: that's the Canva carousel, which is already in Canva.)
- If that folder isn't in the repo yet, or has fewer than 114 files in total (counting subfolders), the upload
  hasn't landed yet: wait 15 minutes, pull again, and retry (up to 4 times). Don't upload a partial set.

DESTINATION (already exists and is empty, so don't create another one)
  Drive folder "08 — Hot Food (Coming soon)":
  https://drive.google.com/drive/folders/1FlxLgXpxY7dSyB_S4-t8OPtlKcGueQDn
- Use the Google account that owns this folder (open the link to check which one).
- Put the CONTENTS of the repo folder "08 — Hot Food (Coming soon)" into that Drive folder, keeping every
  subfolder and file name exactly as it is. Folder names use a long dash "—".
  Don't nest an extra "08 — Hot Food (Coming soon)" folder inside it.

HARD RULES
- Do NOT move, rename, edit, overwrite or delete anything already in my Drive. Only add these files.
- Only create the subfolders that come with this folder. If one already exists from a half-finished attempt,
  use it. Never make "... (1)" duplicates. If a file with the same name already exists, skip it.
- Don't convert, compress or re-export anything. Upload the files exactly as they are, including the .md, .txt,
  .json, .py, .js, .html, .sh, .woff2, .png and .jpg files in the "Editable source" folders.
- Don't upload anything from outside this one folder.

HOW (use whichever works on my computer)
Option 1: Google Drive for desktop is installed
  - Find the synced path of "05 — Brand Motion Kit/08 — Hot Food (Coming soon)"
    (Mac: ~/Library/CloudStorage/GoogleDrive-<account>/My Drive/..., Windows: G:\My Drive\...).
  - Copy without overwriting:
      macOS:   rsync -av --ignore-existing "<repo folder>/" "<Drive folder>/"
      Windows: robocopy "<repo folder>" "<Drive folder>" /E /XC /XN /XO
  - Wait for Drive to finish syncing.
Option 2: Browser (drive.google.com)
  - Open the Drive link above. Select everything INSIDE the repo folder "08 — Hot Food (Coming soon)"
    (the three project folders and the two .md files) and drag them in. Drive keeps the subfolders.
  - Wait until Drive says the uploads are complete.

CHECK WHEN DONE
- The Drive folder should hold 114 files in total, including 16 .mp4 videos: 6 in "01 — Hot food intro" (with
  its subfolders), 2 in "02 — Full range with hot food (14 collections)" and 8 in "04 — Hot food carousel motion"
  (with their "Silent copies"). Report the total and any file that failed.
- Optional: SHA256SUMS-batch5.txt in the repo has a checksum for every file.

Then give me a short summary: the method you used, the number of files uploaded, and anything skipped or failed.
````

## What's in the batch

| Folder | Contents |
|---|---|
| 01 — Hot food intro | 15 s teaser, 1080×1920: **a** steam rising from a paper takeaway bag, **b** steam from a glowing, empty oven. Both are COMING-SOON. "Alternative — typography only" is the first steam-and-light cut |
| 02 — Full range with hot food (14 collections) | The full-range reel (55 s) with a Hot food "Coming soon" beat after Hot coffee. The 13-collection version stays in "05 — Product Range Reels" |
| 04 — Hot food carousel motion | The cream Canva carousel animated. **COMING-SOON** (cover + closing, 10 s) in 1080×1350 and 1080×1920, ready to post. **DRAFT-TEMPLATE** (all six pages, 23.5 s) shows the £[0.00] placeholders and is not for posting |

Every video has a silent copy. "README — outstanding inputs.md" lists what's still needed before the menu versions can go public: confirmed products, prices, units, real photos and a launch date.
