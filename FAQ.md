# Speed Test G FAQ

Speed Test G is a new performance testing system that takes the best parts of traditional speed tests and combines them with the benefits of benchmarks. For full details of how it works please watch this video: 
[Speed Test G - A new way to test real life smartphone performance](https://www.youtube.com/watch?v=0dsQiw-G8O8).

If you want to see why Speed Test G exists, please watch this video: [5 Reasons Why Smartphone Speed Tests Are Fundamentally Flawed](https://www.youtube.com/watch?v=W68nuVxOXaE)

## History
Speed Test G was launched in November 2018. In September/October 2019, Speed Test G 2.0 and Speed Test GX 2.0 were launched. For more information about V2.0 please watch these two videos: [Speed Test G 2.0 is Coming SOON!](https://www.youtube.com/watch?v=l8gFcyI2AaY) and [Speed Test G for iOS](https://www.youtube.com/watch?v=Dh6lz4gkgpY).

## Speed Test G YouTube Channel.
Speed Test G videos appear on the [Gary Explains](https://youtube.com/c/garyexplains) and also on the dedicated [Speed Test G](https://youtube.com/c/speedtestg) channel. The difference? Major and important Speed Test G videos will be published ion the GE channel, whereas more frequency videos with various combinations and permutations of devices will appear on the Speed Test G channel.

## 1. Where can I download Speed Test G so I can try it on my device?
You can't. Sorry. The sole reason is that I don't want smartphone makers to have access to this code and then try to "cheat" the system.
The idea is that this test remains independent and trustworthy.

## 2. Can Speed Test G run on iOS?
Yes. As of Speed Test G 2.0, it is available for Android and iOS. There are two versions of Speed Test G 2.0. The vanilla Speed Test G 2.0 (for Android only) and the cross-platform Speed Test GX 2.0 (for Android and iOS). The suites are almost identical except that Speed Test G 2.0 contains two 3D tests, one written in Unity and one written in Unreal. The GX version only has the Unity test. When comparing cross-platform GX times on one platform can be compared to GX times on the other.

## 3. Can the results of Speed Test G 1.0 be compared with the results from Speed Test G 2.0 or Speed Test GX 2.0?
No. Speed Test G 2.0 is a complete re-write and you can't compared the times.

## 4. Will you be making improvements to the test?
Abolsultey. First, there was Speed Test G 1.0, then Speed Test G 2.0 and Speed Test GX 2.0. Speed Test 3.0 will be developed at some point.

## 5. Why don't you do 5/10/50/100 test runs to ensure that the results are consistent?
Before recording, we do multiple test runs to ensure that the results we are seeing are correct. This includes running the tests from a known
state (i.e. after a reboot, etc). To ensure that CPU throttling (due to heat) isn't an issue the devices are left to cool before each test
run and before the recording of the final test. All tests are done in airplane mode. See question #6 for more.

## 6. Are the results consistent?
Yes. For example, three different test runs on three different days on the Pixel 3 XL yielded the times of 1:49.26, 1:49.27, and 1:49.33.
If a device is showing a difference of more than 1 (maximum 2) seconds between tests then showing isn't right then
the device/environment/conditions need to be examined.

## 7. Is it fair to compare a device running Android X.x with a device running a different version of Android, e.g. Android Y.y?
Yes, for two reasons. First, this is a device test. This means that when you buy the device, this is what you get. If the device underperforms
because of a software issue then consumers need to know that. Second, there are rarely major advances in Android performance from one version
to the next. It does happen, for example when Android moved from Davlik to ART, but that doesn't happen every day! If and when that becomes
a factor then it will be duly noted during the test run.

## 8. I read on a forum that if you tweak X and flash Y and alter Z then my device will run faster
That may well be true, but here we are testing the devices as supplied by the manufacturers.

## 9. Device XYZ has a Turbo mode/Performance mode/Burst mode/Game mode. Did you enable that before the test?
The devices are used in their defaults configurations. If the relevant performance mode is enabled by default that is how the device is
tested. Occasionally, if warranted, we may perform two tests, one with the mode enabled and one with it disabled.

## 10. Why haven't you tested Device SPQR? I have asked several times on social media or in the comments.
Could be for one of two reasons. 1) The device isn't that interesting. Sorry. 2) But more likely, I don't have access to that device at the moment. I don't have a huge box with every released device which I just open and take the device for the next video. Devices are expensive. Sometimes I can borrow a device. Sometimes my teammates have access to the device and I can use that. Sometimes I need to buy the device and hope to sell it afterwards.

## 11. Can the app show the individual tests times?
At the moment the test shows the CPU, CPU/GPU (mixed), and GPU times. Those numbers should be sufficient for most people.

## 12. Will you add sustained performance tests
Yes. I am planning on making a separate (but similar) test suite for testing throttling and sustained performance. Sustained performance testing will feature in separate videos and not as part of the normal Speed Test G run.

## 13. Any plans for a battery drain test?
Yes. I am planning on making a separate (but similar) test suite for testing battery life. Battery life testing will feature in separate videos and not as part of the normal Speed Test G run.

## 14. Speed Test G doesn't test RAM management like other speed tests.
That is true, it doesn't. At the moment I have no plans to change that, for philosophical and technical reasons. It certainly isn't planned for the Speed Test G 3.0.

## 15. Shouldn't the taping of the Start button be synchronized somehow (via Bluetooth, at a fixed time, by a laser bouncing off the moon)?
No. Each device records the total test time internally from within the Speed Test G app. The time reported at the end comes from the app itself, not from an external source, not from the video editing, not from a stopwatch, not from an hourglass. The devices can be started weeks apart but the time result is the same. The only benefit of synchronization is for the video and the "race" aspect of the video. For that, human synchronization is good enough.

## 16. Does the screen resolution affect the performance? If device A has a lower resolution screen, won't it be quicker? Is that fair?
Absolutely. And since this is a real-world test and not a theoretical test then that is what we are trying to test. If you buy device A,
is the GPU powerful enough to handle the display at the native resolution? Remember these tests are device tests, not processor (SoC) tests. For example, the Pixel 3 completes the test 5 seconds quicker than the Pixel 3 XL. Why? Because both have the same processor but one has a smaller screen resolution.

### OK, but I still want the devices to use the same screen resolution
From time to time, when demand necessitates, I will also make videos with devices set to their non-default screen resolutions.

## 17. Will you add an AI/Neural Networks/NPU test
That is certainly something that can be considered for V2.0. The simplest way would be to use the Android Neural Networks API. However, if the test was to become cross-platform (Android and iOS) then this would present a problem.

## 18. Is there a Speed Test G playlist.
Yes! [Speed Test G Playlist](https://www.youtube.com/playlist?list=PLxLxbi4e2mYF7bM129a7dW3Ulc9qLRdS3)

## 19. Is there a website with a leaderboard?
Yes! [SpeedTestG.com](http://speedtestg.com)

## 20. Can you show a leaderboard at the end of the video?
I currently don't show a leaderboard at the ends of the video because most people don't watch these videos in chronological order, which means that the leaderboard will be a) out of date, b) irrelevant unless you watched all the videos, c) confusing viewers who arrive via a search, d) misleading in that it might make device A look better than it is because at the time of that particular video devices X or Y or Z hadn't yet been tested.
Also see #19.

## 21. Why do some phones show "Speed Test G" and others "Speed Test G L"? Are they the same version?
During the development of Speed Test G I found some compatibility problems with the way the custom launcher interacts with the Android framework. Some phones would work one way, some a different way and some work either way! So there are technically two variants of Speed Test G, which are used depending on the actual phone. The changes are very minor, literally some flags which are used differently when the launcher installs itself. The changes don't alter the speed of the test run at all and don't impact the results. I have tested this empirically via devices which work with the L and non-L version, there is no difference in the final results.

## 22. What does the SQLite test do and why is it important?
The SQLite test adds 500 records to an SQLite database and then removes them. SQLite is the most widely deployed database in the world. It is the default way to store persistent data on Android and is used (probably unknown to most users) by hundreds of thousands of apps. Talking of SQLite on Android, the Google developer docs state that, "Apps that handle non-trivial amounts of structured data can benefit greatly from persisting that data locally. The most common use case is to cache relevant pieces of data. That way, when the device cannot access the network, the user can still browse that content while they are offline." In other words, if a device is able to process SQLite transactions quickly then it improves the overall user experience.

## 23. Why don't you include "off-screen" GPU test?
Because people don't play games off-screen. This is a real-world device test.

## 24. Why do your results show different relative performance numbers compared to the popular benchmark apps?
It comes down to three things:

1) What are you measuring? If you are measure raw CPU performance, with little access to the memory, lots of L1 and L2 cache hits, little or no access to the IO etc, then you will get a different result than if you are measure overall system performance. Overall system performance will include more memory access, more cache misses, more IO access plus other factors like app start-up time. Same goes with the GPU. Many of these benchmarks use "off-screen" testing to see how the GPU performs when it doesn't need to display the result and regardless of the screen resolution, that is fine, but at a system-level (real-world) level nobody plays games "off-screen". 

2) Can smartphone makers optimize their systems for benchmarks? Absolutely. Some have been caught cheating, by artificially increasing the performance of the CPU/GPU during a benchmark, but even if a manufacturer doesn't do that, you can be sure that it has a lab of people making sure that the device works very, very well for the popular benchmarks, so that they can make % claims during keynotes. See also question #1.

3) Improvements to CPU and GPU processing power never translate to the same increase at a system level as "the system" includes more than just the processor, there is the RAM, the internal storage, the motherboard (with interrupts and buses and IO channels etc), the display driver, the video encoder/decoder, other components of the SoC like the neural engine etc. Bottom line: Speed Test G tests the whole device, not just the CPU or GPU. That is what users will see in the real world.
