# web @vue/cli 项目
| 环境依赖 | 依赖版本 |
|:----:|:----:|
| vue | 2.5.2 |
| node | 10.15.3 |
| npm | 6.9.0 |
# web vite2 项目
| 环境依赖 | 依赖版本 |
|:----:|:----:|
| vue | 3.X |
| node | 12.x |
| npm | - |

### 项目结构目录
├── build                                       # webpack配置文件 <br/>
├── config                                      # 项目打包路径 <br/>
├── src                                         # 源码目录 <br/>
│   ├── assets                                  # 公共资源， 公共css <br/>
│   ├── components                              # 公共组件 <br/>
│   ├── mock                                    # 异步模拟ajax调用接口 <br/>
│   ├── router                                  # 路由相关 <br/>
│   ├── vuex                                    # 状态管理相关 <br/>
│   ├── utils                                   # 工具类，方法 <br/>
│   ├── views                                   # 页面相关 <br/>
│   ├── App.vue                                 # 页面入口文件 <br/>
│   └── main.ts                                 # 程序入口文件，加载各种公共组件 <br/>
└── index.html                                  # 入口html文件 <br/>
# 多版本node管理切换 nvm