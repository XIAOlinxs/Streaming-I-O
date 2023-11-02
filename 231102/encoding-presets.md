# Encoding presets

The encoding preset is a set of parameters of how the video should be encoded -- container, video and audio codecs, additional parameters.

When you configure a destination, you can select one of the available presets or create a new one:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1dKgxEM\_leS1EgCqR%2F-Mb1drCV\_YWY9PMiirwb%2Fimage.png?alt=media\&token=690f9c7d-0d90-4446-b063-8537789024c6)

If the "_Create a new preset_" is selected, you can add a new one by clicking the **+** button. For the existing presets, you can open the configuration menu with the edit button:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1dKgxEM\_leS1EgCqR%2F-Mb1dwsqH-rTDlSgVMEC%2Fimage.png?alt=media\&token=8a4e24d4-92b3-4cd6-8f17-293ba19a344b)

Here is how the preset settings look like:

![](.gitbook/assets/右边设置栏.png)

You should set the name of the preset with the **Preset name** field.

**Container** list contains available file format for recording:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1c\_q0l6IvvRtvy5Tz%2F-Mb1cpjxkAgxV5lErMbg%2Fimage.png?alt=media\&token=748b9c42-26ab-46c5-9f33-96cb8fedf77c)

Different containers support different sets of available video and audio codecs. So you should choose the Container first. Once the container is set, you can set the video and audio codecs.

The Video contains a list of available video codecs:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXGz0Kg-Cu4Z\_av8xlC%2Fimage.png?alt=media\&token=47149602-75f8-4fb9-8d3e-83cb7cdbdeff)

Below there are fields for **Bitrate** and the **Keyframe interval**.

The bitrate is set in formats of Mb or kb. For example, "_15M_" or "_2500K_".

The keyframe interval is set in frame units. For example, "_60_" means to have one keyframe on 60 processed frames. So for 30 fps input, this results in a 2-seconds keyframe interval, and for 60 fps input, it is a 1-second interval.

The Audio contains available audio sources:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH-0i07gYSMGhgSUK-%2Fimage.png?alt=media\&token=cdccf77c-e671-4552-8557-4f6d76eeed43)

**Timecode** lists the possible start timecode options:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1c\_q0l6IvvRtvy5Tz%2F-Mb1d1YrPGw\_UGZDEqm-%2Fimage.png?alt=media\&token=6d451a34-00e4-4c38-ac2a-49f757d5c595)

* Use embedded timecode -- if a source contains embedded timecode data, the start timecode of the resulting files matches the timecode of the source. For example, if you have an SDI input with embedded timecode, the resulting files will have the start timecode value that matches the timecode from this SDI source.
* Use the system time -- use the local time of your machine as the start timecode value for the resulting files.
* Manual timecode -- set the timecode manually in _hh:mm:ss:ff_ format
* Don't use timecode -- timecode is disabled in the resulting files.

**Configuration** field presents the resulting encoding configuration. It is updated when you change the above parameters, but you can type the configuration manually. Contact our support team to get a configuration for the desired results.

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH0BAw4miGfqK8riaz%2Fimage.png?alt=media\&token=90e1c012-dee1-4b0b-a690-c9d2156ed12f)

You can copy the configuration to the clipboard with the top-right button to share it with your teammates or with Livemix support engineers.

Here is how the configuration might look like:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH0X-eidkA5wtQ3C-u%2Fimage.png?alt=media\&token=debcdfb5-7bad-4f8b-8916-041e67994315)

Click the Save Preset button to add the preset to the available Encoding Presets list:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH0lb\_nDG0jNnx6ZQh%2Fimage.png?alt=media\&token=b1701039-98e5-4007-89a1-f7f211406231)

To edit the preset, click the Edit button:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH0utRBtJ9gurr9Fpl%2Fimage.png?alt=media\&token=20074e59-19e1-4de7-9e49-e4616d006b32)

By this, you open the Preset settings menu:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-MXGfIUdqxTo3qjQvRhl%2F-MXH15SPeeg5W0LED0Zx%2Fimage.png?alt=media\&token=8c9c2f2f-d2a2-4209-9e76-1b47ae836d74)

You can change the preset parameters and apply the changes by clicking the Save Preset button. To cancel the changes, click the X button. To remove the preset, click the trash bin button.

Note please that for the Network Streaming type the presets include the streaming protocols as available **Container** options:

![](https://2640386862-files.gitbook.io/\~/files/v0/b/gitbook-legacy-files/o/assets%2F-MWeDSPKGN0gVp2Gooat%2F-Mb1dKgxEM\_leS1EgCqR%2F-Mb1d\_Ft7sOzICu8eQeH%2Fimage.png?alt=media\&token=eb4a329a-a46c-42ac-9e5f-e19f8fb8b967)
