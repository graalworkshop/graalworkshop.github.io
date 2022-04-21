---
layout: year
title: 2022
---

# Science, Art, Magic: Using and Developing The Graal Compiler

The Fourth Graal Workshop was held virtually at [CGO](https://www.cgo.org) on April 2, 2022.

Talk about the workshop on Twitter using [#graalcgo2022](https://twitter.com/search?q=%23graalcgo2022) and follow us [@graalcgo](https://twitter.com/graalcgo).

Topics for discussion included exploring speedup opportunities with GraalVM Native Image, novel uses of Truffle, and new features in the GraalVM compiler.

## Program

All times EDT (UTC-4).

| Start         | End           | Title                                                                 | Resources                                                                                                                | Speaker(s)                 |
| ------------: | ------------: | :-------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------- | :------------------------- |
| 9:00&nbsp;AM  | 9:05&nbsp;AM  | Welcome                                                               |                                                                                                                          | Niklas Vangerow            |
| 9:05&nbsp;AM  | 10:00&nbsp;AM | Keynote: Static Java: The GraalVM Native Image Programming Model      | [Slides](slides/0_Native_Image_Programming_Model.pdf), [Recording](https://youtu.be/qNG0fFBpUGU)                         | Christian Wimmer           |
| 10:00&nbsp;AM | 10:30&nbsp;AM | Faster Native Image development build times with Quick Build mode     | [Slides](slides/1_Quick_build_Mode.pdf), [Recording](https://youtu.be/TY-2G4ulEBc)                                       | Carlo Refice               |
| 10:30&nbsp;AM | 11:00&nbsp;AM | Improving GraalVM Reflection File Generation                          | [Slides](slides/2_Improving_GraalVM_Reflection_File_Generation.pdf), [Recording](https://youtu.be/_LqicKO29lo)           | Nicolas Toper              |
| 11:00&nbsp;AM | 11:30&nbsp;AM | **Break**                                                             |                                                                                                                          |                            |
| 11:30&nbsp;AM | 12:00&nbsp;PM | Truffle Interpreter Performance without the Holy Graal                | [Slides](slides/3_Truffle_Interpreter_Performance_without_the_Holy_Graal.pdf), [Recording](https://youtu.be/7ICtHAwELX4) | Stefan Marr                |
| 12:00&nbsp;PM | 12:30&nbsp;PM | TruffleString: highly optimized cross-language string implementation. | [Slides](slides/4_TruffleStrings.pdf), [Recording](https://youtu.be/wI-qcZUA2vA)                                         | Josef Haider               |
| 12:30&nbsp;PM | 1:00&nbsp;PM  | State of AArch64 on GraalVM                                           | [Slides](slides/5_GraalVM_State_of_AArch64.pdf), [Recording](https://youtu.be/7Xuy1tFFjSo)                               | Thomas Shull               |
| 1:00&nbsp;PM  | 1:30&nbsp;PM  | Call-Target Agnostic Keyword Arguments                                | [Slides](slides/6_Call-Target_Agnostic_Keyword_Arguments.pdf), [Recording](https://youtu.be/RVqY1FRUm_8)                 | Maple Ong and Chris Seaton |
| 1:30&nbsp;PM  | 2:00&nbsp;PM  | Tuning autovectorization in Graal                                     | [Slides](slides/7_Tuning_Autovectorization_in_Graal.pdf), [Recording](https://youtu.be/DDD0T_6y1Lw)                      | Yunjie Pan                 |
| 2:00&nbsp;PM  | 2:30&nbsp;PM  | **Break**                                                             |                                                                                                                          |                            |
| 2:30&nbsp;PM  | 3:45&nbsp;PM  | Lightning Talks                                                       |                                                                                                                          |                            |
| 3:45&nbsp;PM  | 4:00&nbsp;PM  | Closing remarks &amp; survey                                          |                                                                                                                          | Uma Srinivasan             |
{:.table .table-sm}

### Keynote

| ------------ | --- |
| **Speaker**  | Christian Wimmer (Oracle Labs) |
| **Title**    | Static Java: The GraalVM Native Image Programming Model |
| **Abstract** | In this talk we will present our vision for "Static Java": the programming model enabled by GraalVM Native Image. Applications are initialized at image build time, to allow fast startup time and low memory footprint at run time. Counterintuitively, the ahead-of-time compilation of Java bytecode to machine code is not part of the programming model. But since it is an important implementation detail, we will also talk about the benefits and problems of compiling ahead-of-time compilation. We will show where static analysis helps, what the limitations of static analysis are, which compiler optimizations work well both for JIT and AOT compilation, and where additional compiler phases for AOT compilation are necessary. |
| **Bio**      | Christian Wimmer is the architect of GraalVM Native Image. He was one of the first engineers of the GraalVM project, and helped growing it from a research project of Oracle Labs to a supported Oracle product. He believes that all languages should be equally fast, and that we therefore need to stop writing individual VMs and instead have one polyglot VM. His research interests span from compilers, virtual machines, and secure systems to component-based software architectures. [More info](https://conf.researchr.org/profile/cgo-2022/christianwimmer). |
{:.table .table-sm}

## Organizers

| Name            | Email                                                     | Twitter                                         |
| --------------- | :-------------------------------------------------------- | :---------------------------------------------- |
| Niklas Vangerow | [nvangerow@twitter.com](mailto:nvangerow@twitter.com)     | [@nvgrw](https://twitter.com/nvgrw)             |
| David Degazio   | [davidd@twitter.com](mailto:davidd@twitter.com)           | [@elucentdev](https://twitter.com/elucentdev)   |
| Uma Srinivasan  | [usrinivasan@twitter.com](mailto:usrinivasan@twitter.com) | [@umatweep](https://twitter.com/umatweep)       |
{:.table .table-sm}

## Program committee

Christian Wimmer (Oracle Labs), David Leopoldseder (Oracle Labs/JKU Linz), Niklas Vangerow (Twitter),
Kingsum Chow (Alibaba), Kevin Menard (Shopify), Monica Beckwith (Microsoft), Uma Srinivasan (Twitter).

## Previous years

* [2021, Virtual](../2021/)
* [2020, San Diego CA](../2020/)
* [2019, Washington DC](../2019/)
