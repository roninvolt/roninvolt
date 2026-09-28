# 🚀 How to Publish Your New GitHub Profile README

Your profile README has been generated in [`README.md`](README.md) along with your custom high-tech hero banner in [`assets/banner.jpg`](assets/banner.jpg).

Follow these quick steps to make it go live on your GitHub profile:

---

### Method 1: Via GitHub Web Interface (Quickest ~ 1-2 Mins)

1. Go to **GitHub** and make sure you are logged into your account: [github.com/roninvolt](https://github.com/roninvolt).
2. Click the **`+`** icon in the top right corner and select **New repository**.
3. In the **Repository name** field, type **`roninvolt`** (must match your username exactly in lowercase).
   > GitHub will display a special message: *"You found a secret! `roninvolt/roninvolt` is a ✨special✨ repository that you can use to add a `README.md` to your GitHub profile."*
4. Ensure the repository visibility is set to **Public**.
5. Check the box **"Add a README file"** and click **Create repository**.
6. On the new repository page, click the pencil icon ✏️ to **Edit** the `README.md`.
7. Replace the default text with the contents of your generated [`README.md`](README.md).
8. To include the banner:
   - Click **Add file** -> **Upload files**, upload [`assets/banner.jpg`](assets/banner.jpg) inside an `assets` folder (or simply drag and drop `banner.jpg`).
9. Commit your changes. Visit your profile at [github.com/roninvolt](https://github.com/roninvolt) to see your new live profile!

---

### Method 2: Via Git Command Line

If you have Git configured locally:

```bash
# In this directory (c:\Users\Volt\Documents\Readme Volt):
git init
git branch -M main
git add .
git commit -m "feat: initial release of interactive profile README"
git remote add origin https://github.com/roninvolt/roninvolt.git
git push -u origin main --force
```

---

### 🎨 Your Verified Contact & Community Links

All your links have already been populated into [`README.md`](README.md):

- [x] **Portfolio**: Connected to [roninvolt.vercel.app](https://roninvolt.vercel.app/)
- [x] **Discord Server**: Connected to your active community invite [discord.com/invite/uUjqYU4dRp](https://discord.com/invite/uUjqYU4dRp)
- [x] **Email**: Connected to `roninvolt1@gmail.com`
- [x] **GitHub**: Connected to [github.com/roninvolt](https://github.com/roninvolt)

---

### 🖥️ Local Preview

To preview your README right in your web browser:
1. Double-click or open [`preview.html`](preview.html) in your browser (e.g. Chrome, Edge, Brave).
2. It renders using GitHub's exact dark markdown stylesheet and live SVG widgets!
