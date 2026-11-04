# jpomarketing9.github.io

GitHub Pages-site. Kun `public/` udgives, via `.github/workflows/deploy-pages.yml`.

## Rules

- public-encrypted/ må aldrig committes eller pushes (står i .gitignore, brug aldrig git add -f) - repoet er offentligt, så alt committet kan læses på github.com.
- Forsiden (public/index.html) må aldrig liste kundenavne - kunder kommer ind via deres kundekode (= mappenavn i public/). Fortrolige rapporter skal krypteres, da kundekoden ikke er en adgangskode.
- Kør altid git pull før ændringer - der publiceres også fra andre mapper/sessioner (lokal main var bagud ift. origin 4/11)
