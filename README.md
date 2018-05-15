# patchinfo
##
Utility for working with patches

#installation
    sudo install -m 755 ./patchinfo /usr/local/bin

#usage
    $ patchinfo test/0001-New-Added-README-file.patch
    0001-New-Added-README-file.patch
    From: Miroslav Safr <Miroslav.Safr@gmail.com>
    Date: Tue, 15 May 2018 16:58:38 +0300
    Subject: [PATCH] New: Added README file
     file     : size:0 created:- modified:2018-05-15 16:58:44.869331211 +0300
     access   : -rw------- 600 unified diff output, ASCII text
     file diff: patches:1 changed files:1
     line diff: +:4 -:0 changed:4
     char diff: changed:12 words 118 chars

