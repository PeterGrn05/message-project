# Как включить локально проект:
curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
sudo apt update && sudo apt install yarn
В root используем yarn
переходим  через cd server/ -> используем yarn, возвращаемся обратно cd ..
переходим  через cd client/ -> используем yarn, возвращаемся обратно cd ..
node –version (НУЖНО использовать 16-ую ноду)
Nvm use 16
Yarn start
Ждем когда будет доступен либо локальный порт 3000 или сам откроется.


