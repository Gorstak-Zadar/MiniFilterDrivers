# 🔧 MiniFilterDrivers

> Batch script to **unload and remove** BFS and UnionFS minifilter drivers — `fltmc unload`, takeown, icacls, delete.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🗑️ **Unload** | `fltmc unload bfs`, `fltmc unload unionfs` |
| 🔒 **Takeown** | Takes ownership of driver .sys files |
| 📋 **icacls** | Resets and modifies ACLs |
| 🧹 **Delete** | Removes bfs.sys, unionfs.sys |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **Privileges** | Administrator |

---

## 🚀 Usage

```cmd
:: Run as Administrator
MiniFilterDrivers.cmd
```

---

<p align="center">
  <sub>🔧 Gorstak System Utilities</sub>
</p>
