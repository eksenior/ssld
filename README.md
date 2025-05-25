# ssld
![Version](https://img.shields.io/badge/version-1.0-green)

## English | [中文](#中文)

### 🚀 Features
- mach-o code pseudo signature
- extract entitlements/cms
- unpack fat mach-o

### 🛠 Usage
```python
# pseudo signature
ssld -s binary.dylib
# pseudo signature and attachment: identifier + entitlements.xml + cms.der
ssld -s binary.dylib -ident testname -e entitlements.xml -cms cms.der
# clear signature
ssld -cls binary.dylib
```

---

## 中文

### 🚀 功能特性
- mach-o代码伪签名
- 提取entitlements/cms
- 拆开fat mach-o多架构

### 🛠 使用示例
```python
# 伪签名
ssld -s binary.dylib
# 伪签名并附加：identifier + entitlements.xml + cms.der
ssld -s binary.dylib -ident testname -e entitlements.xml -cms cms.der
# 清空签名
ssld -cls binary.dylib
```

