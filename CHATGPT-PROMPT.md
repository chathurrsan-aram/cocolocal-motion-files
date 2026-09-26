# Prompt for ChatGPT

Copy everything inside the box below into ChatGPT, with it connected to your computer.

````text
Please upload a set of finished marketing videos from a private GitHub repo into my Google Drive.
Nothing needs editing or converting. It's a straight copy.

SOURCE
- Private GitHub repo: https://github.com/chathurrsan-aram/cocolocal-motion-files (branch: main)
- It has 288 .mp4 files (about 1.1 GB) inside a folder called "05 — Brand Motion Kit", laid out
  in the same subfolders that already exist in my Drive.
- Get it onto my computer with ONE of these (I'm logged into GitHub):
  a) git clone https://github.com/chathurrsan-aram/cocolocal-motion-files.git
  b) or on the repo page: Code > Download ZIP, then unzip it.

DESTINATION
- My existing Drive folder "05 — Brand Motion Kit":
  https://drive.google.com/drive/folders/1m8yIoYK-5VUiEc3kP0F9TvTMKdwcWHND
- Use the Google account that owns that folder (open the link to check which one).
- The subfolders already exist. Put each file into the subfolder with the SAME path it has in the repo:

  | Repo folder (inside "05 — Brand Motion Kit")    | Files | Drive folder link |
  |---|---|---|
  | 01 — Signature Reveal (approved)                | 18 | https://drive.google.com/drive/folders/1h06lXaj_iE_FEwC_uUWskjgVuQwqkOXm |
  | 01 — Signature Reveal (approved)/Silent copies  | 18 | https://drive.google.com/drive/folders/1QUyNksH4dYjCZbGhq95Ur_7LaJbFp_Gd |
  | 02 — Outros (approved)                          | 72 | https://drive.google.com/drive/folders/136OpXk2gsXaUsS-BXKR9SIUQp_5dU1Cg |
  | 02 — Outros (approved)/Silent copies            | 72 | https://drive.google.com/drive/folders/1Owc_oGJ37rOLrBFLQwg9kZloUFKuIZGH |
  | 03 — Intro Sting (approved)                     |  9 | https://drive.google.com/drive/folders/1oJuKwz33COS0N2AdbmpltELAf0I2_hcl |
  | 03 — Intro Sting (approved)/Silent copies       |  9 | https://drive.google.com/drive/folders/1A0JDB-EpGn3LyeiWC-QTUzk-bj3HcXax |
  | 04 — Follow Us                                  |  6 | https://drive.google.com/drive/folders/1XqOaJozQJ54uD0mbR0cwSfhackWY9jjO |
  | 04 — Follow Us/Light                            |  6 | https://drive.google.com/drive/folders/1NxpEc14BI5E-PlSOgPPlDSULHyw8W6kK |
  | 04 — Follow Us/Indigo                           |  6 | https://drive.google.com/drive/folders/1l14q9zE5pw6-x6T0dE-UBFrBG2pkHZH0 |
  | 05 — Weekly Offers                              |  6 | https://drive.google.com/drive/folders/1KE8TomciFsda8w7OMYrzRYF8eTiSMhTT |
  | 05 — Weekly Offers/Light                        |  6 | https://drive.google.com/drive/folders/1hHY3dLtjQo6PAUkJeV7YFuNf2_xqeq0_ |
  | 05 — Weekly Offers/Indigo                       |  6 | https://drive.google.com/drive/folders/1GrkMTob_mq-9WzU1V7drpCh5C3rnrIST |
  | 06 — Coco Wheel                                 | 18 | https://drive.google.com/drive/folders/12QoeTvLudy6P-jzIdunFTntYkBFDieP6 |
  | 06 — Coco Wheel/Light                           | 18 | https://drive.google.com/drive/folders/1_ZuWYbGv2sIKJNoq8mYNl9Fz4iTWjC-t |
  | 06 — Coco Wheel/Indigo                          | 18 | https://drive.google.com/drive/folders/19LMV_kKwkDZK54G2y7vVdRcejDip3xYf |

  (The counts are files directly in that folder, not including its subfolders.)

HARD RULES
- Do NOT move, rename, edit, overwrite or delete anything that is already in my Drive.
  Only add new files. If a file with the same name is already in the target folder, skip it.
- Do NOT create new copies of the folders (no "04 — Follow Us (1)"). Upload files INTO the
  existing folders above. Don't upload the parent folder itself.
- Don't convert, compress or re-export the videos. Upload the .mp4 files exactly as they are.
- Skip README.md, CHATGPT-PROMPT.md, SHA256SUMS.txt and the .git folder. Only upload .mp4 files.

HOW (use whichever works on my computer)
Option 1: Google Drive for desktop is installed (fastest)
  - Find "05 — Brand Motion Kit" in the synced Drive folder. On a Mac it's usually under
    ~/Library/CloudStorage/GoogleDrive-<account>/My Drive/...; on Windows, a drive like G:\My Drive\...
    If you can't find it, the folder may be in "Shared with me". In that case use Option 2.
  - Copy without overwriting anything, keeping the subfolders:
      macOS:   rsync -av --ignore-existing --include='*/' --include='*.mp4' --exclude='*' \
                 "<repo>/05 — Brand Motion Kit/" "<Drive path>/05 — Brand Motion Kit/"
      Windows: robocopy "<repo>\05 — Brand Motion Kit" "<Drive path>\05 — Brand Motion Kit" *.mp4 /E /XC /XN /XO
  - Wait for Drive to finish syncing (the Drive icon in the menu bar/tray stops showing activity).

Option 2: Browser (drive.google.com)
  - For each row in the table: open the Drive folder link, then use New > File upload (or drag and
    drop) to upload ALL the .mp4 files from the matching repo folder. Select only the files in that
    folder, not its subfolders.
  - Wait for each batch to say "uploads complete" before moving on.

CHECK WHEN DONE
- Open every Drive folder in the table and confirm the number of .mp4 files matches the Files column
  (288 in total). Report any folder where the count is off, and any file that failed or was skipped
  because it already existed.
- Optional: SHA256SUMS.txt in the repo lists a checksum for every file if you want to verify the
  local copy before uploading.

Then give me a short summary: the method you used, files uploaded per folder, and anything skipped or failed.
````
