# PCL Miku Realtime Home

实时生成 Minecraft API 状态与官方新闻的 Miku 横屏 PCL 主页。

## PCL 地址

```text
https://raw.githubusercontent.com/minecraftmc22/pcl-miku-realtime-home/main/Custom.xaml
```

GitHub Actions 每 30 分钟更新一次 `Custom.xaml` 和 `Custom.xaml.ini`，也可以在 Actions 页面手动运行 `Update PCL homepage`。

## 本地调试

```powershell
py realtime_home_server.py
```

本地地址：`http://127.0.0.1:8765/Custom.xaml`
# pcl-miku-realtime-home
