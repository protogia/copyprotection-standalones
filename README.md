# Copyprotection for Mediafiles

## The idea
Because avoiding copying of files is not possible, I created a mediaviewer which only opens and encrypt files if certrain creteria are met. The encrypted files can only be opened with the special standalone-mediaviewer.

## Information

- Currently only pdf-files are supported.
- Other ways to reproduce the data (like taking screenshots) cannot be avoided
- You are not allowed to **move** or **copy** the folder to another location

## How to setup

1. Download the Project and store it on an USB-Drive you want to protect
2. Store your Mediafiles into the `media`-folder
3. Run encrypt.exe. You are not allowed to **move** or **copy** the folder to another location after you run encrypt.exe
4. Move the `encrypt.exe` and the mediafolder to another location as backup. Both should only be acessable for you.
5. To watch the files run `mediaviewer.exe`

## What if moved or copyied anyway?
create `media`-folder at the target-location, run `encrypt.exe` again. Then remove both again.
