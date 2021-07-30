+++
title = "Curriculum Vitae"
hidden = true
date = "2021-07-11"
date_update = true
+++

## Education

### Shanghai Jiao Tong University

Bachelor of Engineering, Computer Science \
September 2018 — June 2022 (Expected) \
Shanghai, China

<details>
<summary>First 3 years GPA: 93.97 / 100 (Rank: 1 / 154) <br> (Click to Expand)</summary>

* Full-score (100/100) courses
    * CS154: C++ Programming Language (Fall 2018)
    * CS149: Data Structure (Spring 2019)
    * MS125: Principle and Practice of Computer Algorithms (Summer 2019)
    * CS241: Principles and Practice of Problem Solving (Fall 2019)
    [[final project + presentation]](https://github.com/skyzh/Meteor)
    * CS307: Operating System (Spring 2020)
    * CS356: Operating System Projects (Spring 2020)
    [[final project + presentation]](https://github.com/skyzh/oom_killer)
    * CS145: Computer Architecture Experiments (Spring 2020)
    [[final project + report]](https://github.com/skyzh/mips-cpu)
    * ... and 2 more
* Other A+ courses
    * (95/100) CS359: Computer Architecture (Spring 2020)
    * (96/100) EI209: Computer Organization (Spring 2020)
    * (96/100) CS339: Computer Networks (Fall 2020)
    * (95/100) CS236: Cloud Computing (Fall 2020)
    * (99/100) CS410: Artificial Intelligence (Fall 2020)
    * (99/100) CS467: Theory of Computation (Fall 2020)
    * ... and 16 more
</details>

### No.2 High School Attached to East China Normal University

High School \
September 2015 — June 2018 \
Shanghai, China

## Experience

### TerarkDB Team

Storage System R&D Intern, Bytedance \
June 2021 — Now \
Beijing, China

I worked on TerarkDB for Zoned Namespace SSDs, and an unnamed
file system for next-generation key-value storage engine.

### TiKV Storage Team

Storage System R&D Intern, PingCAP \
August 2020 — January 2021 \
Shanghai, China

I built a key-value storage engine [AgateDB][agatedb].
Inspired by WiscKey paper, AgateDB separates large values 
from the LSM tree into a value log. This design leads to a 
10x write speedup on large values, compared with the
current storage engine used by TiKV. AgateDB is a Rust port of [BadgerDB][badger].

[badger]: https://github.com/dgraph-io/badger
[agatedb]: https://github.com/tikv/agatedb

## Open Source Contributions

### TiKV Community

May 2020 — Now

* TiKV Maintainer, Co-leader of Coprocessor SIG
    * Migrate the TiKV Coprocessor framework to use TiDB Chunk format (similar to Apache Arrow) during the computation process, as a mentee in Community Bridge mentorship. This is so-called [Full Chunk-based Computing](https://github.com/tikv/tikv/issues/7724) project. (May 2020 — July 2020)
        * Also check out the [blog post](https://tikv.org/blog/communitybridge-mentorship/) by me.
        * And the [presentation](https://youtu.be/46zhiiDBT5w?t=682) on TiKV monthly meeting.
    * Review patches and help grow the community.
* Mentor of TiKV LFX Mentorship
    * Mentored on [Enum/Set support in TiKV](https://github.com/tikv/tikv/issues/9066) project. (September 2020 — December 2020)
        * Also check out the [blog post](https://tikv.org/blog/my-experience-in-flx-for-tikv/) by our mentee Xuanwo.
    * Co-mentored on [Coprocessor Plugin](https://github.com/tikv/tikv/issues/9747) project with [Andy Lok](https://github.com/andylokandy). (March 2021 — May 2021)
        * Also check out the [blog post](https://tikv.org/blog/lfx-2021-copr-v2/) by our mentee Andreas Zimmerer.
* Develop AgateDB (after my internship in PingCAP)

### Shanghai Jiao Tong University Linux User Group

May 2019 — Now

[SJTUG](https://github.com/sjtug/), or Shanghai Jiao Tong University Linux User Group,
is an open-source community as well as a Linux user group in SJTU.

* Maintainer of SJTUG mirror service (May 2019 — Now)
    * SJTUG mirror serves 70k users, 1.5 million requests, and 3TB of data per day.
    * Build an open-source [mirror infrastructure](https://github.com/sjtug/mirror-docker-unified).
    * Set up [Siyuan mirror server](https://mirror.sjtu.edu.cn).
    * Build [mirror-intel](https://github.com/sjtug/mirror-intel), which enables us to host the first Flathub mirror in China.
    * Leverage object storage service to store files with [mirror-clone](https://github.com/sjtug/mirror-clone).
* Maintainer of SJTU TeX Templates (May 2021 — Now)
    * Maintainer of [SJTUThesis](https://github.com/sjtug/SJTUThesis), the LaTeX thesis template for all SJTU students.
    * Incubate [SJTUBeamer](https://github.com/sjtug/SJTUBeamer) template.

## Other Experience

### TA in PPCA Ray-Tracing Project

July 2020 — August 2020

Principle and Practice of Computer Algorithms (PPCA)
is a project-oriented course for first-year undergraduates,
where they use what they have learned to build a toy application
in one month. I designed a lab based on *Ray Tracing In One Weekend*
and mentored 13 students to make a ray-tracer with the Rust
programming language.

You may take a look at [Student Project Showcase](https://github.com/skyzh/raytracer-tutorial/issues/9) and [Project Template and Tutorials](https://github.com/skyzh/raytracer-tutorial).

## Talks

* Paper Reading on “Lethe: A Tunable Delete-Aware LSM Engine” (October 2020)
    * Video on [Bilibili](https://www.bilibili.com/video/BV1Yi4y1j74S)
    * [Original Paper](https://arxiv.org/abs/2006.04777)
* Paper Reading on “FPTree: A Hybrid SCM-DRAM Persistent and Concurrent B-Tree for Storage Class Memory” (May 2021)
    * Video on [Bilibili](https://www.bilibili.com/video/BV1wf4y1Y7eZ)
    * [Original Paper](https://wwwdb.inf.tu-dresden.de/misc/papers/2016/Oukid_FPTree.pdf)
    * [Slides](https://docs.google.com/presentation/d/1RHVP81jJHqHhzHACu98RZMNXxRMsa1pPllqjVkfIM7g)
* Sharing of “The SJTUG Mirror Service” (July 2021, at [Tunight](https://tuna.moe/event/2021/summer-salon/))
    * [Slides](https://github.com/skyzh/skyzh.github.io/files/6757800/The.SJTUG.Mirror.Service.pdf)

## Projects

See [Build things for fun, for all](/pages/projects).

## Honors and Awards

National Scholarship (Ministry of Education of P.R. China), 2019

I was also qualified for National Scholarship in 2020, but I gave that chance to
my classmates. It's boring to get the same award every year.

</details>
