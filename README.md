# ymca_hp
## How to Set Up
### Set up npm
- for Mac PC
0. `node -v` ...check your node.js has been installed.
  -> if you get response for example v12.3.0, skip 1~3
1. `brew -v` ...check you have homebrew. -> if you have homebrew, skip 2
2. ```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"```...install homebrew.
  when it finished, you check `brew -v` and it is successful when you get response!
3. `brew install nodebrew` ...install nodebrew, this is manager of node.js version.
4. `nodebrew install-binary v14.15.4` ...install node.js ver of this is used by our project.
5. `nodebrew user v14.15.4`...Use node.js by v14.15.4.
6. `vi ~/.zshrc` and press "i" key to use insert mode, to write `export PATH=$HOME/.nodebrew/current/bin:$PATH`. when finished it, press "esc", and next type ":wq" to save this change.
7. `source ~/.zshrc`...make node.js of this version available.
  And you can "npm", this is manager package(library) of node.js.
8. `npm -v `...check your npm version.
  and when your npm version below "5.2.0" run `npm install -g npm`
### clone to your PC
- `git clone git@github.com:Hopin-inc/ymca_hp.git`
  - If you haven't set up github or ssh of github, check below link
    [GitHubでssh接続する手順〜公開鍵・秘密鍵の生成から〜](https://qiita.com/shizuma/items/2b2f873a0034839e47ce)
    [githubからsshでクローンする。sshでpushする](https://qiita.com/dorara/items/942485e064f3e2bdd4f7)

## How to Develop
### make your local branch
- `git pull origin develop`...can your branch use now update latest developing version.
- `git branch [branch name] `...can make branch from the branch used by you now.

### make the same environment as this project in your PC
- check your current directory "ymca_hp_nuxt"
- `mpm install` ...this can install packages referenced by package.json and package-lock.json

### push your code to origin branch
- `git add .` ...regist(stage) your change of this project.
- `git commit -m "[commit message]"` ... confirm your change in local
- `git push origin [origin branch name]`...regist(push) your change in remote branch and compare to merge it.

## How to Run in Local Environment
- check your current directory "ymca_hp_nuxt"
- `npm run dev` ...start local server.

## How to Deploy
- check your current directory "ymca_hp_nuxt"
- `npm run build`...this make project minified.
- `npm run start`...start server by production mode.
