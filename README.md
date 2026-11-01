# Job Blaster demo

Live: https://joshuameyer113geo.github.io/job-blaster-demo/

This repository contains **only the compiled static files** of a public demo of Job Blaster's try-it flow. It is a demo: all tailoring runs in the visitor's browser with simple sample logic (it reorders your bullet points and skills to match the job; it never adds facts). There is no server, no login, no AI, no API keys, no admin side and no stored data.

GitHub Pages serves these files from the `main` branch root; GitHub's built-in `pages-build-deployment` Actions workflow publishes each push. (A custom Actions workflow is ready to add once the deploy token has the `workflow` scope.)
