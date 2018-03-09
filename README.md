## badges

<p align="center">
    <img src="./badges.png" width="20%" />
</p>

<p align="center">
    To make badges more standard and acceptable.
</p>

[![badges](./aleen42.svg)](https://github.com/aleen42/badges/blob/master/aleen42.svg)

A collection of badges designed for personal repositories, and I hope that all of these badges can be widely accepted and used in the document of any project so that they can become more and more standard. If you also have some new ideas about badges, just open an issue. Always remember that: **More than a coder, more than a designer.**

So how to create such cute badges? It's very simple. As it's only registered on [npm](https://www.npmjs.com/), you should install it by typing:

```bash
sudo npm install -g badges-cli
```

Then you can use this command line tool for creating badges yourself:

Take the following command as an example, `t` means text content, and `c` means color. If you want to create a badge with SVG sources, you can specify with `p` to tell the tool where to find your sources. Finally, `o` is used to specify where to export the badge.

```bash
badge -t Alipay -c 1CACEB -p alipay.svg -o output.svg
```

One more thing, according to [the suggestion](https://github.com/facebook/jest/issues/5438#issuecomment-362553867) during creating badges for Jest, this tool has been extended to support skins with `s` to specify, which value can be "light" or "dark" temporarily at this moment.

To uninstall the tool, you can just uninstall it by typing:

```bash
sudo npm uninstall -g badges-cli
```

As for how to create a badge and add it in the collection? There are some steps you may need to follow:

1. Fork the repository
2. Install `badges-cli`
3. Create a logo with SVG formatted (**recommended**), or any other formats like PNG. (_**The logo should be wrapped into a square, in another word, the width should be equal to the height, or it would have been horizontally squished.**_)
4. Save the logo in the folder `dist`
5. Add data for your badge in the file `script/data.js`
    ```js
    'React Router': {
        fileName: 'router.svg',
        color: '62DAFB',
        description: 'A badge used for projects using React Router'
    }
    ```
5. Run the script by typing `npm run build`
6. If succeed, the readme file will be automatically updated
7. Finally, push all updates and create a pull request for your change
8. **Done!!**

> Note that: so far haven't I thought out a perfect solution for calculating width of text accurately yet, and it means that the text can not be aligned in some cases.

### Coder

- [![angular](./src/angular.svg)](https://aleen42.github.io/badges/src/angular.svg) A badge used for repositories which has used the framework, Angular
- [![npm](./src/npm.svg)](https://aleen42.github.io/badges/src/npm.svg) A badge used for npm packages
- [![gulp](./src/gulp.svg)](https://aleen42.github.io/badges/src/gulp.svg) A badge used for projects using Gulp to build
- [![vue](./src/vue.svg)](https://aleen42.github.io/badges/src/vue.svg) A badge used for repositories which has used the framework, Vue
- [![react](./src/react.svg)](https://aleen42.github.io/badges/src/react.svg) A badge used for repositories which has used the framework, React
- [![router](./src/router.svg)](https://aleen42.github.io/badges/src/router.svg) A badge used for projects using React Router
- [![modernizr](./src/modernizr.svg)](https://aleen42.github.io/badges/src/modernizr.svg) A badge for projects using Modernizr
- [![reactivex](./src/reactivex.svg)](https://aleen42.github.io/badges/src/reactivex.svg) A badge for projects using ReactiveX
- [![jest](./src/jest_1.svg)](https://aleen42.github.io/badges/src/jest_1.svg) A badge used for projects using Jest for testing JavaScript
- [![jest](./src/jest_2.svg)](https://aleen42.github.io/badges/src/jest_2.svg) A badge used for projects using Jest for testing JavaScript
- [![jasmine](./src/jasmine.svg)](https://aleen42.github.io/badges/src/jasmine.svg) A badge used for projects using Jasmine for testing JavaScript
- [![visual_studio](./src/visual_studio.svg)](https://aleen42.github.io/badges/src/visual_studio.svg) A badge for the Visual Studio IDE
- [![visual_studio_code](./src/visual_studio_code.svg)](https://aleen42.github.io/badges/src/visual_studio_code.svg) A badge for the Visual Studio Code IDE
- [![qunit](./src/qunit.svg)](https://aleen42.github.io/badges/src/qunit.svg) A badge for projects using QUnit for unit tests
- [![redux](./src/redux.svg)](https://aleen42.github.io/badges/src/redux.svg) A badge used for projects using React Redux
- [![eslint](./src/eslint.svg)](https://aleen42.github.io/badges/src/eslint.svg) A badge used for projects using ESLint
- [![gitbook](./src/gitbook_1.svg)](https://aleen42.github.io/badges/src/gitbook_1.svg) A badge used for books publish on Gitbook
- [![gitbook](./src/gitbook_2.svg)](https://aleen42.github.io/badges/src/gitbook_2.svg) A badge used for books publish on Gitbook
- [![node](./src/node.svg)](https://aleen42.github.io/badges/src/node.svg) A badge used for projects built with Node.js
- [![gitter](./src/gitter.svg)](https://aleen42.github.io/badges/src/gitter.svg) A badge used for projects can be discussed on Gitter
- [![atom](./src/atom.svg)](https://aleen42.github.io/badges/src/atom.svg) A badge for the Atom editor
- [![sublime_text](./src/sublime_text.svg)](https://aleen42.github.io/badges/src/sublime_text.svg) A badge for the Sulime Text editor
- [![bower](./src/bower.svg)](https://aleen42.github.io/badges/src/bower.svg) A badge used for bower packages
- [![gitlab](./src/gitlab.svg)](https://aleen42.github.io/badges/src/gitlab.svg) A badge used for Gitlab repositories
- [![grunt](./src/grunt.svg)](https://aleen42.github.io/badges/src/grunt.svg) A badge used for projects using grunt to build
- [![rss](./src/rss.svg)](https://aleen42.github.io/badges/src/rss.svg) A badge used for RSS subscribing
- [![javascript](./src/javascript.svg)](https://aleen42.github.io/badges/src/javascript.svg) A badge used for projects that coded with JavaScript
- [![mocha](./src/mocha.svg)](https://aleen42.github.io/badges/src/mocha.svg) A badge used for projects using Mocha for unit tests
- [![apiary](./src/apiary.svg)](https://aleen42.github.io/badges/src/apiary.svg) A badge used for documents written on Apiary
- [![docker](./src/docker.svg)](https://aleen42.github.io/badges/src/docker.svg) A badge used for projects deployed on Docker
- [![jsfiddle](./src/jsfiddle.svg)](https://aleen42.github.io/badges/src/jsfiddle.svg) A badge used for projects running on JSFiddle
- [![webpack](./src/webpack.svg)](https://aleen42.github.io/badges/src/webpack.svg) A badge used for projects built with Webpack
- [![slack](./src/slack.svg)](https://aleen42.github.io/badges/src/slack.svg) A badge used for projects discussed on Slack
- [![idea](./src/idea.svg)](https://aleen42.github.io/badges/src/idea.svg) A badge for the IDEA editor
- [![codepen](./src/codepen.svg)](https://aleen42.github.io/badges/src/codepen.svg) A badge used for projects running on CodePen
- [![hacker](./src/hacker.svg)](https://aleen42.github.io/badges/src/hacker.svg) A badge used for hacking projects (**Business Using is not allowed)**
- [![github](./src/github.svg)](https://aleen42.github.io/badges/src/github.svg) A badge used for GitHub repositories


### Community

- [![juejin_translation](./src/juejin_translation.svg)](https://aleen42.github.io/badges/src/juejin_translation.svg) A badge used for any articles translated by gold-miner
- [![facebook](./src/facebook.svg)](https://aleen42.github.io/badges/src/facebook.svg) A badge used for sharing communities on Facebook
- [![stackexchange](./src/stackexchange.svg)](https://aleen42.github.io/badges/src/stackexchange.svg) A badge used for references on Stack Exchange
- [![superuser](./src/superuser.svg)](https://aleen42.github.io/badges/src/superuser.svg) A badge used for references on Super User
- [![twitter](./src/twitter.svg)](https://aleen42.github.io/badges/src/twitter.svg) A badge used for sharing communities on Twitter
- [![google_plus](./src/google_plus.svg)](https://aleen42.github.io/badges/src/google_plus.svg) A badge used for sharing communities on Google+
- [![pinterest](./src/pinterest.svg)](https://aleen42.github.io/badges/src/pinterest.svg) A badge used for sharing communities on Pinterest
- [![sina_weibo](./src/sina_weibo.svg)](https://aleen42.github.io/badges/src/sina_weibo.svg) A badge used for sharing communities on Sina Weibo
- [![reddit](./src/reddit.svg)](https://aleen42.github.io/badges/src/reddit.svg) A badge used for articles shared on Reddit
- [![stackoverflow](./src/stackoverflow.svg)](https://aleen42.github.io/badges/src/stackoverflow.svg) A badge used for GitHub repositories
- [![medium](./src/medium.svg)](https://aleen42.github.io/badges/src/medium.svg) A badge used for articles shared on Medium
- [![serverfault](./src/serverfault.svg)](https://aleen42.github.io/badges/src/serverfault.svg) A badge used for references on Server Fault


### Communication

- [![messenger](./src/messenger.svg)](https://aleen42.github.io/badges/src/messenger.svg) A badge used for sharing communication ways on Messenger
- [![telegram](./src/telegram.svg)](https://aleen42.github.io/badges/src/telegram.svg) A badge used for sharing communication ways on Telegram
- [![skype](./src/skype.svg)](https://aleen42.github.io/badges/src/skype.svg) A badge used for sharing communication ways on Skype
- [![whatsapp](./src/whatsapp.svg)](https://aleen42.github.io/badges/src/whatsapp.svg) A badge used for sharing communication ways on WhatsApp
- [![line](./src/line.svg)](https://aleen42.github.io/badges/src/line.svg) A badge used for sharing communication ways on Line
- [![wechat](./src/wechat.svg)](https://aleen42.github.io/badges/src/wechat.svg) A badge used for sharing communication ways on WeChat
- [![lunkr](./src/lunkr.svg)](https://aleen42.github.io/badges/src/lunkr.svg) A badge used for sharing communication ways on Coremail Lunkr


### Multimedia

- [![soundcloud](./src/soundcloud.svg)](https://aleen42.github.io/badges/src/soundcloud.svg) A badge used for music shared on SoundCloud
- [![spotify](./src/spotify.svg)](https://aleen42.github.io/badges/src/spotify.svg) A badge used for music shared on Spotify


### Inc

- [![nasa](./src/nasa.svg)](https://aleen42.github.io/badges/src/nasa.svg) A badge used for projects of NASA
- [![codrops](./src/codrops.svg)](https://aleen42.github.io/badges/src/codrops.svg) A badge used for any project of Codrops Inc.
- [![paypal](./src/paypal.svg)](https://aleen42.github.io/badges/src/paypal.svg) A badge used for the Paypal Inc.
- [![alipay](./src/alipay.svg)](https://aleen42.github.io/badges/src/alipay.svg) A badge used for the Alipay Inc.
- [![xitu](./src/xitu.svg)](https://aleen42.github.io/badges/src/xitu.svg) A badge used for any articles of Xitu Inc.
- [![coremail](./src/coremail.svg)](https://aleen42.github.io/badges/src/coremail.svg) A badge used for the Coremail Inc.
- [![soundtooth](./src/soundtooth.svg)](https://aleen42.github.io/badges/src/soundtooth.svg) A badge used for any project of Soundtooth Inc.
- [![patreon](./src/patreon.svg)](https://aleen42.github.io/badges/src/patreon.svg) A badge used for the Patreon Inc.
- [![amazon](./src/amazon.svg)](https://aleen42.github.io/badges/src/amazon.svg) A badge used for the Amazon Inc.
- [![bitcoin](./src/bitcoin.svg)](https://aleen42.github.io/badges/src/bitcoin.svg) A badge used for the Bitcoin Inc.
- [![airbnb](./src/airbnb.svg)](https://aleen42.github.io/badges/src/airbnb.svg) A badge used for the Airbnb Inc.
- [![monsoon](./src/monsoon.svg)](https://aleen42.github.io/badges/src/monsoon.svg) A badge used for the Monsoon Inc.


### Car

- [![lamborghini](./src/lamborghini.svg)](https://aleen42.github.io/badges/src/lamborghini.svg) A badge used for cars of Lamborghini
- [![bugatti](./src/bugatti.svg)](https://aleen42.github.io/badges/src/bugatti.svg) A badge used for cars of Bugatti
- [![porsche](./src/porsche.svg)](https://aleen42.github.io/badges/src/porsche.svg) A badge used for cars of Porsche
- [![tesla](./src/tesla.svg)](https://aleen42.github.io/badges/src/tesla.svg) A badge used for cars of Tesla
- [![ferrari](./src/ferrari.svg)](https://aleen42.github.io/badges/src/ferrari.svg) A badge used for cars of Ferrari
- [![toyota](./src/toyota.svg)](https://aleen42.github.io/badges/src/toyota.svg) A badge used for cars of Toyota
- [![mitsubishi](./src/mitsubishi.svg)](https://aleen42.github.io/badges/src/mitsubishi.svg) A badge used for cars of Mitsubishi
- [![maserati](./src/maserati.svg)](https://aleen42.github.io/badges/src/maserati.svg) A badge used for cars of Maserati
- [![marussia](./src/marussia.svg)](https://aleen42.github.io/badges/src/marussia.svg) A badge used for cars of Marussia
- [![koenigsegg](./src/koenigsegg.svg)](https://aleen42.github.io/badges/src/koenigsegg.svg) A badge used for cars of Koenigsegg
- [![bmw](./src/bmw.svg)](https://aleen42.github.io/badges/src/bmw.svg) A badge used for cars of BMW
- [![land_rover](./src/land_rover.svg)](https://aleen42.github.io/badges/src/land_rover.svg) A badge used for cars of Land Rover
- [![mercedes_benz](./src/mercedes_benz.svg)](https://aleen42.github.io/badges/src/mercedes_benz.svg) A badge used for cars of Mercedes Benz
- [![audi](./src/audi.svg)](https://aleen42.github.io/badges/src/audi.svg) A badge used for cars of Audi


### Football Clubs

- [![liverpool](./src/liverpool.svg)](https://aleen42.github.io/badges/src/liverpool.svg) A badge used for FC Liverpool
- [![real_madrid](./src/real_madrid.svg)](https://aleen42.github.io/badges/src/real_madrid.svg) A badge used for FC Real Madrid
- [![manchester_united](./src/manchester_united.svg)](https://aleen42.github.io/badges/src/manchester_united.svg) A badge used for FC Manchester United
- [![arsenal](./src/arsenal.svg)](https://aleen42.github.io/badges/src/arsenal.svg) A badge used for FC Arsenal
- [![ac_milan](./src/ac_milan.svg)](https://aleen42.github.io/badges/src/ac_milan.svg) A badge used for FC AC Milan
- [![bayern_munchen](./src/bayern_munchen.svg)](https://aleen42.github.io/badges/src/bayern_munchen.svg) A badge used for FC Bayern Munchen
- [![barcelona](./src/barcelona.svg)](https://aleen42.github.io/badges/src/barcelona.svg) A badge used for FC Barcelona
- [![chelsea](./src/chelsea.svg)](https://aleen42.github.io/badges/src/chelsea.svg) A badge used for FC Chelsea


### Game

- [![steam](./src/steam.svg)](https://aleen42.github.io/badges/src/steam.svg) A badge used for any game supported on the platform Steam
- [![ingress](./src/ingress.svg)](https://aleen42.github.io/badges/src/ingress.svg) A badge used for the game Ingress published by Niantic Inc.
- [![osu](./src/osu.svg)](https://aleen42.github.io/badges/src/osu.svg) A badge used for the game osu! published by ppy


### Designer

- [![behance](./src/behance.svg)](https://aleen42.github.io/badges/src/behance.svg) A badge used for designing projects sharing on Behance
- [![photoshop](./src/photoshop.svg)](https://aleen42.github.io/badges/src/photoshop.svg) A badge used for designing projects using Photoshop as a tool
- [![illustrator](./src/illustrator.svg)](https://aleen42.github.io/badges/src/illustrator.svg) A badge used for designing projects using Illustrator as a tool
- [![dreamweaver](./src/dreamweaver.svg)](https://aleen42.github.io/badges/src/dreamweaver.svg) A badge used for projects using Dreamweaver as a tool
- [![after_effects](./src/after_effects.svg)](https://aleen42.github.io/badges/src/after_effects.svg) A badge used for designing projects using After Effect as a tool
- [![premiere](./src/premiere.svg)](https://aleen42.github.io/badges/src/premiere.svg) A badge used for designing projects using Premiere as a tool
- [![flash](./src/flash.svg)](https://aleen42.github.io/badges/src/flash.svg) A badge used for designing projects using Flash as a tool
- [![zeplin](./src/zeplin.svg)](https://aleen42.github.io/badges/src/zeplin.svg) A badge used for designing projects with Zeplin

#### :fuelpump: How to contribute

Have an idea? Found a bug? See [how to contribute](https://aleen42.gitbooks.io/personalwiki/content/contribution.html).

#### :scroll: License

[MIT](https://aleen42.gitbooks.io/personalwiki/content/MIT.html) © aleen42
