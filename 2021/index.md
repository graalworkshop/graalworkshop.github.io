---
layout: year
title: 2021
---

# Science, Art, Magic: Using and Developing The Graal Compiler

The Third Graal Workshop was held virtually at [CGO](https://www.cgo.org) on February 27, 2021.

Talk about the workshop on Twitter using [#graalcgo2021](https://twitter.com/search?q=%23graalcgo2021) and follow us [@graalcgo](https://twitter.com/graalcgo).

You can find the recordings for all sessions on [YouTube](https://www.youtube.com/playlist?list=PL5s7-0PKqopPJCpW3wThCBd-Hn3fAk5wl) and individual video links below.

<style>
    img.half-width {
        width: 49%;
    }
</style>

[![Group photo from the first session](images/session1.png){:.img-fluid .half-width}](images/session1.png)
[![Group photo from the second session](images/session2.png){:.img-fluid .half-width}](images/session2.png)

Topics for discussion included exploring speedup opportunities in the GraalVM compiler, novel uses of GraalVM's infrastructure, new features in GraalVM, and benchmarking the GraalVM compiler.

## Program

All times EST (UTC-5).

| Start         | End           | Title                                                                                 | Resources                                                                                                                                                          | Speaker(s)                                  |
| ------------: | ------------: | :------------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------ |
| 8:00&nbsp;AM  | 8:05&nbsp;AM  | Welcome                                                                               | [Slides](slides/Welcome.pdf)                                                                                                                                       | Uma Srinivasan                              |
| 8:05&nbsp;AM  | 9:00&nbsp;AM  | Keynote: Exploring speedup opportunities in the GraalVM compiler                      | [Slides](slides/0_Keynote_Exploring_speedup_opportunities_in_the_GraalVM_compiler.pdf)                        [Video](https://www.youtube.com/watch?v=ri-7s5iPzFc) | François Farquet                            |
| 9:00&nbsp;AM  | 9:30&nbsp;AM  | Babashka: a native Clojure interpreter for scripting.                                 | [Slides](slides/1_Babashka_a_native_Clojure_interpreter_for_scripting.pdf)                                    [Video](https://www.youtube.com/watch?v=Yjeh57eE9rg) | Michiel Borkent                             |
| 9:30&nbsp;AM  | 10:00&nbsp;AM | Truffle Startup and Warmup Challenges and Opportunities                               | [Slides](slides/2_Truffle_Startup_and_Warmup_Challenges_and_Opportunities.pdf)                                [Video](https://www.youtube.com/watch?v=w4o0hTl6AMg) | Chris Seaton                                |
| 10:00&nbsp;AM | 10:30&nbsp;AM | One more gap bridged towards practice -- support serialization fature in native image | [Slides](slides/3_One_more_gap_bridged_towards_practice_-_support_serialization_feature_in_native_image.pdf)  [Video](https://www.youtube.com/watch?v=ws6qFX-3xa8) | Ziyi Lin                                    |
| 10:30&nbsp;AM | 11:00&nbsp;AM | Improving Compiler Optimizations by Employing Machine Learning                        | [Slides](slides/4_Improving_Compiler_Optimizations_by_Employing_Machine_Learning.pdf)                         [Video](https://www.youtube.com/watch?v=D75lXbkisTs) | Raphael Mosaner                             |
| 11:00&nbsp;AM | 11:30&nbsp;AM | GraalVM at Facebook                                                                   | [Slides](slides/5_GraalVM_at_Facebook.pdf)                                                                    [Video](https://www.youtube.com/watch?v=Hepjf00LJrM) | Chen Li                                     |
| 11:30&nbsp;AM | 12:00&nbsp;PM | Tracking Performance of Graal on Public Benchmarks                                    | [Slides](slides/6_Tracking_Performance_of_Graal_on_Public_Benchmarks.pdf)                                     [Video](https://www.youtube.com/watch?v=kQO4ELUkMb8) | Petr Tuma                                   |
| 12:00&nbsp;PM | 3:00&nbsp;PM  | **Break**                                                                             |                                                                                                                                                                    |                                             |
| 3:00&nbsp;PM  | 3:30&nbsp;PM  | Performance understanding tools for GraalVM using eBPF                                | [Slides](slides/7_Performance_understanding_tools_for_GraalVM_using_eBPF.pdf)                                 [Video](https://www.youtube.com/watch?v=CKdb1aDNUU4) | Andy Nisbet                                 |
| 3:30&nbsp;PM  | 4:00&nbsp;PM  | Strato (Twitter PaaS) & Graal Native Image                                            | [Slides](slides/8_Strato_and_Graal_Native_Image.pdf)                                                          [Video](https://www.youtube.com/watch?v=Leosx0eKKbU) | Anton Panasenko                             |
| 4:00&nbsp;PM  | 5:00&nbsp;PM  | Panel Session: Graal on AArch64                                                       |                                                                                                                                                                    |                                             |
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
