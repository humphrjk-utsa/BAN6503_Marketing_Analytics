# Marketing Analytics — Course Repository

**Dr. Jamie Humphries · Carlos Alvarez College of Business · UTSA**

This repository is your working environment for the course. It holds every week's lesson, the data that goes with it, and a complete Python setup that runs in your browser. You never install anything on your own computer.

## What this course is about

Marketing, done properly, is a measurement discipline. It is the work of figuring out what your customers actually value, putting a number on it, and aligning what the company spends against that number. Over the semester you will learn to build a customer value equation from survey data, connect satisfaction to retention and revenue, read a regression honestly, and decide where a company's money should go and — just as often — where it should stop going.

Each week pairs a case about a real company with an analysis you run yourself in Python. The cases are about executives making expensive decisions on incomplete information. The analysis is how you would have done better.

## What is in the repository

Every week has a folder under `lessons/`, and each folder contains the same three things:

| File | What it is |
| --- | --- |
| `Class_N_….ipynb` | The week's Jupyter notebook — the lesson worked end to end, with every cell already run so you can read it before you run it |
| `data/` | The data files the notebook reads. Keep them where they are; the notebook expects them there |
| `Class_N_….html` | An audio-capable tutorial that walks the notebook step by step, explains what every cell does in plain words, and reads itself aloud. Open it in a browser tab beside the notebook |

The HTML tutorials are built for screen readers as well as for listening: every chart has a text description and a table, every output is restated in words, and the first step explains how to drive the notebook from the keyboard. If you have any difficulty reading the notebook on screen, start with the tutorial.

Everything in the repository is also available inside your Codespace, so you do not need to download anything to begin.

## Getting started — one time only

1. **Make your own copy.** Open this repository on GitHub and click the green **Use this template** button, then **Create a new repository**. Name it `MarketingAnalytics-YourLastName`, set it to **Private**, and click **Create repository**. From now on, work in *your* copy, never in the original.
2. **Open a Codespace.** On your repository, click the green **Code** button → **Codespaces** → **Create codespace on main**. The first build takes two to five minutes while it installs Python and the course packages. After that it opens in seconds.
3. **Check it works.** When VS Code appears in your browser, open `lessons/Class_1/` and open the notebook. Click **Run All** at the top. If every cell runs and shows output, you are ready.

If VS Code asks you to pick a kernel, choose the Python environment it suggests. There is only one.

The full setup guide — including GitHub Education for extra free hours, and what to do if a Codespace freezes on the campus network — is on Canvas.

## Working from campus

On the UTSA network a Codespace will often open and then **freeze when you run a cell**. Nothing is wrong with your setup; the campus firewall blocks the connection. Use the campus editor link from the Canvas setup guide instead. It opens the same Codespace in a window that works on campus. Bookmark it.

## Each week

1. Open your Codespace from [github.com/codespaces](https://github.com/codespaces), or create a new one from your repository if it has been deleted.
2. Open that week's folder under `lessons/`.
3. Open the HTML tutorial in a browser tab if you want the walkthrough, then open the notebook and work through it.
4. When you are done, save your work to GitHub (next section) and submit it to Canvas (section after).

Your work auto-saves inside the Codespace, but a Codespace is not permanent — GitHub deletes ones that sit unused for about a month. Anything you have not pushed to GitHub goes with it.

## Saving your work to GitHub — commit and sync

Do this at the end of every session. No command line is needed.

1. Save the notebook: **Ctrl+S** on Windows, **Cmd+S** on a Mac.
2. Click the **Source Control** icon in the left sidebar — it looks like a branching tree.
3. You will see the files you changed. Click the **+** beside each one to stage it, or the **+** beside **Changes** to stage all of them.
4. Type a short message in the box, such as `Finished Class 1 notebook`.
5. Click **Commit**.
6. Click **Sync Changes**. This pushes your commit to GitHub.

To check it worked, open your repository on github.com in a browser and look for your change. If it is not there, you committed but did not sync — go back and click **Sync Changes**.

You can commit and sync as often as you like. Pushing is how you *save*. It is not how you *submit*.

## Submitting an assignment to Canvas

Assignments are not collected from GitHub. You download the finished notebook from your Codespace and upload it to the Canvas assignment. Downloading from the Codespace keeps the outputs you just ran, so the grader sees your results without re-running anything.

1. In the Codespace, open the assignment notebook and click **Run All** so every cell shows its output. Check that the outputs are there, then save.
2. In the **Explorer** panel on the left, **right-click the notebook file** and choose **Download…**. The `.ipynb` file, with its outputs, saves to your computer.
3. Open the assignment in **Canvas** and upload that `.ipynb` file. Canvas accepts it as-is; do not convert it to PDF unless the assignment asks for one.
4. After uploading, open your submission in Canvas to confirm the right file is attached.
5. Commit and sync as well, so the same work is safe on GitHub.

**Always run and save before you download.** A notebook downloaded with empty output cells is graded as empty.

## If something goes wrong

| Problem | What to do |
| --- | --- |
| Codespace opens but freezes when I run a cell | You are probably on campus. Use the campus editor link from the Canvas guide. |
| `ModuleNotFoundError` when a cell runs | Open the terminal (**View → Terminal**) and run `pip install -r requirements.txt`, then restart the kernel and run the cell again. |
| `FileNotFoundError` reading the data | The notebook is looking in the wrong folder. Keep the data files in each week's `data/` folder and open the notebook from there. |
| My changes do not show on GitHub | You committed but did not sync. Open Source Control and click **Sync Changes**. |
| Codespace will not start | Delete it at [github.com/codespaces](https://github.com/codespaces) and create a new one from your repository. Anything you pushed is restored automatically. |
| Commit button is greyed out | You opened a Codespace on the original template instead of your copy. Go back to *Getting started*, step 1. |

If none of that resolves it, bring your laptop to office hours. Environment problems are far faster to fix in person than by email.

---

*Case materials © their original authors and used by permission. Notebooks and tutorials prepared for UTSA Marketing Analytics.*
