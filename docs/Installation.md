---
layout: default
title: Installation
nav_order: 99
---

# Installation

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
- TOC
{:toc}
</details>
---

## Clonen in git-bash

```
User@Me19 MINGW64 ~
$ cd BsTd/BsWb/

User@Me19 MINGW64 ~/BsTd/BsWb
$ ls -als
total 13
0 drwxr-xr-x 1 User 197608   0 Feb 26 15:19 ./
4 drwxr-xr-x 1 User 197608   0 Feb 26 10:53 ../
4 drwxr-xr-x 1 User 197608   0 Feb 26 15:19 bs-jek/
1 -rw-r--r-- 1 User 197608 175 Feb 26 10:56 index.markdown
0 drwxr-xr-x 1 User 197608   0 Feb 26 15:11 Logs/
4 -rw-r--r-- 1 User 197608 930 Feb 26 16:20 ReadmeHm.txt

User@Me19 MINGW64 ~/BsTd/BsWb
$ git clone https://github.com/muellerh08/bs-jtd.git
Cloning into 'bs-jtd'...
remote: Enumerating objects: 17, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 17 (delta 3), reused 8 (delta 1), pack-reused 0
Receiving objects: 100% (17/17), 8.64 KiB | 2.88 MiB/s, done.
Resolving deltas: 100% (3/3), done.

User@Me19 MINGW64 ~/BsTd/BsWb
$ ls -als
total 18
0 drwxr-xr-x 1 User 197608   0 Mrz  3 08:35 ./
4 drwxr-xr-x 1 User 197608   0 Feb 26 10:53 ../
4 drwxr-xr-x 1 User 197608   0 Feb 26 15:19 bs-jek/
4 drwxr-xr-x 1 User 197608   0 Mrz  3 08:35 bs-jtd/
1 -rw-r--r-- 1 User 197608 175 Feb 26 10:56 index.markdown
0 drwxr-xr-x 1 User 197608   0 Feb 26 15:11 Logs/
4 -rw-r--r-- 1 User 197608 930 Feb 26 16:20 ReadmeHm.txt
1 -rw-r--r-- 1 User 197608  54 Mrz  3 08:28 ReadmeJtd.txt

User@Me19 MINGW64 ~/BsTd/BsWb
$ cd bs-jtd/

User@Me19 MINGW64 ~/BsTd/BsWb/bs-jtd (main)
$ ls -als
total 31
4 drwxr-xr-x 1 User 197608    0 Mrz  3 08:35 ./
0 drwxr-xr-x 1 User 197608    0 Mrz  3 08:35 ../
4 drwxr-xr-x 1 User 197608    0 Mrz  3 08:35 .git/
0 drwxr-xr-x 1 User 197608    0 Mrz  3 08:35 .github/
1 -rw-r--r-- 1 User 197608  460 Mrz  3 08:35 .gitignore
1 -rw-r--r-- 1 User 197608  269 Mrz  3 08:35 _config.yml
1 -rw-r--r-- 1 User 197608  294 Mrz  3 08:35 Gemfile
4 -rw-r--r-- 1 User 197608 2225 Mrz  3 08:35 Gemfile.lock
4 -rw-r--r-- 1 User 197608 2289 Mrz  3 08:35 index.md
4 -rw-r--r-- 1 User 197608 1091 Mrz  3 08:35 LICENSE
8 -rw-r--r-- 1 User 197608 7059 Mrz  3 08:35 README.md

User@Me19 MINGW64 ~/BsTd/BsWb/bs-jtd (main)
````

## Erstinstallation in PowerShell

````
PS C:\Users\User\BsTd\BsWb> d bs-jtd

    Directory: C:\Users\User\BsTd\BsWb\bs-jtd

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          03.03.2024    08:35                .github
-a---          03.03.2024    08:35            269 _config.yml
-a---          03.03.2024    08:35            460 .gitignore
-a---          03.03.2024    08:35            294 Gemfile
-a---          03.03.2024    08:35           2225 Gemfile.lock
-a---          03.03.2024    08:35           2289 index.md
-a---          03.03.2024    08:35           1091 LICENSE
-a---          03.03.2024    08:35           7059 README.md

PS C:\Users\User\BsTd\BsWb\bs-jtd> bundle install
Bundler 2.5.6 is running, but your lockfile was generated with 2.3.26. Installing Bundler 2.3.26 and restarting using that version.
Fetching gem metadata from https://rubygems.org/.
Fetching bundler 2.3.26
Installing bundler 2.3.26
Fetching gem metadata from https://rubygems.org/...........
Resolving dependencies...
Using rake 13.1.0
Using bundler 2.3.26
Using public_suffix 5.0.4
Using colorator 1.1.0
Using eventmachine 1.2.7
Using http_parser.rb 0.8.0
Using ffi 1.16.3 (x64-mingw-ucrt)
Using forwardable-extended 2.6.0
Using rb-fsevent 0.11.2
Using rexml 3.2.6
Using liquid 4.0.4
Using mercenary 0.4.0
Using rouge 4.2.0
Using safe_yaml 1.0.5
Using unicode-display_width 2.5.0
Fetching concurrent-ruby 1.2.2
Using webrick 1.8.1
Using addressable 2.8.6
Using em-websocket 0.5.3
Using rb-inotify 0.10.1
Fetching google-protobuf 3.25.1 (x64-mingw-ucrt)
Using pathutil 0.16.2
Using kramdown 2.4.0
Using terminal-table 3.0.2
Using listen 3.8.0
Using kramdown-parser-gfm 1.1.0
Using jekyll-watch 2.2.1
Installing concurrent-ruby 1.2.2
Installing google-protobuf 3.25.1 (x64-mingw-ucrt)
Fetching sass-embedded 1.69.5 (x64-mingw-ucrt)
Using i18n 1.14.1
Installing sass-embedded 1.69.5 (x64-mingw-ucrt)
Using jekyll-sass-converter 3.0.0
Using jekyll 4.3.3
Using jekyll-include-cache 0.2.1
Using jekyll-seo-tag 2.8.0
Using just-the-docs 0.8.0
Bundle complete! 2 Gemfile dependencies, 34 gems now installed.
Use `bundle info [gemname]` to see where a bundled gem is installed.
PS C:\Users\User\BsTd\BsWb\bs-jtd> bundle exec jekyll serve
Configuration file: C:/Users/User/BsTd/BsWb/bs-jtd/_config.yml
            Source: C:/Users/User/BsTd/BsWb/bs-jtd
       Destination: C:/Users/User/BsTd/BsWb/bs-jtd/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 2.695 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'C:/Users/User/BsTd/BsWb/bs-jtd'
    Server address: http://127.0.0.1:4000
  Server running... press ctrl-c to stop.
----------------------------------------------------------------------------------------
Unter http://localhost:4000/ wird angezeigt -> 'Just the Docs Template'
````

## Einige Links

- [URLs and links in Jekyll](https://mademistakes.com/mastering-jekyll/how-to-link/)
- [Anwendungen neuen Dateityp bzw. Anwendung hinzufügen](https://www.camp-firefox.de/forum/thema/135174-anwendungen-neuen-dateityp-bzw-anwendung-hinzuf%C3%BCgen/): Genauer: https://www.camp-firefox.de/forum/thema/135174-anwendungen-neuen-dateityp-bzw-anwendung-hinzuf%C3%BCgen/?postID=1207945#post1207945

Wegen Öffnen von *.C Dateien in Firefox, siehe "C:\Program Files\Mozilla Firefox\firefox.exe".

## Log

- 08.03.24: Im build-Schritt tritt der Fehler:
"Error: The process '/opt/hostedtoolcache/Ruby/3.1.4/x64/bin/bundle' failed with exit code 16"
auf. Als Lösung wird immer wieder auf das Installieren von [bundle lock --add-platform x86_64-linux](https://stackoverflow.com/questions/76756736/error-the-process-opt-hostedtoolcache-ruby-3-1-4-x64-bin-bundle-failed-with) verwiesen. Es muss aber hier eine andere Lösung geben, da x86_64-linux in Gemfile.lock vorhanden ist:

````text
PLATFORMS
  arm64-darwin-23
  x64-mingw-ucrt
  x86_64-linux
````  
