# TVBoxMobile

基于
* [q215613905](https://github.com/q215613905)/[TVBoxOS](https://github.com/q215613905/TVBoxOS)

## APK 构建指南

详细构建教程请参考 [docs/APK_BUILD_GUIDE.md](docs/APK_BUILD_GUIDE.md)

### 快速构建

```bash
chmod +x gradlew
./gradlew assembleRelease
```

构建产物: `app/build/outputs/apk/release/MBox_v*.apk`

### GitHub Actions 自动化构建

本项目支持 GitHub Actions 自动化构建:
- **Test Build**: 手动触发，构建测试 APK
- **Release Build**: Git Tag 触发，自动构建并发布

配置详见 [构建指南 - GitHub Actions](docs/APK_BUILD_GUIDE.md#6-github-actions-自动化构建)

## Build
[Github Actions](https://github.com/XiaoRanLiu3119/MBox-Build/actions)

精力有限,未必会及时维护,仅用于学习

## 推荐使用
[takagen99](https://github.com/takagen99/Box)
[FongMi](https://github.com/FongMi/TV)