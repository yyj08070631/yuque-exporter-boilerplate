# yuque-exporter-boilerplate

Follow steps below to download markdown files of your Yuque articles, without any code and command

## Step 1 - Create a private repo from boilerplate

- "Create a new repository"
<img width="1524" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/694a388c-5764-4a5b-8fa0-cf09131f46ef">

- Set private
<img width="808" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/d63bbb5f-d4a0-4956-9f16-e2de9afe8e42">

## Step 2 - Setup YUQUE_TOKEN and run the workflow

- Setup YUQUE_TOKEN in Settings/Secrets
- YUQUE_TOKEN is required, you can apply it on https://www.yuque.com/settings/tokens
<img width="1263" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/b3919df2-bb55-4c69-98fb-d12ed213b956">

- Setup REPOS in Settings/Variables
- REPOS is optional, you can specify several repos you want like "bufeidefeiyang/blog bufeidefeiyang/test"
- If empty, all repos would be exported
<img width="1267" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/8fe59ff9-a7db-433d-b69d-d8a39509c2fa">

- Run the only job
<img width="1654" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/635ee284-790c-418f-8481-cb22058acdd0">

- Success
<img width="663" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/92d7bba6-f4a8-4c87-b3ad-ea706dfa3f95">

- Markdown files would be pushed to <repo_name>/storage
<img width="903" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/c0926703-4d4c-4ced-bec1-3f33a65efe8e">

## Step 3 - Download files without code and command

- Download Github Desktop
<img width="969" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/c2997edd-c8ef-4227-b79e-82063eb403dd">

- Sign in Github
<img width="960" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/9c71151c-1d40-4701-b6e6-2544945db932">

- Select your repo then clone to local
<img width="960" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/c81f9f43-7c3f-4d56-b1b7-ee9732c24ca7">

- Click "Show in Finder" to browse your Markdown files
<img width="960" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/16a9d4a6-df33-40f3-8072-8f8c8676ae2e">

- Click "Fetch origin" to get latest acticles from Github repo
<img width="960" alt="image" src="https://github.com/yyj08070631/yuque-exporter-boilerplate/assets/27988527/df3347ec-fb4e-43cc-89b7-9af331458c14">
