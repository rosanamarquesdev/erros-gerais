# erros-gerais

# 👇 update npm to the latest version
npm install -g npm@latest

# 👇 clean npm cache
npm cache clean --force

# 👇 delete node modules and package-lock.json 
npm rm -rf node_modules && rm package-lock.json

# 👇 retry installing dependencies
npm install
