# vscode 安装 Settings Sync 插件同步设置

## github 生成 Access Token

### 登录 github 进入`Settings / Developer settings`配置界面，点击`Generate new token`

![github_developer_settings](./images/github_developer_settings.png)

### 生成新的 Access Token，勾选 gist

![github_create_access_token](./images/github_create_access_token.png)

### 记录生成的 Access Token

```github token
vscode_settings_sync: 72f059042c5458d257a2173abbd09d8ac4840ecb
```

![github_access_token](./images/github_access_token.png)

## vscode Settings Sync 插件配置

![vscode_settings_sync](./images/vscode_settings_sync.png)

### 1. 登录 github 并列出所有 gists，选择一个 gists 同步数据（如果还没有 gists 的话会自动创建一个）

![vscode_select_gist](./images/vscode_select_gist.png)

### 2. 打开 vscode Settings Sync 配置页，输入 Gist ID（执行第 1 步后会自动填上），输入令牌（即 github `Developer settings`生成的 token）

![vscode_settings_sync_configuration](./images/vscode_settings_sync_configuration.png)

## 登录 github 查看同步结果

![github_gists](./images/github_gists.png)
