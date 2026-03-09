# 💍 Sneha & Ezaz — Wedding Invitation

Beautiful animated wedding invitation for **Sneha & Ezaz**, 2nd May 2026, Katiahat.

## 📁 Folder Structure

```
wedding-invitation/
  photos/
    bride.jpeg    ← Sneha's photo
    groom.jpeg    ← Ezaz's photo
  index.html
  README.md
```

## 🚀 Hosting on GitHub Pages (ezaznitd.me/wedding-invitation)

Since your custom domain `ezaznitd.me` is already pointing to your GitHub Pages root, host this as a **sub-repo**:

1. Create a new GitHub repo named exactly **`wedding-invitation`**
2. Push the contents of this folder to that repo:
   ```bash
   cd /Users/ezaz/Desktop/wedding-invitation
   git init
   git add .
   git commit -m "Initial wedding invitation"
   git branch -M main
   git remote add origin https://github.com/ezaznitd/wedding-invitation.git
   git push -u origin main
   ```
3. Go to the repo → **Settings → Pages**
4. Under **Source**, select `main` branch, `/ (root)` → **Save**
5. Your site will be live at: **https://ezaznitd.me/wedding-invitation**

> If the site shows a 404, wait 2–3 minutes for GitHub Pages to build, then hard refresh.
