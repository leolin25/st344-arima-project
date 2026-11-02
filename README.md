# ST344 ARIMA Time Series Analysis

## Beforehand

1. Install GitHub Desktop (very beginner friendly for non Git users)
2. Check Emails for repository invite (you need to accept invite for repo)
3. Clone Repository and select this project "st344-arima-project" and give it a suitable folder

## Quick Start for Team Members

1. **Clone the Repository:** Open GitHub Desktop, go to **File > Clone Repository**, and select this project.
2. **Open the Project:** Double-click `st344-arima-project.Rproj` to launch RStudio with the correct working directory.
3. **Restore Packages:** In the RStudio console, run:
   renv::restore()
   
## Daily Git Workflow

Follow this 3-step routine in **GitHub Desktop** every time you work on the project to keep team files synced and prevent code overwrites:

### 1. START: Pull Latest Changes
* Open **GitHub Desktop**.
* Click **Fetch origin** (or **Pull origin**) in the top bar.
* *Goal:* Download updates pushed by teammates before you make local edits.

### 2. WORK: Edit & Save in RStudio
* Open `st344-arima-project.Rproj` in RStudio[cite: 1].
* Work on `ST344TeamARIMA.Rmd` or script files and save your changes[cite: 1].
* **If you install a new package:** Run `renv::snapshot()` in the R console to update `renv.lock`[cite: 1].

### 3. FINISH: Commit & Push Work
1. **Save All Files:** Ensure all open files in RStudio are saved.
2. **Review Changes:** Switch to **GitHub Desktop** to view modified files listed on the left panel.
3. **Commit Changes:**
   * Enter a brief description in the **Summary** box at the bottom left (e.g., *"Added ARIMA model diagnostics"*).
   * Click **Commit to main**.
4. **Push Changes:**
   * Click **Push origin** in the top bar.
   * *Goal:* Upload your updates to GitHub so your team can pull them.