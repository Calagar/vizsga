# Vizsga feladat!

Ebben a fajlban reszetesen leirtam milyen parancsokat hasznaltam a feladat elvegzesehez, minden parancsot consolbol futtatam.

# Parancsok

**mkdir vizsga**
**cd vizsga**
**git clone https://github.com/szabopeter92/git-vizsga**
**git init**
**git remote add origin https://github.com/Calagar/vizsga.git**
**git remote -v**
**cd git-vizsga**
**touch README.md**
**touch .gitignore**
** echo -e '*.txt\n*.doc\n*.docx\n*.pdf' >> .gitignore **
**vi README.md**
**git add .gitignore README.md**

**git commit -m "README.md es .gitignore letrehozasa"**

** git branch console**
** git checkout/switch console**
** app js file modositasa line 21:**
**window.addEventListener('load', function() {
console.log("Az oldal sikeresen betöltődött");
});**
**style.css modositasa hatter valtoztatas**
**background-image: linear-gradient(205deg, rgba(34,193,195,1) 31%, rgba(253,187,45,1) 81%);**
**git add **
**git commit -m "app.js es style.css modositasa"**
**git push -u origin console master**
