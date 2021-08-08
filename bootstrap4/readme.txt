#npm package install
npm init
npm install lite-server --save-dev
npm install bootstrap@4.0.0 --save
npm install jquery@3.3.1 popper.js@1.12.9 --save
npm install font-awesome@4.7.0 --save
npm install bootstrap-social@5.1.1 --save


#server run
npm start

#dist folder preparation
npm install --save-dev onchange@3.3.0 parallelshell@3.0.2
npm install --save-dev rimraf@2.6.2
npm -g install copyfiles@2.0.0
npm -g install imagemin-cli@3.0.0
npm install --save-dev usemin-cli@0.5.1 cssmin@0.4.3 uglifyjs@2.4.11 htmlmin@0.0.7

npm run build
