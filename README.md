lineage-audio-mod
=================

A Magisk module for audio improvements

Features
--------

- Remove Android defualt effects (exclude downmix and volume)
- Add Hi-Res Audio profile to audio policy
- Change volume curve for too loud sound

Tested environment
------------------

- self-built [LineageOS 18.1 GSI](https://github.com/AndyCGYan/lineage_build_unified/tree/lineage-18.1) on Mode1 GRIP

Copyrights
----------

- `audio_effects.xml` or `default_volume_tables.xml`
  - these files are part of LineageOS 18.1
  - these files under the [Apache License 2.0][2]
- `audio_policy_configuration.xml`
  - this file based on [yzyhk904/USB\_SampleRate\_Changer's bypass template xml][1]
  - this file under the [AGPL v3.0][3]
- `update-binary`
  - this file copied from [Magisk Repository][4]

NOTICE
------

Volume curve referenced from [Lowering the minimum volume on Android][5]

Author
------

OKAMURA Naoki aka nyarla <nyarla@kalaclista.com>

[1]: https://github.com/yzyhk904/USB_SampleRate_Changer/blob/main/templates/bypass_offload_template.xml
[2]: https://www.apache.org/licenses/LICENSE-2.0
[3]: https://github.com/yzyhk904/USB_SampleRate_Changer/blob/main/LICENSE
[4]: https://github.com/topjohnwu/Magisk/blob/master/scripts/module_installer.sh
[5]: https://veronneau.org/lowering-the-minimum-volume-on-android.html
