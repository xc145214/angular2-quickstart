# angular2 quick start

> 在终端窗口运行 `node -v`` 和 `npm -v`` ，来确认你的 `node`` 版本为 `v5.x.x` ， `npm` 版本为 `3.x.x` 。 老版本会出错。

##1. 创建并配置项目

**创建项目目录**

```
mkdir angular2-quickstart
cd    angular2-quickstart
```

**添加包定义与配置文件**

+ package.json 列出了“快速起步”应用的依赖，并定义了一些有用的脚本。 参见 npm 包配置 了解详情。
+ tsconfig.json 是 TypeScript 的编译器配置文件。 参见 TypeScript 配置 了解详情。
+ typings.json 指定 TypeScript 定义文件。 参见 TypeScript 定义文件 了解详情
+ typings.json identifies TypeScript definition files. See TypeScript Configuration for details.
+ systemjs.config.js 是 SystemJS 的配置文件。 参见 下面的讨论 。


**安装依赖包**

```
npm install
npm run typings install
```