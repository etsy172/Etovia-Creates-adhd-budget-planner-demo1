FREE DEMO PAGE: ADHD BUDGET PLANNER
===================================
This folder is a static website (no build step, no server code).
  index.html   the demo page
  assets/      screenshots of the sample planner

STEP 1: ADD YOUR ETSY LINK
Open index.html in a text editor. Near the bottom, find:
    const ETSY_URL = "PASTE_YOUR_LISTING_URL_HERE";
Replace the text between the quotes with your listing URL (it must start with https://).
Until you do, the "Get the full planner on Etsy" buttons stay hidden.

STEP 2: TEST LOCALLY
Double-click index.html. Try the tabs and both calculators.

STEP 3A: PUBLISH ON GITHUB PAGES (free)
1. Create a free account at github.com and click New repository (name it e.g. budget-planner-demo, set Public).
2. Click "uploading an existing file" and drag in index.html AND the assets folder. Commit.
3. Open the repository Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", Branch "main", folder "/ (root)", then Save.
5. After a minute your link appears at the top of that page, like:
   https://YOUR-USERNAME.github.io/budget-planner-demo/

STEP 3B: PUBLISH ON VERCEL (free hobby plan)
1. Create a free account at vercel.com.
2. Easiest: push this folder to a GitHub repository (Step 3A, steps 1-2), then in Vercel click Add New > Project, import that repository, and click Deploy. No settings needed.
3. Your link looks like: https://your-project-name.vercel.app
   (Vercel's free hobby plan is intended for non-commercial use. Check Vercel's current terms, because promoting a shop may count as commercial. GitHub Pages is the safer choice if unsure.)

STEP 4: ADD THE LINK TO ETSY
Put the link in your listing description (for example "Try the free demo: <link>") and in your listing FAQ. Etsy generally allows links, but does not allow sending buyers off-site to complete a purchase. Check Etsy's current policies.

NOTES
- The demo shows screenshots and two small calculators only. It does not include your Excel file or formulas.
- Nothing typed in the calculators is stored or sent anywhere.
- To update screenshots later, replace the PNG files in assets/ using the same file names.
