
# Line-bot-python-simple-starter

## 安裝所需要的外部模組
```
$ pip install line-bot-sdk flask pyquery
```

# 環境變數範例

請設置在 .env 檔案中

```
LINE_CHANNEL_SECRET=
LINE_CHANNEL_ACCESS_TOKEN=
OPENAI_API_KEY=
```

## 說明

本範例改寫於[line-bot-sdk-python](https://github.com/line/line-bot-sdk-python)，較適合初次接觸聊天機器人架設的人使用。

### 如何安裝Git並設置Git

請至Git的[官方網站](https://git-scm.com/)下載並安裝Git

初次安裝好Git請透過終端機輸入以下指令：
```
git config --global user.name 你的使用者名稱
git config --global user.email 你的Email
```

# 將專案推送到Github repo
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Fangvan/line-conversation-robot.git
git push -u origin main