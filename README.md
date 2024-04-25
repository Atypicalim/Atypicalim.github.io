
# kompasim

> Hi there 👋 kompasim@163.com

![icon](https://avatars.githubusercontent.com/u/16191037?v=4)

---

## Links

* [github](https://github.com/kompasim)
* [blog](https://kompasim.github.io)
* [python](https://pypi.org/user/kompasim/)
* [vscode](https://marketplace.visualstudio.com/publishers/kompasim)
* [kirguzguch](https://kompasim.github.io/others/kirguzguch.html)
* [fontlar](https://gitee.com/kompasim/fontlar)

---

## Learning

* [script to record new words easily for windows](https://gist.github.com/kompasim/00335d5ea603a84c13a6be1d71a39997)

* [New Turkish words for myself](tr.md)
* [New Russian words for myself](ru.md)
* [Most used Turkish words for beginners](turkish.md)
* [Most used Russian words for beginners](russian.md)

---

## Tools

* [FFmpeg](https://ffmpeg.org/) | [FFmpegKit](https://tanersener.github.io/ffmpeg-kit/)

* [Lua for Windows](https://github.com/rjpcomputing/luaforwindows)

* [Lua to executables](https://www.tutorialspoint.com/how-to-create-standalone-lua-executables)

* [Netease Cloud Music](https://neteasecloudmusicapi.vercel.app/#/)

* [Spleeter](https://github.com/deezer/spleeter) | [SpleeterGui]([git@github.com:boy1dr/SpleeterGui.git](https://github.com/boy1dr/SpleeterGui))

* [PowerShell to EXE converter](https://ps2exe.azurewebsites.net/)

* [EasyOCR](https://github.com/JaidedAI/EasyOCR)

* [Dependencies](https://github.com/lucasg/Dependencies)

---

## AI

* [Poe AI Chat](https://poe.com/Sage)
* [AI Image Generator](https://aiimagegenerator.io/)
* [AI Remove Background](https://removebg.one/)
* [upscale low resolution images](https://www.upscayl.org/)
* [AI Video Generator](https://reccloud.cn/)

---

## Collections

### 1. knowledges

* [How modern web browsers work](https://web.dev/howbrowserswork/)

* [How Does a Database Work?](https://cstack.github.io/db_tutorial/)

### 2. front-end

* [JavaScript template engine in just 20 lines](https://krasimirtsonev.com/blog/article/Javascript-template-engine-in-just-20-line)

* [Write your Virtual DOM 1: Dom & diff](https://medium.com/@deathmood/how-to-write-your-own-virtual-dom-ee74acc13060)

* [Write your Virtual DOM 2: Props & Events](https://medium.com/@deathmood/write-your-virtual-dom-2-props-events-a957608f5c76)

* [A Guide to Reading VanJS Codebase](https://vanjs.org/about#source-guide)

### 3. server-side

* [Let’s Build A Web Server](https://ruslanspivak.com/lsbaws-part1/)

### 4. golang

* [character-set conversion library implemented in Go](https://github.com/axgle/mahonia)

### 5. others

* [Baby’s First Garbage Collector](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/)

* [Let’s Build A Simple Interpreter](https://ruslanspivak.com/lsbasi-part1/)

* [Write your Own Virtual Machine](https://www.jmeiners.com/lc3-vm/)

---

## Snippets

* JavaScript Proxy for function

```javascript
let tags = new Proxy((name, ...args) => {
    return `<${name}>${args}</${name}>`;
}, {
    get: (target, name) => {
        return target.bind(null, name);
    }
})
const {div} = tags;
console.log(tags("div", "content...")); // <div>content...</div>
console.log(div("content...")); // <div>content...</div>
```

---

<script src="https://giscus.app/client.js"
        data-repo="kompasim/kompasim.github.io"
        data-repo-id="R_kgDOH1aiUQ"
        data-category="General"
        data-category-id="DIC_kwDOH1aiUc4CRL4b"
        data-mapping="pathname"
        data-strict="0"
        data-reactions-enabled="1"
        data-emit-metadata="0"
        data-input-position="bottom"
        data-theme="light"
        data-lang="en"
        crossorigin="anonymous"
        async>
</script>
