# MiraiGo-module-setu-repo

ID: aimerneige.test.setu

Module for [MiraiGo-Template](https://github.com/Logiase/MiraiGo-Template)

## 功能

在群聊中接受到指定消息时发送特定的消息和色图。

## 使用方法

在适当位置引用本包

```go
package example

imports (
    // ...

    _ "github.com/aimerneige/MiraiGo-module-setu-repo"

    // ...
)

// ...
```

编辑你的配置文件 `seturepo.yaml`：

```yaml
"来点萝莉":
  - "太变态了！不可以!"
  - "/home/aimerneige/Pictures/luoli/"
"刻晴老婆":
  - "好耶，是刻晴"
  - "/home/aimerneige/Pictures/wallpaper/"
```

在你的 `application.yaml` 里填入配置来指定配置文件路径（默认 `./seturepo.yaml`）：

```yaml
aimerneige:
  seturepo:
    path: "./config/seturepo.yaml"
```