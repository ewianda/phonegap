# phonegap
sudo apt-get install nodejs npm nodejs-legacy 
sudo npm install -g phonegap
sudo apt-get install ant
sudo apt-get install openjdk-7-jre
sudo apt-get install openjdk-7-jdk
wget http://dl.google.com/android/android-sdk_r24.4.1-linux.tgz
tar -xvzf android-sdk_r24.4.1-linux.tgz 
sudo mv android-sdk-linux /usr/local/

npm init

npm install babel-cli babel-core babel-preset-es2015 babel-preset-react  babel-preset-stage-0 --save-dev
echo '{\n  "presets": ["es2015", "stage-0","react"]\n}' > .babelrc

npm install webpack babel-loader file-loader webpack-dev-server --save-dev
