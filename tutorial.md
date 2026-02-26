First things first, make sure you fork the repo, clone it, etc. etc.

Now to begin our tutorial!

0. Install pytest (only needed once)

**You can run with** ```python3 -m pip install pytest```

1. Run main.py to see your current results
- If you notice anything weird in main.py, great!
- However, this wants you to get used to debugging WITH Github actions.

**You can run with** ```python3 main.py```

2. Run main_test.py
- Let's see where do we find errors!

**You can run with** ```python3 -m pytest main_test.py```

3. Push your changes and watch the pipeline run
- Commit and push to `main` on your fork
- Open the **Actions** tab on your fork on GitHub and click the latest run
- Red ❌ means a step failed. Click into the failing step to read the log, fix the problem, and push again until it's green ✅

Really, it'll be ideal if you can use the GitHub Actions docs:

https://docs.github.com/en/actions
