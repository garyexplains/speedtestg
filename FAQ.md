# Speed Test G FAQ

Speed Test G is a new performance testing system that takes the best parts of traditional speed tests and combines them with the benefits of benchmarks. For full details of how it works please watch this video: 
[Speed Test G - A new way to test real life smartphone performance](https://www.youtube.com/watch?v=0dsQiw-G8O8).

## 1. Where can I download Speed Test G so I can try it on my device?
You can't. Sorry. The sole reason is that I don't want smartphone makers to have access to this code and then try to "cheat" the system.
The idea is that this test remains independent and trustworthy.

## 2. Can Speed Test G run on iOS?
No. The test suite is written specifically for Android. In the future it may be possible to create a port to iOS, however, that is a long-term 
possibility, not a short-term goal.

## 3. Can you compare the latest Snapdragon with the latest Apple processor?
Please see question #2.

## 4. Will you be making improvements to the test?
Abolsultey. This is Speed Test G 1.0. At some point, I will release Speed Test G 2.0. Current aims include greater complexity, Unreal 3D tests alongside the Unity tests, possibly the use of Vulcan, and much more.

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
For one of two reasons. 1) The device isn't that interesting. Sorry. 2) But more likely, I don't have access to that device at the moment. I don't have a huge box with every released device which I just open and take the device for the next video. Devices are expensive. Sometimes I can borrow a device. Sometimes my teammates have access to the device and I can use that. Sometimes I need to buy the device and hope to sell it afterwards.

## 11. Can the app show the individual tests times?
Changes in that area are coming. Current plans are to show three times alongside the total time: "Mainly CPU", "Mixed CPU/GPU", "Mainly GPU".

## 12. Will you add networking tests?
That isn't planned for the moment.

## 13. Any plans for a battery drain test?
Not at this time.

## 14. Speed Test G doesn't test RAM management like other speed tests.
That is true, it doesn't. At the moment I have no plans to change that, for philosophical and technical reasons. It certainly isn't planned for the Speed Test G 2.0.

## 15. Shouldn't the taping of the Start button be synchronized somehow (via Bluetooth, at a fixed time, by a laser bouncing off the moon)?
No. Each device records the total test time internally from with the Speed Test G app. The time reported at the end comes from the app itself, not from an external source, not from the video editing, not from a stopwatch, not from an hourglass. The devices can be started weeks apart but the time result is the same. The only benefit of synchronization is for the video and the "race" aspect of the video. For that, human synchronization is good enough.

## 16. Does the screen resolution affect the performance? If device A has a lower resolution screen, won't it be quicker? Is that fair?
Absolutely. And since this is a real-world test and not a theoretical test then that is what we are trying to test. If you buy device A,
is the GPU powerful enough to handle the display at the native resolution? Remember these tests are device tests, not processor (SoC) tests. For example, the Pixel 3 completes the test 5 seconds quicker than the Pixel 3 XL. Why? Because both have the same processor but one has a smaller screen resolution.
