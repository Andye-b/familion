# Familion

Calendario familiar de 3 depas (203, 809, Vail 753) y 6 casas.

**Version actual: 0.4 Casa**

- App: un solo `index.html`
- Hosting: Firebase `familion-25fb1` → https://familion-25fb1.web.app
- Repo: https://github.com/Andye-b/familion

## Como trabajar

```bash
git clone https://github.com/Andye-b/familion.git
cd familion
# edita index.html
git add -A && git commit -m "cambio" && git push
firebase deploy --only hosting --project familion-25fb1
```

La primera vez copia el HTML 0.4:

```bash
cp ~/Downloads/familion-live.html ./index.html
git add index.html firebase.json .firebaserc
git commit -m "v0.4 Casa"
git push
firebase deploy --only hosting --project familion-25fb1
```

## 0.4 Casa

- Calendario lista / semana / mes / ano
- Filtro compacto
- 22 personas sin login Google
- Subdivision por familia
- Clon Firestore calendario/oficial
