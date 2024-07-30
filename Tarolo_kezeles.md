tároló címe: https://github.com/harsanyijanos/hj_proba.github.io.git
# tenivalok új tárolok létrehozásánál
echo "# hj_proba.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/harsanyijanos/hj_proba.github.io.git
git push -u origin main
# felpakolás már létező (és használt) tároló esetén
git remote add origin https://github.com/harsanyijanos/hj_proba.github.io.git
git branch -M main
git push -u origin main
# szinkronizálás
git checkout main
git pull --rebase origin
