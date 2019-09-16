# Linux-Reference-Link
# Command
* [practice - get file creation time](https://gist.github.com/hyunjun/63f16a820cbbed2d094a18e024a70fb6)
* [10가지 재밌는 리눅스 명령어들](http://www.clien.net/cs2/bbs/board.php?bo_table=lecture&wr_id=338629) cmatrix, asciiviewer, rev, yes, rig, figlet, toilet, banner, text to speech with espeak, :(){:|:&};:
* [백그라운드로 작업하는 몇 가지 방법](http://jybaek.tistory.com/683)
* [리눅스 명령어 삼대장: find, grep, awk](http://jybaek.tistory.com/704)
* [60 Commands of Linux : A Guide from Newbies to System Administrator](http://www.tecmint.com/60-commands-of-linux-a-guide-from-newbies-to-system-administrator/)
  * [Switching From Windows to Nix or a Newbie to Linux – 20 Useful Commands for Linux Newbies](http://www.tecmint.com/useful-linux-commands-for-newbies/)
  * [20 Advanced Commands for Middle Level Linux Users](http://www.tecmint.com/20-advanced-commands-for-middle-level-linux-users/)
  * [20 Advanced Commands for Linux Experts](http://www.tecmint.com/20-advanced-commands-for-linux-experts/)
* [Command Line Analytics](http://www.drbunsen.org/command-line-analytics/)
* [commandlinefu.com](www.commandlinefu.com)
* [command line power user - modern command line workflow with ZSH, Z and related tools](http://commandlinepoweruser.com/)
* [Learn the Command Line - Learn how to use the command line to manipulate data and automate tasks](https://www.codecademy.com/en/courses/learn-the-command-line)
* [the art of command line - Master the command line, in one page](https://github.com/jlevy/the-art-of-command-line)
* [Learn Enough Command Line to Be Dangerous](http://www.learnenough.com/command-line)
* [No one expect command execution !](http://0x90909090.blogspot.kr/2015/07/no-one-expect-command-execution.html)
* [Explaining Shell Commands in the Shell](https://www.mankier.com/blog/explaining-shell-commands-in-the-shell.html?hn=1)
* [UNIX TOOLBOX](http://cb.vu/unixtoolbox.xhtml)
* `sync && echo [1|2|3] > /proc/sys/vm/drop_caches` & `[swapoff|swapon] -a`
  * [Empty the linux buffer cache](http://www.commandlinefu.com/commands/view/1026/empty-the-linux-buffer-cache) 
  * [How do you empty the buffers and cache on a Linux system?](http://unix.stackexchange.com/questions/87908/how-do-you-empty-the-buffers-and-cache-on-a-linux-system)
* [More shell, less egg](http://leancrew.com/all-this/2011/12/more-shell-less-egg/) `tr -cs A-Za-z '\n' < [input] | tr A-Z a-z | sort | uniq -c | sort -rn | sed ${1}q`
* [Extract it](http://extractit.mawalabs.de/) command line to extract compressed file
* [Designing Command Line Experiences](http://neovintage.org/product/design/2015/10/01/designing-command-line-experiences/)
* [리눅스 명령어를 이용한 시스템 모니터링 하기](http://tech.whatap.io/2015/09/03/linux-monitoring/)
* [POSIX CLI1](https://opentutorials.org/module/3747)
* [The Unix Shell: Summary of Basic Commands](http://swcarpentry.github.io/shell-novice/reference/)
* [유닉스 쉘](https://statkclee.github.io/shell-novice-kr/)
* [유닉스 쉘(Unix Shell)](http://statkclee.github.io/shell-novice/index-kr.html)
* [SCP vs SFTP - 5 Key Comparisons](https://www.jscape.com/blog/scp-vs-sftp)
* [Linux 공부 14 - 개념 정리](http://throughkim.kr/2017/01/09/linux-14/)
* [리눅스 실무기술300](https://gist.github.com/hyunjun/f2a15bf2de9ed8cce7a0dc87ed16d839#file-linux_practical_tech300-md)
* **[8 super heroic Linux commands that you probably aren't using](https://www.youtube.com/watch?v=Zuwa8zlfXSY)**
* [Build your own Command Line with ANSI escape codes](http://www.lihaoyi.com/post/BuildyourownCommandLinewithANSIescapecodes.html)
* **[The Art of Command Line](https://github.com/jlevy/the-art-of-command-line/blob/master/README-ko.md)** 기초적인 부분을 거의 모두 정리해 놓은 매우 유용한 자료
* [Command line reference – Database and OS scripting](https://ss64.com)
* [Munging CSV files with standard Unix tools](https://www.johndcook.com/blog/2019/08/30/cut-sort-awk/) cut sort awk
* [`ack` - ack is a tool like grep, optimized for developers](https://beyondgrep.com)
  * [ACK: 개발자용 GREP](https://iamsang.com/blog/2014/11/22/ack/)
* `at`
  * [practice](https://gist.github.com/hyunjun/f2a15bf2de9ed8cce7a0dc87ed16d839#file-atq-md)
  * [Linux tip: Job scheduling with cron and at](http://www.ibm.com/developerworks/library/l-job-scheduling/)
  * [One Time Task Scheduling using `at` Command in Linux](http://tecadmin.net/one-time-task-scheduling-using-at-commad-in-linux/)
  * [Understand at, atq, atrm, batch Commands using 9 Examples](http://www.thegeekstuff.com/2010/06/at-atq-atrm-batch-command-examples/)
* `awk`
  * [AWK script 가이드](https://mug896.github.io/awk-script)
  * `$0` means whole line
  * sum of numbers in file `awk '{ sum += $1 } END { print sum }' [file name]`
  * [Merging Frequencies in a File](http://www.unix.com/shell-programming-and-scripting/156614-merging-frequencies-file.html)
  * [AWK greater than?](http://www.unix.com/shell-programming-and-scripting/56223-awk-greater-than.html)
  * [Print only the Nth line before each line that matches a pattern](https://unix.stackexchange.com/questions/283471/print-only-the-nth-line-before-each-line-that-matches-a-pattern)
  * `awk '{ gsub(/\xef\xbb\xbf/,""); print }' INFILE > OUTFILE` [remove ALL <U+FEFF>](https://gist.github.com/szydan/b225749445b3602083ed) 
* `basename` get file name from path
  * e.g. `$ basename /tmp/mdstat.tmp .tmp` returns `mdstat`
* `comm`
  * `comm [-1] [-2] [-3] [file1] [file2]` print common lines between file1 & file2 (-1 suppresses only lines from file1 & -2 does the same from file2, -3 does the same for duplicated lines)
    * [reverse diff](http://stackoverflow.com/questions/746458/how-to-show-lines-in-common-reverse-diff)
* crontab
  * **[Crontab Generator](https://crontab-generator.org/)**
  * [crontab.guru](http://crontab.guru/)
  * [cron and crontab usage and examples](https://www.pantz.org/software/cron/croninfo.html)
  * `` `date "+\%Y\%m\%d"` `` [How can I execute `date` inside of a cron tab job?](http://unix.stackexchange.com/questions/29578/how-can-i-execute-date-inside-of-a-cron-tab-job)
  * `LANG=ko_KR.UTF-8` [Python3: UnicodeEncodeError only when run from crontab](http://stackoverflow.com/questions/11735363/python3-unicodeencodeerror-only-when-run-from-crontab)
  * [Cron in production? That is a double edged sword!](https://orchestrate.io/blog/2014/03/31/cron-in-production-that-is-a-double-edged-sword/)
  * [www.lesstif.com/display/1STB/cron](https://www.lesstif.com/display/1STB/cron)
  * [Crontab을 이용한 노드 API 호출](http://engineeryun.tistory.com/entry/Crontab%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-%EB%85%B8%EB%93%9C-API-%ED%98%B8%EC%B6%9C)
  * [해당 달의 첫 평일에 실행하는 스케쥴](http://ohgyun.com/759)
  * [crontab 사용시 권한 주의](http://jybaek.tistory.com/712)
  * [python-crontab](https://pypi.python.org/pypi/python-crontab)
  * [Cron Expression](https://gitlab.com/cosmochain/handbook/blob/master/TwIL/20180910-20180921/20180927_SM_Cron_Expressions.md)
* `curl`
  * [practice - `-k` insecure & `-svo` verbose](https://gist.github.com/hyunjun/44a68ec086d690bdda94a369e8e43daa#file-curl_insecure-md)
  * [A CURL CHEAT SHEET](http://daniel.haxx.se/blog/2015/09/16/a-curl-cheat-sheet/)
  * [online curl commandline builder](https://curlbuilder.com/)
  * [TLS Connection Control](http://blog.mailgun.com/tls-connection-control/)
  * [Use Curl to identify bottlenecks in your service layers](https://gist.github.com/adamkaplan/adf15f0d622f4932f4af)
  * [Is curl|bash insecure?](https://blog.sandstorm.io/news/2015-09-24-is-curl-bash-insecure-pgp-verified-install.html)
* `cut`
  * [Linux Tutorials - 24 cut command Slitting a file vertically | GeeksforGeeks](https://www.youtube.com/watch?v=eHGCxEVlHd0)
  * [How to specify more spaces for the delimiter using cut?](https://stackoverflow.com/questions/7142735/how-to-specify-more-spaces-for-the-delimiter-using-cut)
  * [Working with wide text files at the command line](https://www.johndcook.com/blog/2019/08/28/cut/)
* `date`
  * `date +%Y%m%d [--date '1 days ago']`

    ```
    for i in {n..m}
    do
      echo $i
      YYYYMMDD=`date "+%Y%m%d" --date "$i days ago"`
      YYYY=${YYYYMMDD:0:4}
      MM=${YYYYMMDD:4:2}
      DD=${YYYYMMDD:6:2}
    done
    ```
  * 날짜 차이 계산 [How to calculate time difference in bash script?](http://stackoverflow.com/questions/8903239/how-to-calculate-time-difference-in-bash-script)

    ```
    #!/bin/sh
    TODAY=`date '+%Y%m%d'`
    DAY=${1:-$TODAY}  # 입력이 있으면 사용하고 아니면 오늘 날짜 사용
    A_YEAR_AGO=`date '+%Y%m%d' -d "$DAY - 366 days"`  # 366일 전
    YESTERDAY=`date '+%Y%m%d' -d "$DAY - 1 days"`     # 어제
    ```
  * `date -d "Mon Feb 27 15:03:58 2017" +"%Y%m%d"`
    * [HowTo Format Date For Display or Use In a Shell Script](https://www.cyberciti.biz/faq/linux-unix-formatting-dates-for-display/)
    * [Bash convert string to timestamp](http://stackoverflow.com/questions/26432050/bash-convert-string-to-timestamp)
  * [Convert string to date in bash](https://stackoverflow.com/questions/11144408/convert-string-to-date-in-bash)

    ```
    date -d '20121212' +'%Y-%m-%d'
    date -d '20121212 -7 days' +'%Y-%m-%d'
    dat2=$(date -d "$dat -1 days" +'%Y%m%d')
    ```
  * `date +%s` [How can I generate Unix timestamps?](https://stackoverflow.com/questions/1204669/how-can-i-generate-unix-timestamps)
* df
  * [df 명령어](https://johngrib.github.io/wiki/df/)
  * [디스크가 가득 찼을 때](http://wikibook.co.kr/article/when-the-disk-is-full/)
  * [df와 du의 용량차이 발생과 해결(아무리 지워도 디스크 사용량이 줄어들지 않을때)](http://me2c.blogspot.com/2011/02/df-du.html)
* `diff`
  * [Delta is a command-line utility for text diffs. View split diffs in the browser with syntax highlighting (demo), or in the command-line using the --cli flag](http://delta.octavore.com/)
* `dirname` get directory name from path
* [dnf - dnf is a package manager based on yum and libsolv](https://github.com/rpm-software-management/dnf)
* du
  * [du 명령어](https://johngrib.github.io/wiki/du/) `du -hs <directory>` `du -ckx | sort -n -r | head` 가장 용량이 큰 디렉토리 찾기
  * [df와 du의 용량차이 발생과 해결(아무리 지워도 디스크 사용량이 줄어들지 않을때)](http://me2c.blogspot.com/2011/02/df-du.html)
* echo
  * `echo -e "..."` ['echo' without newline in a shell script](http://stackoverflow.com/questions/11193466/echo-without-newline-in-a-shell-script)
* `find`
  * `find [directory] -iname "[file name or pattern]" -exec ls -alt {} \;`
  * `find [directory] -name "[file name or pattern]" -exec ls -alt {} \;`
  * `find ~/Downloads/*.pdf -mtime -10` -atime = access / -ctime = creation, file 속성 / -mtime = modification
  * `find <dir> -not -newermt 2010-01-01` [Shell script to find files older than 1st Jan 2010](http://stackoverflow.com/questions/4378450/shell-script-to-find-files-older-than-1st-jan-2010)
  * `find . -type d -exec zip -r {}.zip {} \;` 현재 directory의 sub directory들을 찾아 각각의 이름으로 압축
  * [find 명령 정리](http://blog.naver.com/antimidal/220041200248)
* `grep`
  * `grep: Binary file <some file> matches` > `grep [-a|--text] <some file>`
  * `grep '^[A-Z_]\+[   ]\+[0-9]\+' [file name]` 파일에서 영어 대문자와 \_(underscore)로 시작하고 중간에 스페이스, 탭으로 이뤄진 공백이 있고 숫자로만 끝나는 line 찾기
  * [Capturing Groups From a Grep RegEx](http://stackoverflow.com/questions/1891797/capturing-groups-from-a-grep-regex)
    * `grep -Po 'query=\K[a-zA-Z]{16,}'` log에서 query=...으로 되어 있는 부분에서 16자 이상의 영문자만 찾고 싶은 경우. -P는 perl regular expression, \K는 앞 부분은 결과에서 제외, GNU grep version 2.5 이상
  * [Deep Dive Grep](http://avengers.alinos.net/2016/06/04/deep-dive-grep/)
  * [리눅스에서 Grep and , or , not 사용법](http://hamait.tistory.com/809)
* gzip
  * [Parallel gzip compression with pigz](https://rachaellappan.github.io/pigz/)
* nohup
  * [리눅스 nohup 사용법](https://zetawiki.com/wiki/%EB%A6%AC%EB%88%85%EC%8A%A4_nohup_%EC%82%AC%EC%9A%A9%EB%B2%95)
* iconv
  * [파일 캐릭터셋(character set) 변경](http://blog.naver.com/antimidal/220192718002)
  * `iconv -f UTF-16LE -t UTF-8 <infile> > <outfile>` infile 형식이 `Little-endian UTF-16 Unicode text, with CRLF, CR line terminators`라 utf8로 바꾸는 경우
* `ip` replacement of ifconfig
  * [There's real reasons for Linux to replace ifconfig, netstat, et al](https://utcc.utoronto.ca/~cks/space/blog/linux/ReplacingNetstatNotBad)
* join
  * [15 Linux Split and Join Command Examples to Manage Large Files](http://www.thegeekstuff.com/2012/10/15-linux-split-and-join-command-examples-to-manage-large-files/)
* kill
  * [Best way to kill all child processes](http://stackoverflow.com/questions/392022/best-way-to-kill-all-child-processes)
  * [Killing a process and all of its descendants](http://morningcoffee.io/killing-a-process-and-all-of-its-descendants.html)
* `less`
  * [Stop using tail -f (mostly)](http://www.brianstorti.com/stop-using-tail/)
* `ls`
  * [Linux ls Command: Sort Files By Size](https://www.cyberciti.biz/faq/linux-ls-command-sort-by-file-size/)
* `mkdir`
  * [get the most out of mkdir](https://blog.hauck.io/get-the-most-out-of-mkdir/)
* [monit](https://mmonit.com/) 설정이 엄청나게 쉽다지만, 간단한 건 upstart가 더 쉬웠음
  * [아마존 웹 서비스 7 – 데몬 자동 부활주문서 monit](http://www.creativeworksofknowledge.com/2015/06/07/aws-daemon-monitoring-using-monit/)
* `mv`
  * [Unix filesystems: How mv can be dangerous](http://jstimpfle.de/fun/mv.html)
* nc

  ```
  SERVER$ nc -l [port number] > [file name]
  CLIENT$ nc [server ip] [port number] < [file name]

  SERVER$ nc -l [port number] | tar xvfz -
  CLIENT$ tar cvfpz - [files] | nc [server ip] [port number]
  ```
  * [Play with Netcat in Ubuntu](https://www.unixmen.com/play-with-netcat-in-ubuntu/)
* nm
  * [How do I list the symbols in a .so file](http://stackoverflow.com/questions/34732/how-do-i-list-the-symbols-in-a-so-file)
* nmap
  * [Nmap Examples For Network Admins](http://teknixx.com/nmap-examples-for-network-admins/)
* [nq - Unix command line queue utility](https://github.com/chneukirchen/nq)
* nslookup
  * [nslookup 사용법](http://qnfmfmd.tistory.com/11)
* ntp
  * [practice - ntpd, ntpdate, ntpq](https://gist.github.com/hyunjun/f2a15bf2de9ed8cce7a0dc87ed16d839#file-ntp-md)
  * [RHEL, CentOS에서 ntp 서버 설정하기(사설망 내부 서버들의 시간 동기화)](http://hook.tistory.com/entry/RHEL-CentOS%EC%97%90%EC%84%9C-ntp-%EC%84%9C%EB%B2%84-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0%EC%82%AC%EC%84%A4%EB%A7%9D-%EB%82%B4%EB%B6%80-%EC%84%9C%EB%B2%84%EB%93%A4%EC%9D%98-%EC%8B%9C%EA%B0%84-%EB%8F%99%EA%B8%B0%ED%99%94)
* `objdump` / `gobjdump` (OS X)
  * [practice](https://gist.github.com/hyunjun/693e04c3fec40094cef9)
* `paste` `paste -d"[delimiter] [file1] [file2]`
  * [how to merge two files consistently line by line](http://stackoverflow.com/questions/16394176/how-to-merge-two-files-consistently-line-by-line)
* `pbcopy`
  * [터미널에서 현재 디렉토리를 클립보드로 복사하기](http://www.appilogue.kr/2844595)
* `ping`
  * [The Story of the PING Program](http://ftp.arl.army.mil/~mike/ping.html)
  * [prettyping is a wrapper around the standard ping tool with the objective of making the output prettier, more colorful, more compact, and easier to read](http://denilson.sa.nom.br/prettyping/)
* pipe
  * [Persistent "pipes" in Linux](https://gist.github.com/CAFxX/571a1558db9a7b393579)
  * [How Linux pipes work under the hood](https://brandonwamboldt.ca/how-linux-pipes-work-under-the-hood-1518/) pipe 동작 내부 설명
* ps
  * `ps -T -p <process num>` [How to view threads of a process on Linux](http://ask.xmodulo.com/view-threads-process-linux.html)
* rdate [리눅스(Linux) 계열 운영체제에서 시간 동기화하기](https://jhrun.tistory.com/158)
* `read`
  * [How to read from file or stdin in bash?](http://stackoverflow.com/questions/6980090/how-to-read-from-file-or-stdin-in-bash)
* `rm`
  * [How to Recover a Deleted File in Linux](https://www-tecmint-com.cdn.ampproject.org/c/s/www.tecmint.com/recover-deleted-file-in-linux/amp/)
* `rsync`
  * `rsync -avz --rsh="ssh -l [id]" [ip]:[src path] [dst path]`
    * daemon / ssh 방식 두 가지가 있는데, ssh의 경우 ssh public key를 추가해야 접속이 가능
  * [ssh 를 이용한 rsync 및 스크립트](http://blueamor.tistory.com/190)
* `sed`
  * [Sed stream editor 가이드](https://mug896.github.io/sed-stream-editor)
  * [Bash Shell: Remove (Trim) White Spaces From String / Variable](http://www.cyberciti.biz/faq/bash-remove-whitespace-from-string/)
    * `sed -e 's/^[ \t]*//'` remove tab & space at the start of the line
    * `sed -e 's/[ \t]*$//'` remove tab & space at the end of the line
  * `sed 's/\xEF\xBB\xBF//g'` remove <feff>
    * [<U+FEFF> character showing up in files. How to remove them?](http://stackoverflow.com/questions/7297888/ufeff-character-showing-up-in-files-how-to-remove-them)
    * [Removing special characters(<200c> <200d> from a text file](http://stackoverflow.com/questions/9257103/removing-special-characters200c-200d-from-a-text-file)
  * `sed -e "s/^M//" <infile> > <outfile>` ^M 제거
  * [Delete specific line number(s) from a text file using sed?](http://stackoverflow.com/questions/2112469/delete-specific-line-numbers-from-a-text-file-using-sed)
* [seq](http://www.delorie.com/gnu/docs/textutils/coreutils_156.html)
  * `seq -f '%05g' [start number] [end number]` format string %e, %g, %f
  * [리눅스 seq 명령어 사용법](https://www.snoopybox.co.kr/1680)
  * [How To Shuffle and Sample on the Command-Line](http://blog.jpalardy.com/posts/how-to-shuffle-and-sample-on-the-command-line/)
* shuf
  * [How To Shuffle and Sample on the Command-Line](http://blog.jpalardy.com/posts/how-to-shuffle-and-sample-on-the-command-line/)
* `sort`
  * `sort -u -t[delimiter] -k[column num],[column num] [file name]` [remove lines based on duplicates within one column](http://unix.stackexchange.com/questions/171091/remove-lines-based-on-duplicates-within-one-column-without-sort)
  * `sort -t'    ' -k9 -n -r [file name]` tab 구분 시 9번째 column 기준으로 숫자 역순으로 정렬
  * [Sort Files Like A Master With The Linux Sort Command (Bash)](http://www.skorks.com/2010/05/sort-files-like-a-master-with-the-linux-sort-command-bash/)
  * `sort -V` [Sorting numbers inside text strings](http://www.thelinuxrain.com/articles/sorting-numbers-inside-text-strings)
* `split`
  * [텍스트 파일을 잘라보자.split](http://darkrang.tistory.com/179)
* `ss` replacement of netstat
  * [There's real reasons for Linux to replace ifconfig, netstat, et al](https://utcc.utoronto.ca/~cks/space/blog/linux/ReplacingNetstatNotBad)
* `ssh`
  * [Getting Started with SSH](https://semaphoreci.com/community/tutorials/getting-started-with-ssh)
  * [ssh key 효율적인 관리 방법](http://www.popit.kr/ssh-key-%ED%9A%A8%EC%9C%A8%EC%A0%81%EC%9D%B8-%EA%B4%80%EB%A6%AC-%EB%B0%A9%EB%B2%95/)
  * [SSH known_host 메모](http://bcho.tistory.com/1227) ssh-keyscan
  * `ssh-keygen -R <ip>` [Host key verification failed 대처](http://uni2u.tistory.com/93)
  * [A top-down introduction to SSH and how it enables secure data-sharing](https://medium.freecodecamp.org/a-top-down-introduction-to-ssh-965f4fadd32e)
  * [SSH Port Forwarding](https://jusths.tistory.com/102)
* `ssh-copy-id` `ssh-copy-id -i ~/.ssh/id_rsa.pub id@host`
* `stat`
  * `[ 0 = ``stat --printf="%s" $f`` ] && rm $f` remove file if size is 0
  * `stat -c%s <file>`  [How to check size of a file?](http://stackoverflow.com/questions/5920333/how-to-check-size-of-a-file)
* `strip`
  * [10 Linux Strip Command Examples (Reduce Executable/Binary File Size)](http://www.thegeekstuff.com/2012/09/strip-command-examples/)
* [sudo 패스워드 없이 사용하는 방법](https://kkamagui.tistory.com/910)
* [systemd](http://www.freedesktop.org/wiki/Software/systemd/) redhat 6.3에서는 `configure`가 안 됨
  * [How to install, manage, start and autostart ssh service on RHEL 7 Linux](https://linuxconfig.org/how-to-install-manage-start-and-autostart-ssh-service-on-rhel-7-start)
  * [서버 프로세스를 관리하는 올바른 방법](http://www.codeok.net/%EC%84%9C%EB%B2%84%20%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EB%A5%BC%20%EA%B4%80%EB%A6%AC%ED%95%98%EB%8A%94%20%EC%98%AC%EB%B0%94%EB%A5%B8%20%EB%B0%A9%EB%B2%95)
  * [How To Install / Upgrade systemd on RHEL/CentOS 7.0](http://linoxide.com/linux-how-to/install-systemd-centos-redhat/)
  * [Why I dislike systemd](http://www.steven-mcdonald.id.au/articles/systemd.shtml)
  * [Systemd is the best example of Suck](http://suckless.org/sucks/systemd)
  * [hastur is a tool for launching systemd-nspawn containers without need of manual configuration](https://github.com/seletskiy/hastur)
  * [systemd 살펴보기](http://lunatine.net/about-systemd/)
  * [systemd 서비스 unit파일 작성에서 했던 실수](https://springboot.cloud/16)
* systemtap
  * [커널 분석을 위한 systemtap 스크립트](https://brunch.co.kr/@alden/42)
* `tac`
* `tar`
  * [Portability of tar features](https://dev.gentoo.org/~mgorny/articles/portability-of-tar-features.html)
* `tail`
  * [Stop using tail -f (mostly)](http://www.brianstorti.com/stop-using-tail/)
  * [delete first line of a file](http://unix.stackexchange.com/questions/96226/delete-first-line-of-a-file) `tail -n +2 [file name]`
* `tcpdump`
  * [A gentle introduction to Berkeley Packet Filters](http://tylerfisher.org/bpf/)
  * **[tcpdump를 활용한 타임아웃 분석](https://brunch.co.kr/@alden/38)**
  * [Tcpdump Examples](https://hackertarget.com/tcpdump-examples/)
  * [tcpdump 기본 사용법](http://jojoldu.tistory.com/316)
* `top`
  * [Can You Top This? 15 Practical Linux Top Command Examples](http://www.thegeekstuff.com/2010/01/15-practical-unix-linux-top-command-examples/)
  * [iftop 설치, 실시간 트래픽 확인하기](https://ash84.net/2017/11/16/iftop-show-traffic/)
  * [Guider – A System Wide Linux Performance Analyzer](https://www.tecmint.com/guider-a-system-wide-linux-performance-analyzer/)
  * [top 명령어](https://johngrib.github.io/wiki/top/)
  * `top -H` [How to view threads of a process on Linux](http://ask.xmodulo.com/view-threads-process-linux.html)
* `tr`
  * [remove-all-white-spaces](http://stackoverflow.com/questions/9953448/how-to-remove-all-white-spaces-from-a-given-text-file) `tr -d [:blank:]`
  * [replace-whitespaces-with-tabs-in-linux](http://stackoverflow.com/questions/1424126/replace-whitespaces-with-tabs-in-linux)
  * `tr -d '^M'` ^M과 개행 문자를 같이 없애고 싶었는데, 원하는대로 잘 동작하지 않았고, ^M만 없앨 때는 이 방법이 가장 편했음
    * [Different ways to delete ^M character in a file](http://www.theunixschool.com/2011/03/different-ways-to-delete-m-character-in.html)
    * [How to convert the ^M linebreak to 'normal' linebreak in a file opened in vim?](http://stackoverflow.com/questions/811193/how-to-convert-the-m-linebreak-to-normal-linebreak-in-a-file-opened-in-vim)
    * [How can I replace a newline (\n) using sed?](http://stackoverflow.com/questions/1251999/how-can-i-replace-a-newline-n-using-sed)
    * [How to add a carriage return before every newline?](http://unix.stackexchange.com/questions/153091/how-to-add-a-carriage-return-before-every-newline)
    * [sed replace newline (or 5 ways to remove line breaks with sed, python, tr, perl, xargs) 1](http://slash4.net/blog/python/sed-replace-newline-or-python-awk-tr-perl-xargs.html)
* trace
  * [Choosing a Linux Tracer (2015)](http://www.brendangregg.com/blog/2015-07-08/choosing-a-linux-tracer.html)
* uname
  * [cpu 타입 확인하기](http://knight76.tistory.com/entry/cpu-%ED%83%80%EC%9E%85-%ED%99%95%EC%9D%B8%ED%95%98%EA%B8%B0)
* [upstart](http://upstart.ubuntu.com/)
  * [The Upstart Event System: What It Is And How To Use It](https://www.digitalocean.com/community/tutorials/the-upstart-event-system-what-it-is-and-how-to-use-it)
  * [RHEL6 SELinux Upstart - How to reload configuration /etc/init/<conf> without a restart?](https://access.redhat.com/discussions/671253)
  * [practice](https://gist.github.com/hyunjun/ad60cf79c390b3fe0523)
* uptime
  * [uptime 명령어](https://johngrib.github.io/wiki/uptime/)
* `watch`
  * [The watch Command](http://www.linfo.org/watch.html)
* `wc`
  * `wc -c <file>`  [How to check size of a file?](http://stackoverflow.com/questions/5920333/how-to-check-size-of-a-file)
* [`xxd`](https://linux.die.net/man/1/xxd)
  * 0, 1에 대한 bit format 출력
    * `xxd -b (Filename) > BINARY.bin` 현재 디렉토리에 BINARY.bin 파일 생성
    * `xxd -r BINARY.bin > (Filename)` 변환된 바이너리 덤프 -> 원본 파일 형식
      * hex 값을 수정한 이후 이를 다시 원본 형태로 돌려놓아야 할 때 유용
* `zcat` uncompresses either a list of files on the command line or its standard input and writes the uncompressed data on standard output
  
