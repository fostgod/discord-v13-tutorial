### 1. To Install NodeJs v16 Copy This Given Code And Paste In Shell Of Replit.
```
npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH
```

### 2. Create the .replit file to execute node from the shell instead of the console, and insert this in that file.
```
run="npm start"
```

### 3. Add the start script in your package.json file
```
"scripts": {
  "start": "node ."
}
```

### 4. Install DiscordJS v13
```
npm i discord.js
```

Thanks README from FlameQuard
