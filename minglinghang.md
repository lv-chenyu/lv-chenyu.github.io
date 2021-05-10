`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git status`
`On branch master`
`Your branch is up to date with 'origin/master'.`

`Untracked files:`
  `(use "git add <file>..." to include in what will be committed)`
        `_posts/2021-04-01-working.md`

`nothing added to commit but untracked files present (use "git add" to track)`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git add .`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git commit -m "add new files"`
`[master 4df0b10] add new files`
 `1 file changed, 174 insertions(+)`
 `create mode 100644 _posts/2021-04-01-working.md`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git push -u origin master`
`fatal: unable to access 'https://github.com/lv-chenyu/lv-chenyu.github.io.git/': OpenSSL SSL_read: Connection was reset, errno 10054`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git config --global --unset http.proxy`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git config --global --unset https.proxy`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git push -u origin master`
`fatal: unable to access 'https://github.com/lv-chenyu/lv-chenyu.github.io.git/': Failed to connect to github.com port 443: Timed out`

`DELL@DESKTOP-1FJQV10 MINGW64 /d/jekyllWorkspace/lv-chenyu.github.io (master)`
`$ git push -u origin master`
`Enumerating objects: 6, done.`
`Counting objects: 100% (6/6), done.`
`Delta compression using up to 8 threads`
`Compressing objects: 100% (4/4), done.`
`Writing objects: 100% (4/4), 4.21 KiB | 4.21 MiB/s, done.`
`Total 4 (delta 2), reused 0 (delta 0), pack-reused 0`
`remote: Resolving deltas: 100% (2/2), completed with 2 local objects.`
`To https://github.com/lv-chenyu/lv-chenyu.github.io.git`
   `8be2a74..4df0b10  master -> master`
`Branch 'master' set up to track remote branch 'master' from 'origin'.`