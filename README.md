# webpack-playlist

1. npm init
2. npm install webpack --save-dev ( npm install webpack -g )
3. $ webpack ./script-1.js ./bundle.js

         Version: webpack 1.14.0
         Asset     Size  Chunks             Chunk Names
         bundle.js  1.55 kB       0  [emitted]  main
                     [0] ./script-1.js 55 bytes {0} [built]
                     [1] ./script-2.js 34 bytes {0} [built]

4. $ npm install babel-core babel-loader babel-preset-es2015 --save-dev ( http://babeljs.io/ )

5.  $ npm install style-loader css-loader --save-dev

6.  $ npm install node-sass sass-loader --save-dev

            앞으로 webpack.config.js 파일안에 아래 형식을 그대로 사용할것

            {
                test: /\.scss$/,
                loader: 'style-loader!css-loader!sass-loader'
            }
            
