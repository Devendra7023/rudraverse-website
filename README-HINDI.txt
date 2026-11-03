RUDRAVERSE GITHUB PAGES WEBSITE

Publish karne se pehle:
1. index.html, privacy.html aur terms.html mein rudraverse.media@gmail.com ko apne active contact email se replace karein.
2. GitHub par ek naya public repository banayein, naam: rudraverse-website
3. Is ZIP ke andar ki files (ZIP folder khud nahi) repository ke root mein upload karein.
4. Repository Settings > Pages > Build and deployment mein:
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   Save karein.
5. GitHub Pages ka URL kuch aisa hoga:
   https://YOUR-GITHUB-USERNAME.github.io/rudraverse-website/
6. Website open karke Home, Privacy Policy aur Terms teeno pages test karein.
7. Google Cloud > Google Auth Platform > Branding mein:
   Application home page = GitHub Pages ka home URL
   Application privacy policy link = home URL ke saath privacy.html
   Application terms of service link = home URL ke saath terms.html
8. Authorized domains mein github.io add karein (sirf agar Google console is domain ko accept kare; domain verification instructions follow karein).

IMPORTANT:
- Placeholder email ko replace kiye bina publish na karein.
- Privacy policy mein likhi practices ko actual deployed automation ke saath match karna zaroori hai.
- client_secret.json aur token.json ko GitHub repository mein kabhi upload na karein.
