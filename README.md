## 部署在uf的个人主页

- 查看天气(使用高德api)
- 查看个人简历
- 提供个人联系方式
- 播放音乐

![效果图](https://08cb9bad.telegraph-image-qjf.pages.dev/file/cc29daab464ee9d7ab8e0.png)

## 部署方法
> 本项目使用vite构建，需要安装pnpm
```bash
# 安装pnpm
npm install -g pnpm
# 安装依赖
pnpm install
# 预览
pnpm dev
``` 
> 修改 `.env-github` 文件为 `.env`

> 修改 `.env` 文件中的 `VITE_SITE_URL` 为你的网站地址, 应该是 `cise.ufl.edu/~用户名`

构建项目
```bash
pnpm build
```

将`dict`文件夹内的所有文件上传到uf的`public_html`目录下，然后访问 `https://cise.ufl.edu/~用户名` 即可。
### 鸣谢
Fork自[imsyy](https://github.com/imsyy/home)
