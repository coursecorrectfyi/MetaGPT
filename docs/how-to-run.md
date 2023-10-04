```shell
export PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true

npm install @mermaid-js/mermaid-cli

python -m venv metagpt

source metagpt/bin/activate

python startup.py "Design a MOOC recommendation platform frontend with a user interface similar to roamaround.io, using Next.js. The home page should have a 'Stream of study' search bar and an educational video in the background. The results page should be split into a chat window and a results list. The chat window should have quick reply options. The results list should show courses with details and two CTAs - 'Details' and 'Enroll'. If two or more courses are selected, a 'Compare' button is enabled. Assume backend exists, only build the frontend."
```

