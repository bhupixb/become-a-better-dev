# become-a-better-dev
A bookmark of all handy things I know, read or use.
All advice is based on my personal opinion, you may not agree with it & that's ok.

## Git

- video: [Configure git](https://www.youtube.com/watch?v=G3NJzFX6XhY)
- video: [You think you know git part1](https://www.youtube.com/watch?v=aolI_Rz0ZqY)
- video: [You think you know git part2](https://www.youtube.com/watch?v=Md44rcw13k4)

## Vim

I mostly use NeoVim for basic purposes. Configured via LazyVim.

## Browsers
- Use Brave or Firefox with ublock origin.

## Browser Extensions
- [Vimium](https://vimium.github.io/): navigate & manage tabs, scroll pages and many more features at your fingertips. No mouse needed.
- [Awesome Screenshots](https://www.awesomescreenshot.com/): for taking screenshots, edit them and copy/save them.
- Ublock Origin: This needs no intro. Learn more about the usage [here](https://www.youtube.com/watch?v=2lisQQmWQkY).
- Foxy Proxy: for proxying requests to inspect for debugging etc.

## DNS
To reduce the ads/tracking in my mobile, I use [nextdns](https://nextdns.io/). Their free plan is generous and enough for me.

## Password manager
Use a password manager(Bitwarden etc) to store your passwords. No need to remember them.
Always Always ALWAYS use randomly generated password except for those clunky
Bank websites who won't let you autofill and make you type the password.

## GNU core utils:
Ref: [here](https://www.youtube.com/watch?v=lyd6Lxy1IuE)
### [date](https://www.gnu.org/software/coreutils/manual/html_node/Examples-of-date.html)
```sh
$ date

$ date -d '1 hour ago'
```

### factor
Prints the prime factors of a number.

### [numfmt](https://www.gnu.org/software/coreutils/manual/html_node/numfmt-invocation.html) / gnumfmt
```sh
# format via grouping
$ LC_NUMERIC=en_US.UTF-8; echo 1234567890 | numfmt --grouping
1,234,567,890

$ echo 1234567890 | numfmt --to=iec
1.2G

$ echo 1234567890 | numfmt --to=si
1.3G
```

### nproc
nproc - print the number of processing units available

### env
```sh
# run a process with name `lamo`
$ genv -a lmao yes 123
```

### Postgres Reads

- https://byteofdev.com/posts/making-postgres-slow/

### Good reads on SWE

- https://minds.md/zakirullin/cognitive

### Interesting security writeups:

- RCE via SQL injection: https://labs.watchtowr.com/pre-auth-sql-injection-to-rce-fortinet-fortiweb-fabric-connector-cve-2025-25257/

### Software engineering Advice:

-  Advice from Amazon CTO: https://everton.xyz/i-sat-down-with-werner-vogels/ . This url is also saved on wayback machine, in case it fails in future.
-  https://terriblesoftware.org/2025/08/22/the-management-skill-nobody-talks-about/

### IntelliJ IDEA

- JVM debugger in IntelliJ Advanced: https://www.youtube.com/watch?v=40Og3hTV--k
- Pause Program in IntelliJ: https://blog.jetbrains.com/idea/2024/06/debugger-upskill-debug-without-breakpoints/
- How java debuggers work: https://blog.jetbrains.com/idea/2025/05/sources-bytecode-debugging
- Data flow, static analysis: https://blog.jetbrains.com/idea/2020/10/explore-your-program-with-static-analysis/
- Useful shortcuts: https://www.youtube.com/watch?v=hjGVJHOLSjA
