初始化 git 仓库

```bash
git init
```

添加 .gitignore

```bash
echo .idea > .gitignore
```

```bash
git add .gitignore
```

```bash
git commit -m "init .gitignore" .gitignore 
```

添加 README.md

```bash
git add README.md
```

```bash
git commit -m "init README.md" README.md 
```

创建一个 Vue 应用

```bash
pnpm create vue@latest
```

```shell
cd vue-project
```

```sh
pnpm install
```

```sh
pnpm dev
```

初始化 storybook

```shell
pnpm dlx storybook@latest init
```

```shell
pnpm run storybook
```



