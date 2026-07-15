# Belleza

Bu loyiha oddiy statik HTML/CSS/JavaScript sayt bo'lib, Vercel orqali tezda joylashtirish uchun tayyor.

## Lokaldas ko'rish

```bash
python -m http.server 8000
```

Keyin brauzerda http://localhost:8000 oching.

## GitHub va Vercel ga joylashtirish

1. GitHubda yangi repository yarating.
2. Quyidagi komandalar bilan kodni yuboring:

```bash
git add .
git commit -m "Initial deployment"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO.git
git push -u origin main
```

3. Vercel.com da "Add New Project" -> GitHub repository tanlang.
4. Build command va Output directory ni qoldiring (bu statik loyiha uchun kerak emas).
5. Deploy tugmasini bosing.
