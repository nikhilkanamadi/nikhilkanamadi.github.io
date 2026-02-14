# Host this resume on GitHub Pages (github.io)

## 1. Create the repository on GitHub

1. Go to **https://github.com/new**
2. **Repository name:** use **`nikhilkanamadi.github.io`** so your site is at **https://nikhilkanamadi.github.io**
   - (Or use any name like `resume`; then the URL will be `https://nikhilkanamadi.github.io/resume`)
3. Choose **Public**, leave "Add a README" **unchecked**
4. Click **Create repository**

## 2. Push your code

In the project folder, run (replace `nikhilkanamadi` with your GitHub username if different):

```bash
git remote add origin https://github.com/nikhilkanamadi/nikhilkanamadi.github.io.git
git branch -M main
git push -u origin main
```

Log in with your GitHub account when prompted.

## 3. Turn on GitHub Pages

1. In the repo, go to **Settings** → **Pages**
2. Under **Build and deployment**, **Source** choose **Deploy from a branch**
3. **Branch:** `main`, **Folder:** `/ (root)`, then **Save**

After a minute or two, your site will be live at **https://nikhilkanamadi.github.io**.
