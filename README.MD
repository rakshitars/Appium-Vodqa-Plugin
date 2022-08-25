npm run build
export APPIUM_HOME=/tmp/some-temp-dir

./node_modules/.bin/appium plugin install --source=local .
./node_modules/.bin/appium plugin list
./node_modules/.bin/appium server -ka 800 --use-plugins=Vodqa-plugin --base-path /wd/hub