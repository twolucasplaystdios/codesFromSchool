# 作業整理

## 特色
- 我的作業，但是是用 C++

## 安裝與編譯步驟
請確保系統已安裝 `CMake` 與支援 C++17 的編譯器 (如 GCC, Clang 或 MSVC)。

```bash
# 克隆專案
git clone https://github.com/twolucasplaystdios/codesFromSchool.git
cd my-cli-tool

# 建立編譯資料夾並編譯
mkdir build && cd build
cmake ..
cmake --build .
```
編譯完成後，你會在 `build` 資料夾內看到 `runmyhw` 可執行檔。