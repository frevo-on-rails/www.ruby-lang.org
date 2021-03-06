---
layout: news_post
title: "Ruby 2.1.0-preview2 telah dirilis"
author: "nurse"
translator: "gozali"
date: 2013-11-22 22:00:00 UTC
lang: id
---

Kami sangat senang untuk mengumumkan rilis dari Ruby 2.1.0-preview2. 
Silakan uji fitur baru di Ruby 2.1 sebelum rilis akhir!

## Perubahan penting dari preview 1

* perbaikan [Heap Overflow dalam Floating Point Parsing (CVE-2013-4164)](https://www.ruby-lang.org/id/news/2013/11/22/heap-overflow-in-floating-point-parsing-cve-2013-4164/)
* "literal".freeze sekarang dioptimalkan [#9042](https://bugs.ruby-lang.org/issues/9042)
* f suffix dari String Literal dihapus [#9042](https://bugs.ruby-lang.org/issues/9042)
* perbaikan isu memory consuming pada RGenGC ([r43532](http://svn.ruby-lang.org/cgi-bin/viewvc.cgi?view=rev&revision=43532) dan [r43755](http://svn.ruby-lang.org/cgi-bin/viewvc.cgi?view=rev&revision=43755))
* penambahan Exception#cause [#8257](https://bugs.ruby-lang.org/issues/8257)
* pemutakhiran pustaka seperti json, nkf, rake, RubyGems, dan RDoc.

## Unduh

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.tar.bz2](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.tar.bz2)

      SIZE:   11432454 bytes
      MD5:    9d566a9b2d2e7e35ad6125e2a14ce672
      SHA256: 780fddf0e3c8a219057d578e83367ecfac5e945054b9f132b3b93ded4802d1ce

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.tar.gz](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.tar.gz)

      SIZE:   14416029 bytes
      MD5:    ba2b95d174e156b417a4d580a452eaf5
      SHA256: a9b1dbc16090ddff8f6c6adbc1fd0473bcae8c69143cecabe65d55f95f6dbbfb

* [http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.zip](http://cache.ruby-lang.org/pub/ruby/2.1/ruby-2.1.0-preview2.zip)

      SIZE:   16110720 bytes
      MD5:    2ad1aa3d89ae32607cf14fc73b192de1
      SHA256: cc2f7f8e05daed716489e5480e6365a711a13ed7747dbc59e989a41fe2805076

## Perubahan dari 2.0

Perubahan penting adalah:

* VM (method cache)
* RGenGC (Lihat [presentasi ko1's di RubyKaigi](http://rubykaigi.org/2013/talk/S73) dan [presentasi RubyConf 2013](http://www.atdot.net/~ko1/activities/rubyconf2013-ko1_pub.pdf))
* perbaikan [#8481](https://bugs.ruby-lang.org/issues/8481) [#8571](https://bugs.ruby-lang.org/issues/8571)
* perubahan syntax
  * Rational/Complex Literal [#8430](https://bugs.ruby-lang.org/issues/8430)
  * def's return value [#3753](https://bugs.ruby-lang.org/issues/3753)
* Bignum
  * menggunakan 128bit integers [#8509](https://bugs.ruby-lang.org/issues/8509)
  * menggunakan GMP [#8796](https://bugs.ruby-lang.org/issues/8796)
* String#scrub [#8414](https://bugs.ruby-lang.org/issues/8414)
* Socket.getifaddrs [#8368](https://bugs.ruby-lang.org/issues/8368)
* RDoc 4.1.0.preview.2 dan RubyGems 2.2.0.preview.2

Lihat rincian perubahan: [NEWS di repository Ruby (WIP)](https://github.com/ruby/ruby/blob/v2_1_0_preview2/NEWS).

Presentasi ko1 di toruby: [All about Ruby 2.1](http://www.atdot.net/~ko1/activities/toruby05-ko1.pdf)

Konstantin Haase (@konstantinhaase) menulis sebuah ringkasan yang bagus dalam 
artikel di blognya: [What's new in Ruby 2.1?](http://rkh.im/ruby-2.1).

## Komentar Rilis

Isu - isu yang diketahui:

[http://bugs.ruby-lang.org/projects/ruby-trunk/issues?query_id=102](http://bugs.ruby-lang.org/projects/ruby-trunk/issues?query_id=102)

Lihat juga jadwal rilis dan informasi lainya:

[http://bugs.ruby-lang.org/projects/ruby-trunk/wiki/ReleaseEngineering210](http://bugs.ruby-lang.org/projects/ruby-trunk/wiki/ReleaseEngineering210)

