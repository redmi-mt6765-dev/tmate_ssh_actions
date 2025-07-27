# 🔧 Debug GitHub Actions

This GitHub Action lets you **SSH into a live GitHub Actions runner** using [tmate.io](https://tmate.io), so you can debug failing builds, inspect file systems, test commands, or just vibe with your CI pipeline in real-time.

---

## 🚀 What It Does

- Starts an ephemeral Ubuntu runner
- Sets up a secure `tmate` SSH session
- Displays an SSH connection string in the logs
- Lets you connect via terminal to debug manually

---

---

### ⏹️ How To Stop

```bash
sudo touch \continue
```

---

### 📃 Licence:

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
