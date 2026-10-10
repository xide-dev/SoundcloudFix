# SoundcloudFix
SoundCloud Fix ( vibecoded sadly )
Basically a port of Soundcloud 8.65.0 with NexaSc to older versions of ios ( lower than 16.4 )

Official soundcloud for versions under 16.4+ from appstore just broke because soundcloud decided to change their backend and because of that - you basically can't login/signup
and you can't fix it because sc decided to upgrade to a newer sdk.
latest in appstore for devices under ios 16.4 - 7.68.1
our port - 8.65.0 + NexaSc ( no ads )

# Added support for iOS 15.0! 
7.68.1 basically had old auth which was deprecated.
we made it work!

[Download IPA 8.65.0 iOS 16.2+](https://github.com/xide-dev/SoundcloudFix/releases/download/Beta/SoundCloud-8.65.0-NexaSC-v3.ipa)
[Download IPA 7.68.1 iOS 15.0+](https://github.com/xide-dev/SoundcloudFix/releases/download/untagged-5fee770eacd3a547e630/SoundCloud_7.68.1_iOS15_Fixed.ipa)


chatgpt explaining here:

## Overview

Recent SoundCloud builds target iOS 16.4 or later. On iOS 16.2, `dyld` can terminate the app before launch when it encounters required SwiftUI symbols introduced after 16.2.

Current status

The v3 experimental build launches successfully on the test setup:

```text
Device: iPhone 14 Pro Max (iPhone15,3)
OS: iOS 16.2 (20C65)
Jailbreak: Dopamine rootless
```

The initial launch-time SwiftUI linker failures were resolved. Sign-in, search, streaming, background playback, and session persistence still need to be tested individually.

Widgets, sharing, uploads, notifications, payments, and other optional extensions are outside the initial core-client acceptance gate.


Disclaimer

This is unofficial compatibility research. SoundCloud and its trademarks belong to their respective owners. Use only software and devices you are authorized to modify and test.
