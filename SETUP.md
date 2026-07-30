# Setting this up on your profile

1. **Create the special repo** (if you haven't already): go to GitHub → New repository → name it exactly `noahadeleye17-coder` (must match your username). Make it **public**.
2. Add `README.md` (and the `.github/workflows/snake.yml` file) to the root of that repo, then commit and push.
3. **Enable the snake workflow's permissions:**
   - Go to the repo → Settings → Actions → General → under "Workflow permissions," select **Read and write permissions**, then Save.
   - Go to the repo → Actions tab → find "Generate Snake" → click "Run workflow" once manually the first time (it also auto-runs daily via the cron schedule).
   - This will create an `output` branch with the animated snake SVGs the README links to.
4. Give it a minute, then check `github.com/noahadeleye17-coder` — your profile page should now show the new README with stats, streak, trophies, and the snake animation.

### Notes
- The GitHub stats, streak, and trophy images are all live badges pulling from your public GitHub activity — no setup needed beyond the repo existing and being public.
- If any stat image doesn't load right away, GitHub's badge services sometimes cache for a few minutes — refresh after a bit.
- Swap in a real profile photo, banner, or extra project cards any time by editing `README.md` directly on GitHub.
