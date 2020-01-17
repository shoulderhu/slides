# Installation
```bash
git clone https://github.com/shoulderhu/slides.git
cd slides
git checkout --orphan gh-pages
wget https://github.com/hakimel/reveal.js/archive/3.8.0.zip
unzip 3.8.0.zip
mv reveal.js-3.8.0/* .
rm -rf 3.8.0.zip reveal.js-3.8.0/
git add -A
git commit -m "revealjs 3.8.0"
git push -u origin gh-pages
```

# Running
```bash
npm install
npm start
# npm start -- --port 8001
```