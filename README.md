# ENSDF Demo Repository

This is a demo of putting ENSDF data into a git repository.

All data comes from https://www.nndc.bnl.gov/ensarchivals/. 
1. It was downloaded by clicking on two data sets (2016-08-16, 2017-10-01).
2. An empty repository was created and the first data set copied in and committed.
3. The second data set was then copied over the previous data and committed.

After this simple conversion, git can tell you interesting things.

```
git log --stat
```
gives the following list of changed/added files from 2016-08-16 --> 2017-10-01

```
commit 61e838278b432550c1a64ca81d886fe9baecd54d (HEAD -> master)
Author: William A. Wieselquist <william.wieselquist@gmail.com>
Date:   Wed Jan 24 17:33:51 2018 -0500

    from https://www.nndc.bnl.gov/ensarchivals/ ensdf_171001_*

 data/ensdf.011 |    12 +-
 data/ensdf.015 |   354 +-
 data/ensdf.016 |    33 +-
 data/ensdf.017 |    13 +-
 data/ensdf.020 |     4 +-
 data/ensdf.021 |     5 +-
 data/ensdf.023 |   458 +--
 data/ensdf.028 |    10 +-
 data/ensdf.030 |    44 +-
 data/ensdf.033 |     7 +-
 data/ensdf.040 | 27075 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++----------------------------------------------------
 data/ensdf.051 | 12842 +++++++++++++++++++++++++++++------------------------------
 data/ensdf.055 |   628 +--
 data/ensdf.056 |    20 +-
 data/ensdf.070 | 16185 ++++++++++++++++++++++++++++++++++++++++++++------------------------------
 data/ensdf.073 |   241 +-
 data/ensdf.074 |  1044 +++--
 data/ensdf.089 |    95 +-
 data/ensdf.090 |    42 +
 data/ensdf.092 |    43 +
 data/ensdf.093 |   100 +-
 data/ensdf.094 |    43 +
 data/ensdf.096 |    41 +
 data/ensdf.099 | 12610 ++++++++++++++++++++++++++++++++++++----------------------
 data/ensdf.102 |   434 +-
 data/ensdf.106 |   260 +-
 data/ensdf.109 | 27647 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-----------------------------------------
 data/ensdf.115 |     3 +
 data/ensdf.123 |   248 +-
 data/ensdf.135 |   669 ++--
 data/ensdf.139 | 28562 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++---------------------------------------------------
 data/ensdf.146 | 29048 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++------------------------------------------------
 data/ensdf.152 |    66 +-
 data/ensdf.153 |    72 +-
 data/ensdf.154 |    52 +
 data/ensdf.155 |   117 +-
 data/ensdf.156 |   104 +
 data/ensdf.157 |   130 +-
 data/ensdf.158 | 15971 +++++++++++++++++++++++++++++++++++++++++++++++--------------------------
 data/ensdf.159 |   120 +-
 data/ensdf.160 |   263 +-
 data/ensdf.161 |   214 +-
 data/ensdf.162 |   112 +-
 data/ensdf.163 |   138 +-
 data/ensdf.164 |    70 +-
 data/ensdf.165 |    70 +-
 data/ensdf.166 |  3652 ++++++++---------
 data/ensdf.169 |    71 +-
 data/ensdf.170 |    81 +-
 data/ensdf.171 |    72 +-
 data/ensdf.172 |    74 +-
 data/ensdf.175 |     7 +-
 data/ensdf.180 |   941 -----
 data/ensdf.187 |    31 +-
 data/ensdf.189 | 18850 +++++++++++++++++++++++++++++++++++++++++++++++++++++---------------------------------
 data/ensdf.193 | 20216 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++---------------------------------
 data/ensdf.195 |   427 +-
 data/ensdf.196 |  5349 +++++++++++++------------
 data/ensdf.211 |  2530 ++++++------
 data/ensdf.222 |    74 +
 data/ensdf.236 |    85 +-
 data/ensdf.240 |    39 +
 data/ensdf.256 |  1521 +++----
 data/ensdf.258 |  1390 ++++---
 data/ensdf.295 |     0
 data/ensdf.296 |     0
 data/ensdf.297 |     0
 data/ensdf.298 |    54 +
 data/ensdf.299 |    54 +
 69 files changed, 142039 insertions(+), 89798 deletions(-)

```

I created two releases. For each you can directly download all the 
zipped files at the state of that release, e.g. :
https://github.com/wawiesel/ensdf-demo-repo/archive/2017-10-01.zip.




