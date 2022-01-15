npm init -y
npm install -D webpack webpack-cli @webpack-cli/generators
mkdir webpack1
npx webpack init ./webpack1 --force --template=default
cd webpack1
npm install webpack-dev-server
npx webpack b
npx webpack s
