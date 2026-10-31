# PDF Xper

**A completely free PDF reader and editor for macOS on Apple silicon (M-series
chips).** PDF Xper covers more than 90% of the features you would otherwise pay
for in commercial PDF apps — no subscription, no account, no watermark.

**[Download the latest version](https://github.com/Fovaie/pdfx-releases/releases/latest)**

## What you can do

**Read**
- Fast, sharp rendering with tabs for every open PDF in one window
- Full-text search, outline/bookmark navigation, page thumbnails
- Single and two-page layouts, zoom modes, and it remembers where you left off
- A home page with your recent files, cover thumbnails, and reading progress

**Annotate**
- Highlight, underline, strike out, draw, add shapes, notes, and text boxes
- Browse and jump between all annotations from the sidebar

**Edit**
- Edit existing text and images directly on the page
- Add new text, images, and links
- Find and redact sensitive text, and remove hidden text layers

**Organize pages**
- Reorder, rotate, insert, delete, extract, and split pages
- Insert pages from other PDFs or images

**Forms and signatures**
- Fill in PDF forms
- Add a visual signature (draw, type, or sign on your phone via QR code)
- Sign with a digital certificate and validate existing signatures
- Create and place your own stamps

**Protect and optimize**
- Add or remove password protection
- Compress files to reduce their size
- Saves only what changed, so large files save quickly and safely

**For power users**
- A bundled `mpdf` command-line tool for automating PDF tasks

## Install

1. Download `PDF-Xper-<version>.dmg` from the
   [latest release](https://github.com/Fovaie/pdfx-releases/releases/latest)
   and open it.
2. Drag **PDF Xper** into Applications, replacing any older version (including
   one named pdfx).
3. **First launch** — PDF Xper is not notarized by Apple yet, so macOS blocks
   it the first time ("PDF Xper" Not Opened). Right-click › Open no longer
   works on macOS 15 and later; instead:
   1. Click **Done** in that dialog.
   2. Open **System Settings › Privacy & Security** and scroll down to
      *"PDF Xper" was blocked to protect your Mac*.
   3. Click **Open Anyway**, confirm with your password or Touch ID, and open
      PDF Xper again.

   You only need to do this once per installed version.

   Prefer Terminal? This does the same:
   `xattr -dr com.apple.quarantine "/Applications/PDF Xper.app"`

**Requirements:** a Mac with Apple silicon (M1 or later).

## Free updates

- **A new version is released within every 45 days**, so you can keep using
  PDF Xper indefinitely by updating.
- PDF Xper checks this page for new versions on launch and shows a banner when
  an update is available. You can also choose
  **PDF Xper › Check for Updates…** at any time.
- Each release can be used for **45 days** from its release date. After that
  it switches to read-only (reading, searching, and Save As keep working) until
  you install the newest release — which is always free and gives you another
  45 days.

## Terms of use

PDF Xper is free for **personal and educational, non-commercial use**. As long
as you use it only for yourself or for learning, you may keep using it for
free, indefinitely.

**Commercial use is not permitted** without prior written permission. This
includes using PDF Xper in or for a business, organization, or paid work, and
selling, redistributing, or bundling it. Unauthorized commercial use will be
pursued under applicable law.

PDF Xper is provided "as is", without warranty of any kind. Keep backups of
important documents.

### 使用条款（中文）

PDF Xper 仅供**个人使用和学习用途，禁止商业用途**。只要你只是个人使用或学习，
就可以一直免费使用。软件会在每 45 天内发布更新，更新到最新版即可继续使用。

未经书面许可，**不得用于任何商业用途**，包括在公司、组织或有偿工作中使用，
以及出售、再分发或捆绑分发本软件。对于未经授权的商业使用，作者将依法追究法律责任。

本软件按"现状"提供，不提供任何形式的担保，请自行备份重要文件。
