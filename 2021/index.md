---
layout: year
title: 2021
---

# Science, Art, Magic: Using and Developing The Graal Compiler

**What:** Third Graal Workshop at [CGO](https://www.cgo.org).

**When:** February 27, 2021. ([See program for times in your time zone](https://conf.researchr.org/program/cgo-2021/program-cgo-2021))

**Where:** Virtual.

Researchers and practitioners are invited to participate in the Third Graal Workshop at [CGO 2021](https://conf.researchr.org/home/cgo-2021). The workshop is virtually co-located with [PPoPP](https://conf.researchr.org/home/PPoPP-2021), [CC](https://conf.researchr.org/home/CC-2021) and [HPCA](https://hpca-conf.org/2021/).

Topics of interest (not limited to):
- making effective use of the [GraalVM compiler](https://github.com/oracle/graal),
- performance evaluations and opportunities with GraalVM on benchmarks and applications,
- developing new features and optimizations in GraalVM,
- creative and novel uses of the GraalVM compiler infrastructure.

Talk about the workshop on Twitter using [#graalcgo2021](https://twitter.com/search?q=%23graalcgo2021) and follow us [@graalcgo](https://twitter.com/graalcgo).

## Program

All times EST (UTC-5).

| Start         | End           | Title                                                                                                                                                                                        | Speaker(s)                                  |
| ------------: | ------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------ |
|  8:00&nbsp;AM |  8:05&nbsp;AM | Welcome                                                                                                                                                                                      | Uma Srinivasan                              |
|  8:05&nbsp;AM |  9:00&nbsp;AM | [Keynote: Exploring speedup opportunities in the GraalVM compiler](slides/0_Keynote_Exploring_speedup_opportunities_in_the_GraalVM_compiler.pdf)                                             | François Farquet                            |
|  9:00&nbsp;AM |  9:30&nbsp;AM | [Babashka: a native Clojure interpreter for scripting.](slides/1_Babashka_a_native_Clojure_interpreter_for_scripting.pdf)                                                                    | Michiel Borkent                             |
|  9:30&nbsp;AM | 10:00&nbsp;AM | Truffle Startup and Warmup Challenges and Opportunities                                                                                                                                      | Chris Seaton                                |
| 10:00&nbsp;AM | 10:30&nbsp;AM | [One more gap bridged towards practice -- support serialization feature in native image](slides/3_One_more_gap_bridged_towards_practice_-_support_serialization_feature_in_native_image.pdf) | Ziyi Lin, Wei Kuai, and Sanhong Li          |
| 10:30&nbsp;AM | 11:00&nbsp;AM | Improving Compiler Optimizations by Employing Machine Learning                                                                                                                               | Raphael Mosaner                             |
| 11:00&nbsp;AM | 11:30&nbsp;AM | [GraalVM at Facebook](slides/5_GraalVM_at_Facebook.pdf)                                                                                                                                      | Chen Li                                     |
| 11:30&nbsp;AM | 12:00&nbsp;PM | [Tracking Performance of Graal on Public Benchmarks](slides/6_Tracking_Performance_of_Graal_on_Public_Benchmarks.pdf)                                                                        | Petr Tuma, Vojtěch Horký, and Lubomír Bulej |
| 12:00&nbsp;PM |  3:00&nbsp;PM | **Break**                                                                                                                                                                                    |                                             |
|  3:00&nbsp;PM |  3:30&nbsp;PM | [Performance understanding tools for GraalVM using eBPF](slides/7_Performance_understanding_tools_for_GraalVM_using_eBPF.pdf)                                                                | Andy Nisbet, Salim Salim, and Mikel Lujan   |
|  3:30&nbsp;PM |  4:00&nbsp;PM | [Strato (Twitter PaaS) & Graal Native Image](slides/8_Strato_and_Graal_Native_Image.pdf)                                                                                                     | Anton Panasenko                             |
|  4:00&nbsp;PM |  5:00&nbsp;PM | Panel Session: Graal on AArch64                                                                                                                                                              |                                             |
{:.table .table-sm}

### Keynote

| ------------ | --- |
| **Speaker**  | François Farquet (Oracle Labs)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Title**    | Explore speedup opportunities in the GraalVM compiler                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Abstract** | This talk will cover the different approaches the GraalVM compiler team applies in its quest to a better performing compiler, release after release. Regression tracking or comparison against competing compilers are obviously necessary not to fall behind, but a more creative approach can lead to unexpected low-hanging fruits: benchmarking non-default compiler configurations potentially produces better performance, giving the opportunity to fix the suboptimal pattern present in the compiler. <br><br> Moreover, we'll see how this hyperparameter analysis helped in understanding the compiler's trade-offs and in finding optimal default values for all compiler options. From there, we can also go a step further and expose those trade-offs to let the users take the best decision based on their scenario. |
| **Bio**      | François Farquet is a Principal Performance Engineer at Oracle located somewhere in the Swiss Alps. He is a member of the GraalVM compiler team in charge of benchmarking, performance tracking and hyperparameter tuning.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
{:.table .table-sm}

### Panel Session

**Topic**: Graal on AArch64


| Name            | Affiliation | Twitter                                         |
| --------------- | :---------- | :-----------                                    |
| Monica Beckwith | Microsoft   | [@mon_beck](https://twitter.com/mon_beck)       |
| Tom Shull       | Oracle Labs |                                                 |
| Alan Hayward    | Arm         |                                                 |
| Flavio Brasil   | Twitter     | [@flaviusbraz](https://twitter.com/flaviusbraz) |
| Tianxiao Gu     | Alibaba     |                                                 |
| Andrew Dinn     | Red Hat     |                                                 |
{:.table .table-sm}

## Organizers

| Name            | Email                                                     | Twitter                                         |
| --------------- | :-------------------------------------------------------- | :---------------------------------------------- |
| Uma Srinivasan  | [usrinivasan@twitter.com](mailto:usrinivasan@twitter.com) | [@umatweep](https://twitter.com/umatweep)       |
| Niklas Vangerow | [nvangerow@twitter.com](mailto:nvangerow@twitter.com)     | [@nvgrw](https://twitter.com/nvgrw)             |
| Flavio Brasil   | [fbrasil@twitter.com](mailto:fbrasil@twitter.com)         | [@flaviusbraz](https://twitter.com/flaviusbraz) |
{:.table .table-sm}

## Program Committee

Alan Hayward (Arm), Chris Seaton (Shopify), Christian Wimmer (Oracle Labs), David Leopoldseder (Oracle Labs/JKU Linz), Niklas Vangerow (Twitter), Tianxiao Gu (Alibaba), Will Holen (Facebook)

## Previous years

* [2020, San Diego CA](../2020/)
* [2019, Washington DC](../2019/)
