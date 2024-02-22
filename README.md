# tcbdwn
# **tcb** **d**o**wn**load

a simple bash script to scrape the tcbscans site to download manga

> NOTE: it requires `curl`, `fzf`, `soffice`, `pdfunite` and `wget` to run and uses GNU Core Utilities commands `grep`, `awk`, `sed`, `head`, `tail`, `find` etc.
> NOTE: if you are on mac be sure to replace every head command with ghead (GNU version of head) as the default head available in mac doesn't support negative number

## Installing

For the current user:

```
curl https://raw.githubusercontent.com/shivajichalise/tcbdwn/main/tcbdwn > ~/usr/local/bin/tcbdwn && chmod +755 ~/usr/local/bin/tcbdwn
```

Or simply copy the `tcbdwn` file to a location in your `$PATH` and make it executable.

## Usage

- just run the script and it'll ask required input

```sh
tcbdwn
```

## How it works

this script scraptes the tcbscans.com site, downloads every image from the given url, converts them into pdf and merges every pdf into a single one

## Self-Promotion

Star the repository on [Github](https://github.com/shivajichalise/tcbdwn)

Follow [shivajichalise](http://shivajichalise.com.np) on [Github](https://github.com/shivajichalise)

