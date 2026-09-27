# Prompt for ChatGPT: batch 2 (offers revision)

This covers only the new files added on 27 Sep: the Offers Part 2 videos, the drinks reel with its new soundtrack, and the earlier drafts. The first 288 files are already in Drive (see `CHATGPT-PROMPT.md`), so leave them alone.

Copy everything inside the box below into ChatGPT, with it connected to your computer.

````text
Please download a batch of finished marketing videos from my GitHub repo and file them into my Google Drive.
Nothing needs editing or converting. It's a straight copy of 35 new .mp4 files (about 430 MB) into NEW folders.

SOURCE
- GitHub repo: https://github.com/chathurrsan-aram/cocolocal-motion-files (branch: main)
- If I already have it on my computer from last time, update it: in that folder run  git pull
  Otherwise get it with ONE of these (I'm logged into GitHub):
  a) git clone https://github.com/chathurrsan-aram/cocolocal-motion-files.git
  b) or on the repo page: Code > Download ZIP, then unzip it.
- The new files are ONLY in these repo folders (all inside "05 — Brand Motion Kit"):

  | Repo folder (inside "05 — Brand Motion Kit")                                      | Files | What it is |
  |---|---|---|
  | 07 — Offers Part 2 (September)                                                    | 9 | CURRENT: full reel + 8 single-offer shorts, with sound |
  | 07 — Offers Part 2 (September)/Silent copies                                      | 9 | Same 9 videos without sound |
  | 07 — Offers Part 2 (September)/Earlier versions/v1 — first full cut               | 9 | Earlier cut, kept for reference |
  | 07 — Offers Part 2 (September)/Earlier versions/v2 — simple version (first 12 s only) | 3 | Earlier simple-motion test, kept for reference |
  | 07 — Offers Part 2 (September)/Earlier versions/Prototypes                        | 2 | First coffee and McCoy's tests, kept for reference |
  | 05 — Weekly Offers/New soundtrack (groove)                                        | 1 | Drinks reel, same picture, new music |
  | 05 — Weekly Offers/Earlier drafts                                                 | 2 | Drinks reel drafts 1 and 2 (4:5), kept for reference |

  (Counts are .mp4 files directly in that folder, not including subfolders. 35 in total.)
  Folder names use a long dash "—" (em dash), not a hyphen. Keep them exactly as they are.

DESTINATION
- My existing Drive folder "05 — Brand Motion Kit":
  https://drive.google.com/drive/folders/1m8yIoYK-5VUiEc3kP0F9TvTMKdwcWHND
- Its existing subfolder "05 — Weekly Offers":
  https://drive.google.com/drive/folders/1KE8TomciFsda8w7OMYrzRYF8eTiSMhTT
- Use the Google account that owns those folders (open a link to check which one).
- Recreate the repo layout in Drive:
  - Inside "05 — Brand Motion Kit", create the NEW folder "07 — Offers Part 2 (September)" with its
    subfolders "Silent copies" and "Earlier versions", and inside "Earlier versions" the three folders
    "v1 — first full cut", "v2 — simple version (first 12 s only)" and "Prototypes".
  - Inside the EXISTING "05 — Weekly Offers", create the NEW folders "New soundtrack (groove)" and
    "Earlier drafts".
  - Upload each file into the Drive folder with the same path it has in the repo.

HARD RULES
- Do NOT move, rename, edit, overwrite or delete anything already in my Drive. Only add new folders
  and new files.
- Only create the new folders listed above. If one already exists (for example from a half-finished
  earlier attempt), use it instead of making a second copy. Never make "... (1)" duplicates.
- Don't convert, compress or re-export the videos. Upload the .mp4 files exactly as they are.
- Only upload the 35 .mp4 files from the folders in the table. Skip the .md and .txt files and the .git
  folder, and don't re-upload the older folders (01 to 06), which are already in Drive.

HOW (use whichever works on my computer)
Option 1: Google Drive for desktop is installed (fastest)
  - Find "05 — Brand Motion Kit" in the synced Drive folder. On a Mac it's usually under
    ~/Library/CloudStorage/GoogleDrive-<account>/My Drive/...; on Windows, a drive like G:\My Drive\...
    If you can't find it, the folder may be in "Shared with me". In that case use Option 2.
  - Copy only the new folders, without overwriting anything:
      macOS:
        R="<repo>/05 — Brand Motion Kit"; D="<Drive path>/05 — Brand Motion Kit"
        rsync -av --ignore-existing --include='*/' --include='*.mp4' --exclude='*' "$R/07 — Offers Part 2 (September)/" "$D/07 — Offers Part 2 (September)/"
        rsync -av --ignore-existing "$R/05 — Weekly Offers/New soundtrack (groove)/" "$D/05 — Weekly Offers/New soundtrack (groove)/"
        rsync -av --ignore-existing "$R/05 — Weekly Offers/Earlier drafts/" "$D/05 — Weekly Offers/Earlier drafts/"
      Windows (PowerShell):
        $R="<repo>\05 — Brand Motion Kit"; $D="<Drive path>\05 — Brand Motion Kit"
        robocopy "$R\07 — Offers Part 2 (September)" "$D\07 — Offers Part 2 (September)" *.mp4 /E /XC /XN /XO
        robocopy "$R\05 — Weekly Offers\New soundtrack (groove)" "$D\05 — Weekly Offers\New soundtrack (groove)" *.mp4 /XC /XN /XO
        robocopy "$R\05 — Weekly Offers\Earlier drafts" "$D\05 — Weekly Offers\Earlier drafts" *.mp4 /XC /XN /XO
  - Wait for Drive to finish syncing (the Drive icon in the menu bar or tray stops showing activity).

Option 2: Browser (drive.google.com)
  - Open "05 — Brand Motion Kit" (link above). Drag the whole repo folder "07 — Offers Part 2 (September)"
    from my computer into it. Drive keeps its subfolders.
  - Open "05 — Weekly Offers" (link above). Drag in the two repo folders "New soundtrack (groove)" and
    "Earlier drafts".
  - Wait until Drive says the uploads are complete.

CHECK WHEN DONE
- Open each new Drive folder and confirm the .mp4 count matches the Files column in the table (35 in
  total). Report any folder where the count is off, and any file that failed.
- Optional: SHA256SUMS-batch2.txt in the repo lists a checksum for each of the 35 files, if you want to
  verify the local copy before uploading.

Then give me a short summary: the method you used, the Drive link of the new "07 — Offers Part 2 (September)"
folder, files uploaded per folder, and anything that failed.
````

## What's in the batch

| Folder | Contents |
|---|---|
| **07 — Offers Part 2 (September)** | **The current videos.** `coco-offers-part2-full-reel-1080x1920.mp4` (43 s) opens on "This week's deals", runs the "Big favourites. Little prices." cover and all eight offers, then ends on the animated lockup. Eight shorts, one per offer: water, coffee, thirsty, jacobs, mccoys, pringles, barefoot, yellow-tail. |
| Silent copies | The same 9 videos with no sound. Use these if you add music inside Instagram. |
| Earlier versions / v1 — first full cut | The first full reel and shorts (39 s reel, no opener). |
| Earlier versions / v2 — simple version | The calmer fade version, which was only made as a 12 s reel test plus coffee and McCoy's shorts. |
| Earlier versions / Prototypes | The first coffee pour and McCoy's crisp tests. |
| 05 — Weekly Offers / New soundtrack (groove) | The drinks reel you already have, with the new funk and house soundtrack. |
| 05 — Weekly Offers / Earlier drafts | Drinks reel draft 1 (photo panels) and draft 2 (spinning cut-outs), both 4:5. |

Every video is 1080×1920 (9:16) at 60 fps, except the two drinks drafts, which are 1080×1350 (4:5). Alcohol offers carry "18+ · Please drink responsibly".
