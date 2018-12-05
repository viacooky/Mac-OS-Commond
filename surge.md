### 使用 faketime 无限试用 Surge

- 下载编译 faketime

```sh
# 依赖
brew install coreutils

git clone https://github.com/wolfcw/libfaketime.git

cd libfaketime
make
sudo make install
```

- terminal 运行

```sh
faketime '2007-01-01 00:00:00' /Applications/Surge\ 3.app/Contents/MacOS/Surge\ 3 &
```

可以看到试用时间变化

- 由于需要使用 terminal 启动，考虑使用 Alfred Workflow 启动
