# VueJS test project

## Description
This repo was created to learn VueJS! 

## Old build procedure
``` bash
# Clone the repo
git clone https://github.com/daxAKAhackerman/test-project

# Install dependencies
npm install

# Fix any vulns
npm audit fix

# Lint the code
npm run lint

# Build the app
npm run build
```

## New build procedure
``` bash
# Clone the repo
git clone https://github.com/daxAKAhackerman/test-project

# Use my build script! (I'll make it available eventually)
# The --unsafe flag can be used to remove the protections that I have placed on the package.json file
# FLAG-1: HF-tyNjuXASYW4bJQw1cSNZrRQtLKCA34sp
bash build SRC_FOLDER DST_FOLDER [--unsafe]
```

## Even newer build procedure
Use the deployment Web app! 
> The 'unsafe' GET parameter can be added to achieve pretty much the same thing as mentionned above
