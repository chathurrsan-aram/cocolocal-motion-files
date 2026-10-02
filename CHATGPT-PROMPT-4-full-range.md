# Prompt for ChatGPT: batch 4 (Full Range motion video)

This batch has 4 new files: the Full Range video with 13 collections and the shopfront opener, the earlier 12-collection version, and a silent copy of each. They go into three Drive folders that already exist, inside "05 — Product Range Reels". Batches 1 to 3 are already in Drive, so leave them alone.

Copy everything inside the box below into ChatGPT, with it connected to your computer.

````text
Please download a batch of finished marketing videos from my GitHub repo and put them into my Google Drive.
Nothing needs editing or converting. It's a straight copy of 4 .mp4 files (about 230 MB) into three folders
that ALREADY EXIST in my Drive.

SOURCE
- GitHub repo: https://github.com/chathurrsan-aram/cocolocal-motion-files (branch: main)
- If I already have it on my computer from last time, update it: in that folder run  git pull
  Otherwise: git clone https://github.com/chathurrsan-aram/cocolocal-motion-files.git
  (or on the repo page: Code > Download ZIP, then unzip).
- The new files are in this repo folder:
  "05 — Product Range Reels/05 — Full Range Motion (coded)"
  - 1 .mp4 directly in it: coco-full-range-13-collections-1080x1920.mp4 (the latest, with sound)
  - 1 .mp4 in its subfolder "Silent copy"
  - 2 .mp4 in its subfolder "Earlier version — 12 collections"
- If that folder isn't in the repo yet, or has fewer than 4 .mp4 files in total, the upload hasn't landed yet:
  wait 15 minutes, pull again, and retry (up to 4 times). Don't upload a partial set.

DESTINATION (these folders already exist, so don't create them again)
  | Repo folder (inside "05 — Product Range Reels")                         | Files | Drive folder |
  |---|---|---|
  | 05 — Full Range Motion (coded)                                          | 1 | https://drive.google.com/drive/folders/1xqSK1XPCP5pS7fe1yOtdpWQ1R8n5X_jp |
  | 05 — Full Range Motion (coded)/Silent copy                              | 1 | https://drive.google.com/drive/folders/1cJxkS33XXtg5vwVmRforK_PC9XET3tg_ |
  | 05 — Full Range Motion (coded)/Earlier version — 12 collections         | 2 | https://drive.google.com/drive/folders/11j0li6GCT_2_vQNiiQxdw1Rs38iK0DEe |
- Use the Google account that owns these folders (open a link to check which one).
- Put each file into the Drive folder that matches its repo folder. Folder names use a long dash "—".

HARD RULES
- Do NOT move, rename, edit, overwrite or delete anything already in my Drive. Only add these files.
  The Canva exports and the "04 — Editable Source & Product Assets." folder stay exactly as they are.
- Don't create any new folders. If a file with the same name is already in the target folder, skip it.
- Don't convert, compress or re-export the videos. Upload the .mp4 files exactly as they are.
- Only upload these 4 .mp4 files. Skip everything else in the repo.

HOW (use whichever works on my computer)
Option 1: Google Drive for desktop is installed
  - Find the synced path of "05 — Product Range Reels/05 — Full Range Motion (coded)"
    (Mac: ~/Library/CloudStorage/GoogleDrive-<account>/My Drive/..., Windows: G:\My Drive\...).
  - Copy without overwriting:
      macOS:   rsync -av --ignore-existing --include='*/' --include='*.mp4' --exclude='*' "<repo folder>/" "<Drive folder>/"
      Windows: robocopy "<repo folder>" "<Drive folder>" *.mp4 /E /XC /XN /XO
  - Wait for Drive to finish syncing.
Option 2: Browser (drive.google.com)
  - Open each Drive link in the table and upload the .mp4 file(s) from the matching repo folder
    (for the first link, only the file directly in the folder, not the subfolders).
  - Wait until Drive says the uploads are complete.

CHECK WHEN DONE
- The three Drive folders should have 1, 1 and 2 .mp4 files. Report any difference and any file that failed.
- Optional: SHA256SUMS-batch4.txt in the repo has a checksum for each of the 4 files.

Then give me a short summary: the method you used, files uploaded per folder, and anything skipped or failed.
````

## What's in the batch

`coco-full-range-13-collections-1080x1920.mp4` (52 s) is the latest. It opens on the real shopfront ("Come on in."), pushes through the door into the "Discover more at Coco Local." cover, folds into a 13-tile grid, then taps through all 13 collections, now including Hot coffee. Each collection lights its real shelves on the isometric shop map. It ends on "See you in store." with a shopfront polaroid, then the lockup outro. The earlier 12-collection version (47 s) has no shopfront opener and no Hot coffee. Both are 1080×1920 at 60 fps, and the silent copies have no sound. The alcohol collection and the outro carry "18+ · Please drink responsibly".
