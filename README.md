<div align="center">

![Verdant logo](verdant.png)

# Verdant

[![GitHub latest release](https://img.shields.io/github/release-pre/NexerqDev/Verdant.svg)](https://github.com/NexerqDev/Verdant/releases) [![GitHub stars](https://img.shields.io/github/stars/NexerqDev/Verdant.svg)](https://github.com/NexerqDev/Verdant/stargazers) [![License](https://img.shields.io/badge/license-Zlib-green.svg)](https://github.com/NexerqDev/Verdant/blob/master/LICENSE) 

*An open-source game launcher for Naver Channeling Korean Maplestory players.*

*(오픈소스 메이플스토리 네이버 채널링 게임런처)*

*[looking for a GMS launcher without Nexon Launcher? Check my other project [Xenon](https://github.com/NexerqDev/Xenon) out!]*

![Verdant preview](preview.jpg)

</div>

## Usage
Pre-compiled downloads can be found [here](https://github.com/NexerqDev/Verdant/releases). ([프로그램 다운](https://github.com/NexerqDev/Verdant/releases))

All you have to do is login to your Naver account (OTP supported), change your Maple ID if you desire then launch the game! (Naver's CAPTCHA is annoying, so look below for an alternate method to login.)

Note that NGM must be installed, and obviously MapleStory must be too for this launcher to function properly! Other than that, enjoy!

Also, as this program is still definitely a work-in-progress, expect bugs! If you do find any however, please report them at [the issue tracker](https://github.com/NexerqDev/Verdant/issues), that would be most appreciated.

If you do find this program useful, please consider leaving it a [star](https://github.com/NexerqDev/Verdant/stargazers)! Thanks!

### Alternate Login Method
Since Naver's CAPTCHA as mentioned above is super hard to actually get right, I developed this quick way to login (you shouldn't need to login very often anyway, I hope...)

1. Make sure you are logged in to Naver in Chrome (only supported, other browsers haven't tested). When logging in, be sure to have **Stay Signed in ticked** so the session actually lasts!
1. Go to the Naver homepage (http://naver.com).
1. Press F12 to open the DevTools.
1. Go to the Application tab, open Cookies and go into the "www.naver.com" section.
1. **Highlight** all the cookies with your mouse, right click and hit copy. (see below for what it should look like, obviously without the massive censor)
1. Launch Verdant (close and reopen if already opened).
1. Verdant should automatically login using your browser's login session.

![](https://miku.s-ul.eu/8Gyd3tDf.jpg)

## Disclaimer
By using this software, you agree that I (Nicholas Tay <nexerq@gmail.com>) and/or collborators am not responsible for any damages that may be caused using this software (account banned, computer went on fire, etc.). That being said, I have tried to the best of my ability to make the program as transparent as possible, and this realistically should not happen. I mean - I use this software to get in and out of my account all the time, so it should be just fine. Basically, all the details can be found in the `LICENSE` file as in the root of the source code repository. Anyways, enjoy and have fun!

If you still don't trust me, you are welcome to look through the entire source code yourself, de/compile binaries, and whatever!

A note for Nexon (넥슨): if you don't like this software, please contact me via email or Twitter instead of banning me or whatever, and I will happily get it resolved ASAP (take down the repo, whatever). Thank you!

## License
Zlib (full text available in the root of the repository.)
