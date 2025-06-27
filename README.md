# OCTRA Wallet Generation Guide (Via Codespace)

This guide walks you through generating an OCTRA wallet using [Codespaces](https://github.com/features/codespaces) and [Bun](https://bun.sh).

---

## 🚀 Step-by-Step Instructions

### 🔹 Step 1: Install Bun

```bash
curl -fsSL https://bun.sh/install | bash
source ~/.bashrc
bun --version
```

---

### 🔹 Step 2: Install Dependencies

```bash
bun install
```

---

### 🔹 Step 3: Build the Project

```bash
bun run build
```

---

### 🔹 Step 4: Start the Server

```bash
bun start
```

✅ After this, click the “PORTS” tab in Codespace and open `localhost:8888` in your browser.

---

## 💡 Notes

- Make sure your Codespace is set up with Bun properly.
- If any issues occur, recheck your `.bashrc` or re-run installation steps.

---

## 📄 License

MIT
