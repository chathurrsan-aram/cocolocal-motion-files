# Prompt for ChatGPT: batch 3 (Offers Part 2 v6, price first)

This batch has 18 new files: the v6 Part 2 reel and eight shorts, each with a silent copy. They go into two Drive folders that already exist, inside "07 — Offers Part 2 (September)". Batches 1 and 2 are already in Drive, so leave them alone.

Copy everything inside the box below into ChatGPT, with it connected to your computer.

````text
Please download a batch of finished marketing videos from my GitHub repo and put them into my Google Drive.
Nothing needs editing or converting. It's a straight copy of 18 .mp4 files (about 200 MB) into two folders
that ALREADY EXIST in my Drive.

SOURCE
- GitHub repo: https://github.com/chathurrsan-aram/cocolocal-motion-files (branch: main)
- If I already have it on my computer from last time, update it: in that folder run  git pull
  Otherwise: git clone https://github.com/chathurrsan-aram/cocolocal-motion-files.git
  (or on the repo page: Code > Download ZIP, then unzip).
- The new files are in this repo folder:
  "05 — Brand Motion Kit/07 — Offers Part 2 (September)/v6 — price first (latest)"
  - 9 .mp4 files directly in it: the full reel + 8 single-offer shorts, with sound
  - 9 .mp4 files in its subfolder "Silent copies": the same videos without sound
- If that folder isn't in the repo yet, or has fewer than 18 .mp4 files, the upload hasn't landed yet:
  wait 15 minutes, pull again, and retry (up to 4 times). Don't upload a partial set.

DESTINATION (these folders already exist, so don't create them again)
  | Repo folder                                      | Files | Drive folder |
  |---|---|---|
  | v6 — price first (latest)                        | 9 | https://drive.google.com/drive/folders/1-I0CHYEbKPelekAAbHAOaiwX_YFfLZp3 |
  | v6 — price first (latest)/Silent copies          | 9 | https://drive.google.com/drive/folders/1J8B6AfLbzEmd8VWIoJlFuM4tzOxnhPFh |
- Use the Google account that owns these folders (open a link to check which one).
- Put each file into the matching Drive folder. Files directly in "v6 — price first (latest)" go into the
  first link, and files in its "Silent copies" subfolder go into the second link.

HARD RULES
- Do NOT move, rename, edit, overwrite or delete anything already in my Drive. Only add these files.
  The older videos in "07 — Offers Part 2 (September)" stay exactly where they are.
- Don't create any new folders. If a file with the same name is already in the target folder, skip it.
- Don't convert, compress or re-export the videos. Upload the .mp4 files exactly as they are.
- Only upload the 18 .mp4 files from that repo folder. Skip everything else in the repo.

HOW (use whichever works on my computer)
Option 1: Google Drive for desktop is installed
  - Find the synced path of "05 — Brand Motion Kit/07 — Offers Part 2 (September)/v6 — price first (latest)"
    (Mac: ~/Library/CloudStorage/GoogleDrive-<account>/My Drive/..., Windows: G:\My Drive\...).
  - Copy without overwriting:
      macOS:   rsync -av --ignore-existing --include='*/' --include='*.mp4' --exclude='*' "<repo folder>/" "<Drive folder>/"
      Windows: robocopy "<repo folder>" "<Drive folder>" *.mp4 /E /XC /XN /XO
  - Wait for Drive to finish syncing.
Option 2: Browser (drive.google.com)
  - Open the first Drive link and upload the 9 .mp4 files from the repo folder (not the subfolder).
  - Open the second link and upload the 9 .mp4 files from "Silent copies".
  - Wait until Drive says the uploads are complete.

CHECK WHEN DONE
- The first Drive folder should have 9 .mp4 files (plus the "Silent copies" folder), and the second should
  have 9 .mp4 files. Report any difference and any file that failed.
- Optional: SHA256SUMS-batch3.txt in the repo has a checksum for each of the 18 files.

Then give me a short summary: the method you used, files uploaded per folder, and anything skipped or failed.
````

## What's in the batch

The v6 layout makes the price the main thing on each offer, with less writing and slightly smaller product photos. In the full reel (43 s), the "Big favourites. Little prices." slide now comes just before the outro. The eight shorts are water, coffee, thirsty, jacobs, mccoys, pringles, barefoot and yellow-tail. All videos are 1080×1920 at 60 fps.
