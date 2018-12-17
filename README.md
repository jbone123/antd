

##  安装
create-react-app xxoo

## 打开配置文件不可逆
npm run eject

## 模块安装
yarn add less less-loader antd babel-plugin-import axio

## 文件配置
webpack.config.dev.js
    
js模块
```js
    plugins: [
        ['import', [{ libraryName: "antd", style: true}]]
    ],
```
less模块
```js
    //less配置 jbone
      loader: require.resolve('less-loader'),
      loader: require.resolve('css-loader'),


       {
      loader: require.resolve('less-loader'),
      options: {
        modifyVars:{"@primary-color":"#1DA57A"},//默认样式修改
        // 是否激活js
        javascriptEnabled: true
      }
    }
```


webpack.config.pro.js和dev配置一样