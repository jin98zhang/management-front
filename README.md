## 开发

```bash
# 克隆项目
git clone https://gitee.com/y_project/RuoYi-Vue

# 进入项目目录
cd ruoyi-ui

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装依赖，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 http://localhost:80

### 测试账号

> 流程管理账号：admin / admin123
>
> 请假流程测试账号
>
> 普通员工1：guanxing / 123456
>
> 普通员工2：zhoucang / 123456
>
> 部门领导1：guanyu / 123456
>
> 部门领导2：zhaoyun / 123456
>
> 人事：zhugeliang / 123456

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```