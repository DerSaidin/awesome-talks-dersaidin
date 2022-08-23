# Awesome talks

Same idea as the [Awesome talks](https://github.com/JanVanRyswyck/awesome-talks) list, but curated according to my interests.

My interests are:
* Static Analysis
* Systems code: compilers, databases, operating systems (stuff likely to be written in C/C++/Rust or similar)
* Programming languages
* Security and Reliability
* Engineering practices

In addition to being intresting, the content should be worth knowing, and well presented to be awesome enough for this list.

#### Performance and Efficiency

* [Efficiency with Algorithms, Performance with Data Structures](https://www.youtube.com/watch?v=fHNmRkzxHWs) by **Chandler Carruth** [1:13:40] CppCon2014
  * Avoid wasted work. Design APIs to help avoid wasting work. Use dense data structures that maximize cache locality.
* [High Performance Code 201: Hybrid Data Structures](https://www.youtube.com/watch?v=vElZc6zSIXM) by **Chandler Carruth** [55:48] CppCon2016
  * Use small-size optimized containers. Use indirection for big objects in elements. Never use linked lists due to cache locality. Pack data in pointer bits.
* [Practical Data Oriented Design](https://vimeo.com/649009599) by **Andrew Kelley** [46:39] Handmade Seattle 2021
  * Use 32bit indexes instead of 64bit pointers. Store booleans out-of-band. Eliminate padding with struct-of-arrays. Store sparse data in hashmaps. Use "encodings" instead of OOP/polymorphism.
  * Also see [operation costs](http://ithare.com/infographics-operation-costs-in-cpu-clock-cycles/).

#### C and C++

* [Leak-Freedom in C++... By Default](https://www.youtube.com/watch?v=JfmTagWcqoE) by **Herb Sutter** [1:39:24] CppCon2016

#### Rust

* [Error Handling in Rust - A Pragmatic Approach](https://www.youtube.com/watch?v=jpVzSse7oJ4) by **Luca Palmieri** [33:40] RustLinz 2022-01-27
* [Rust: Your code can be perfect](https://www.youtube.com/watch?v=Q3AhzHq8ogs) by **Tris Oaten** [6:50]
  * A succinct argument for Rust.
* [Type-Driven API Design in Rust](https://www.youtube.com/watch?v=bnnacleqg6k) by **Will Crichton** [40:56]
  * Writing APIs that leverage the type system to prevent bad usage. Includes example of Typestate.

#### Nix

* [Nix + Docker, a match made in heaven](https://www.youtube.com/watch?v=WP_oAmV6C2U) by **Rok Garbas** [1:25:13] Bay Area Nix/NixOS User Group on December 21st, 2020 [files](https://github.com/garbas/talks/tree/main/2020-12-sf-meetup)
  * Great introduction to Nix language [starting here](https://www.youtube.com/watch?v=WP_oAmV6C2U&t=1630s), and walking through some example Nix scripts.

#### Static Analysis

* [What is Static Analysis?](https://www.youtube.com/watch?v=POvX4hYIoxg) by **Matt Might** [1:17:38] [Article](http://matt.might.net/articles/intro-static-analysis/)

#### Security

* [Security, Moore’s Law, And The Anomaly Of Cheap Complexity](https://www.err.ee/836236/video-google-0-projekti-tarkvarainseneri-ettekanne-cyconil) by **Thomas Dullien** [44:52] CyCon2018 [slides](https://docs.google.com/presentation/d/17bKudNDduvN-7hWv7S84MiHUj2AnOPNbwjTM8euDC8w/edit#slide=id.p1v)

#### Engineering Practices

* [Refactor or die](https://www.youtube.com/watch?v=fzmjXK9JZ9o) by **Mikhail Matrosov** [4:58] CppCon2017
* [Building Software Capital: How to write the highest quality code and why](https://www.youtube.com/watch?v=ta3S8CRN2TM) by **David Sankel** [59:38] CppCon2016
  * The [0:00 to 13:30] period is recommended for talking about technical debt and software capital, considering a business perspective. The rest of the talk is covered better elsewhere.
* [How Rust Views Tradeoffs](https://www.youtube.com/watch?v=2ajos-0OWts) by **Steve Klabnik** [46:33] QCon London 2019 [slides](https://qconlondon.com/system/files/presentation-slides/how_rust_views_tradeoffs.pdf)
  * The [5:56 to 13:06] section "Bending the Curve" poses a great design question: Is the tradeoff fundamental, or can we find a win-win?
  * The [13:06 to 26:45] section "Design is about Values" makes the point well. Other people's choices look strange if we forget they can have different values.
* [The Man Who Revolutionized Computer Science With Math](https://www.youtube.com/watch?v=rkZzg7Vowao) on **Leslie Lamport** [7:49]
  * Analogy:  Coding -> programming -> what program should achieve ::: typing -> writing -> ideas the writing should convey

#### 3D Graphics

* Nanite, A Deep Dive by **Brian Karis** [??:??] SIGGRAPH2021 [slides](http://advances.realtimerendering.com/s2021/Karis_Nanite_SIGGRAPH_Advances_2021_final.pdf), [InsideUnreal talk](https://youtu.be/TMorJX3Nj6U?t=3134)
