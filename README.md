# Install 
```
mkdir $HOME/src
cd $HOME/src
git clone https://github.com/gohugoio/hugo.git
cd hugo
go install
sudo cp /datago/bin/hugo /usr/bin/

If you want to compile with Sass/SCSS support use --tags extended and make sure CGO_ENABLED=1 is set in your go environment. If you don't want to have CGO enabled, you may use the following command to temporarily enable CGO only for hugo compilation:

CGO_ENABLED=1 go install --tags extended

```
# add theme
```
git init

git submodule add https://github.com/apvarun/blist-hugo-theme.git themes/blist

cd themes/blist/exampleSite/

hugo serve --themesDir ../..

npm i && hugo -D --gc

// npm install -g autoprefixer
// npm install -g postcss-cli
// npm install -g postcss

hugo serve -D --themesDir ../.. --baseUrl="t2pcode.t2p.co.th:1000" --port=1000
hugo serve  --themesDir ../.. --baseUrl="https://t2pcode.t2p.co.th/chubitora" --port=1000
hugo serve --baseUrl="https://t2pcode.t2p.co.th/chubitora" --port=1000
```