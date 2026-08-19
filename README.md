============================================================
A21S HFP / SCO TARGETED CHECK
============================================================
DATE: Wed 08/19/2026 15:47:11.98

[1] BLUETOOTH PROPERTIES
============================================================
FINDSTR: Cannot open 2>&1

[2] HFP CODEC FILE
============================================================
-rw-r--r-- 1 root root 3499 2009-01-01 03:30 /vendor/etc/aidl/hfp/hfp_codec_capabilities.xml

[3] HFP CODEC CONTENT
============================================================
<?xml version="1.0" encoding="UTF-8"?>
<!---
  This is an example to configure HFP hardware offload supported capability settings
  There are 3 list in this file. Add element into each list as needed.

  pathConfiguration: input / output path configuration
  transportConfiguration: transmit / receive configuration

  configuration:
    For each configuration, there are attributes:
      - name
      - codec
      - useControllerCodec
      - maxLatencyMs
      - packetTypes
      - retransmissionEffort
      - input and output path configuration (reference by name)
      - transmit and receive configuration (reference by name)
-->
<hfpOffloadSetting>

  <pathConfiguration name="CVSD_IO" bandwidth="16000" codec="CVSD" codedDataSize="16" pcmDataFormat="2" pcmPayloadMsbPosition="0" dataPath="1" transportUnitSize="0" />
  <pathConfiguration name="MSBC_IO" bandwidth="32000" codec="MSBC" codedDataSize="16" pcmDataFormat="2" pcmPayloadMsbPosition="0" dataPath="1" transportUnitSize="0" />
  <pathConfiguration name="LC3_IO" bandwidth="64000" codec="MSBC" codedDataSize="16" pcmDataFormat="2" pcmPayloadMsbPosition="0" dataPath="1" transportUnitSize="0" />

  <transportConfiguration name="CVSD_TXRX" bandwidth="8000" codec="CVSD" codedFrameSize="60" />
  <transportConfiguration name="MSBC_TXRX" bandwidth="8000" codec="MSBC" codedFrameSize="60" />
  <transportConfiguration name="LC3_TXRX" bandwidth="8000" codec="LC3" codedFrameSize="60" />

  <configuration name="CVSD_D1_controller" codec="CVSD" maxLatencyMs="65535" packetTypes="7" retransmissionEffort="0" useControllerCodec="true" inputPathConfiguration="CVSD_IO" outputPathConfiguration="CVSD_IO" inputTransportConfiguration="CVSD_TXRX" outTransportConfiguration="CVSD_TXRX" />
  <configuration name="CVSD_S3_controller" codec="CVSD" maxLatencyMs="10" packetTypes="959" retransmissionEffort="1" useControllerCodec="true" inputPathConfiguration="CVSD_IO" outputPathConfiguration="CVSD_IO" inputTransportConfiguration="CVSD_TXRX" outTransportConfiguration="CVSD_TXRX" />
  <configuration name="CVSD_S4_controller" codec="CVSD" maxLatencyMs="12" packetTypes="959" retransmissionEffort="2" useControllerCodec="true" inputPathConfiguration="CVSD_IO" outputPathConfiguration="CVSD_IO" inputTransportConfiguration="CVSD_TXRX" outTransportConfiguration="CVSD_TXRX" />

  <configuration name="MSBC_T1_controller" codec="MSBC" maxLatencyMs="8" packetTypes="968" retransmissionEffort="2" useControllerCodec="true" inputPathConfiguration="MSBC_IO" outputPathConfiguration="MSBC_IO" inputTransportConfiguration="MSBC_TXRX" outTransportConfiguration="MSBC_TXRX" />
  <configuration name="MSBC_T2_controller" codec="MSBC" maxLatencyMs="13" packetTypes="904" retransmissionEffort="2" useControllerCodec="true" inputPathConfiguration="MSBC_IO" outputPathConfiguration="MSBC_IO" inputTransportConfiguration="MSBC_TXRX" outTransportConfiguration="MSBC_TXRX" />

  <configuration name="LC3_T1_controller" codec="LC3" maxLatencyMs="8" packetTypes="968" retransmissionEffort="2" useControllerCodec="true" inputPathConfiguration="LC3_IO" outputPathConfiguration="LC3_IO" inputTransportConfiguration="LC3_TXRX" outTransportConfiguration="LC3_TXRX" />
  <configuration name="LC3_T2_controller" codec="LC3" maxLatencyMs="13" packetTypes="896" retransmissionEffort="2" useControllerCodec="true" inputPathConfiguration="LC3_IO" outputPathConfiguration="LC3_IO" inputTransportConfiguration="LC3_TXRX" outTransportConfiguration="LC3_TXRX" />

</hfpOffloadSetting>

[4] BLUETOOTH VENDOR CONFIG
============================================================
#############################################################################
#
# Copyright (c) 2012 - 2014 Samsung Electronics Co., Ltd
#
#############################################################################
# Configuration of which bus to use for handling digital audio data. Valid values are PCM or I2S
audioBusConfig=I2S

# Configuration of H4 device path
h4_file=/dev/scsc_h4_0

# Platform codec configuration: 1 route audio between ear-jack and BT for eSCO
audio_sco_jack=1
[5] BLUETOOTH AUDIO POLICY
============================================================
<?xml version="1.0" encoding="UTF-8"?>
<!-- Bluetooth Audio HAL Audio Policy Configuration file -->
<module name="bluetooth" halVersion="2.0">
    <mixPorts>
        <!-- A2DP Audio Ports -->
        <mixPort name="a2dp output" role="source"/>
        <!-- Hearing AIDs Audio Ports -->
        <mixPort name="hearing aid output" role="source">
            <profile name="" format="AUDIO_FORMAT_PCM_16_BIT"
                     samplingRates="24000,16000"
                     channelMasks="AUDIO_CHANNEL_OUT_STEREO"/>
        </mixPort>
    </mixPorts>
    <devicePorts>
        <!-- A2DP Audio Ports -->
        <devicePort tagName="BT A2DP Out" type="AUDIO_DEVICE_OUT_BLUETOOTH_A2DP" role="sink">
            <profile name="" format="AUDIO_FORMAT_PCM_16_BIT"
                     samplingRates="44100,48000,88200,96000"
                     channelMasks="AUDIO_CHANNEL_OUT_STEREO"/>
        </devicePort>
        <devicePort tagName="BT A2DP Headphones" type="AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_HEADPHONES" role="sink">
            <profile name="" format="AUDIO_FORMAT_PCM_16_BIT"
                     samplingRates="44100,48000,88200,96000"
                     channelMasks="AUDIO_CHANNEL_OUT_STEREO"/>
        </devicePort>
        <devicePort tagName="BT A2DP Speaker" type="AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_SPEAKER" role="sink">
            <profile name="" format="AUDIO_FORMAT_PCM_16_BIT"
                     samplingRates="44100,48000,88200,96000"
                     channelMasks="AUDIO_CHANNEL_OUT_STEREO"/>
        </devicePort>
        <!-- Hearing AIDs Audio Ports -->
        <devicePort tagName="BT Hearing Aid Out" type="AUDIO_DEVICE_OUT_HEARING_AID" role="sink"/>
    </devicePorts>
    <routes>
        <route type="mix" sink="BT A2DP Out"
               sources="a2dp output"/>
        <route type="mix" sink="BT A2DP Headphones"
               sources="a2dp output"/>
        <route type="mix" sink="BT A2DP Speaker"
               sources="a2dp output"/>
        <route type="mix" sink="BT Hearing Aid Out"
               sources="hearing aid output"/>
    </routes>
</module>

[6] AUDIO POLICY SCO REFERENCES
============================================================

[7] HFP / SCO PROCESSES
============================================================
root            15     2          0      0 rescuer_thread      0 I [sec_audio_dbg_s]
audioserver   4824     1      60192   5164 binder_ioctl_write_read 0 S android.hardware.audio.service
bluetooth     4832     1   10875624   2212 binder_ioctl_write_read 0 S android.hardware.bluetooth@1.0-service
audioserver   4876     1   11431596  11184 binder_ioctl_write_read 0 S audioserver
u0_a156       6232  4803   14604920  39032 ep_poll             0 S org.lineageos.audiofx
bluetooth    14508  4803   15527412  71360 ep_poll             0 S com.android.bluetooth

[8] AUDIO DEVICES
============================================================
Events log: audio services lifecycle
08-19 14:48:57:145 AudioService()

Message handler (watch for unhandled messages):
  Handler (com.android.server.audio.AudioService$AudioHandler) {cfca9ec} @ 3516547
    Looper (AudioService, tid 130) {cf69088}
      (MessageQueue is using Legacy implementation)
      (Total messages: 0, polling=true, quitting=false)

Fun with Flags:
	com.android.media.audio.as_device_connection_failure:false
	android.media.audio.autoPublicVolumeApiHardening:false
	android.media.audio.automaticBtDeviceType:true
	android.media.audio.featureSpatialAudioHeadtrackingLowLatency:false
	android.media.audio.focusFreezeTestApi:true
	com.android.media.audio.audioserverPermissions:false
	com.android.media.audio.disablePrescaleAbsoluteVolume:true
	com.android.media.audio.setStreamVolumeOrder:true
	android.media.audio.roForegroundAudioControl:true
	android.media.audio.scoManagedByAudio:false
	com.android.media.audio.vgsVssSyncMuteOrder:true
	com.android.media.audio.absVolumeIndexFix:true
	com.android.media.audio.replaceStreamBtSco:true
	com.android.media.audio.equalScoLeaVcIndexRange:false
Events log: Hardening enforcement

MediaFocusControl dump time: 15:47:04

Audio Focus stack entries (last is top of stack):


No external focus policy



 Notify on duck:  true

 In ring or call: false



Events log: focus commands as seen by MediaFocusControl
08-19 14:49:25:201 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:49:30:922 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:49:33:346 abandonAudioFocus() from uid/pid 1000/5094 clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom
08-19 14:51:20:407 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:51:34:347 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:51:38:962 abandonAudioFocus() from uid/pid 1000/5094 clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom
08-19 14:52:03:213 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:52:14:262 requestAudioFocus() from uid/pid 1000/5094 AA=USAGE_VOICE_COMMUNICATION/CONTENT_TYPE_SPEECH clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom req=2 flags=0x4 sdk=0
08-19 14:52:15:864 abandonAudioFocus() from uid/pid 1000/5094 clientId=AudioFocus_For_Phone_Ring_And_Calls callingPack=com.android.server.telecom
Multi Audio Focus enabled :false

Stream volumes (device: index)
- STREAM_VOICE_CALL:
   Muted: false
   Muted Internally: false
   Min: 1
   Max: 15
   streamVolume:15
   Current: 1 (earpiece): 15, 2 (speaker): 15, 10 (bt_sco): 5, 20 (bt_sco_hs): 15, 40 (bt_sco_carkit): 8, 80 (bt_a2dp): 15, 40000000 (default): 5
   Devices: bt_a2dp(80)
   Volume Group: voice_call

- STREAM_SYSTEM (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: bt_a2dp(80)
   Volume Group: system

- STREAM_RING:
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: speaker(2), bt_a2dp(80)
   Volume Group: ring

- STREAM_MUSIC:
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 25
   streamVolume:16
   Current: 1 (earpiece): 25, 2 (speaker): 22, 20 (bt_sco_hs): 20, 80 (bt_a2dp): 16, 100 (bt_a2dp_hp): 3, 4000000 (usb_headset): 6, 20000000 (ble_headset): 3, 20000002 (ble_broadcast): 3, 40000000 (default): 8
   Devices: bt_a2dp(80)
   Volume Group: music

- STREAM_ALARM:
   Muted: false
   Muted Internally: false
   Min: 1 w/o perm:3
   Max: 7
   streamVolume:4
   Current: 1 (earpiece): 6, 2 (speaker): 4, 80 (bt_a2dp): 6, 40000000 (default): 6
   Devices: speaker(2), bt_a2dp(80)
   Volume Group: alarm

- STREAM_NOTIFICATION:
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 5, 80 (bt_a2dp): 4, 40000000 (default): 5
   Devices: bt_a2dp(80)
   Volume Group: notification

- STREAM_SYSTEM_ENFORCED (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 7
   streamVolume:0
   Current: 1 (earpiece): 5, 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: bt_a2dp(80)
   Volume Group: enforced_audible

- STREAM_DTMF (aliased to: STREAM_RING):
   Muted: true
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:0
   Current: 1 (earpiece): 11, 2 (speaker): 11, 10 (bt_sco): 11, 20 (bt_sco_hs): 11, 40 (bt_sco_carkit): 11, 80 (bt_a2dp): 11, 40000000 (default): 11
   Devices: bt_a2dp(80)
   Volume Group: dtmf

- STREAM_TTS (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:2
   Current: 1 (earpiece): 15, 2 (speaker): 2, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 5
   Devices: speaker(2)
   Volume Group: tts

- STREAM_ACCESSIBILITY (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 1
   Max: 15
   streamVolume:10
   Current: 1 (earpiece): 15, 2 (speaker): 13, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 6
   Devices: bt_a2dp(80)
   Volume Group: accessibility

- STREAM_ASSISTANT (aliased to: STREAM_MUSIC):
   Muted: false
   Muted Internally: false
   Min: 0
   Max: 15
   streamVolume:10
   Current: 1 (earpiece): 15, 2 (speaker): 13, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 5
   Devices: bt_a2dp(80)
   Volume Group: assistant


- mute affected streams = 0x6f

- user mutable streams = 0x2e

Volume Groups (device: index)
- VOLUME GROUP voice_call:
   Muted: false
   Min: 1
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 15, 10 (bt_sco): 5, 20 (bt_sco_hs): 15, 40 (bt_sco_carkit): 8, 80 (bt_a2dp): 15, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_VOICE_CALL 
- VOLUME GROUP system:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_SYSTEM 
- VOLUME GROUP ring:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_RING 
- VOLUME GROUP music:
   Muted: false
   Min: 0
   Max: 25
   Current: 1 (earpiece): 25, 2 (speaker): 22, 20 (bt_sco_hs): 20, 80 (bt_a2dp): 16, 100 (bt_a2dp_hp): 3, 4000000 (usb_headset): 6, 20000000 (ble_headset): 3, 20000002 (ble_broadcast): 3, 40000000 (default): 8
   Devices: bt_a2dp
   Streams: STREAM_MUSIC 
- VOLUME GROUP alarm:
   Muted: false
   Min: 1
   Max: 7
   Current: 2 (speaker): 4, 40000000 (default): 6
   Devices: speaker
   Streams: STREAM_ALARM 
- VOLUME GROUP notification:
   Muted: true
   Min: 0
   Max: 7
   Current: 2 (speaker): 5, 80 (bt_a2dp): 4, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_NOTIFICATION 
- VOLUME GROUP voice_call:
   Muted: false
   Min: 1
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 15, 10 (bt_sco): 5, 20 (bt_sco_hs): 15, 40 (bt_sco_carkit): 8, 80 (bt_a2dp): 15, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_VOICE_CALL 
- VOLUME GROUP enforced_audible:
   Muted: false
   Min: 0
   Max: 7
   Current: 2 (speaker): 5, 20 (bt_sco_hs): 5, 80 (bt_a2dp): 5, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_SYSTEM_ENFORCED 
- VOLUME GROUP dtmf:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 11, 20 (bt_sco_hs): 15, 40 (bt_sco_carkit): 8, 80 (bt_a2dp): 15, 40000000 (default): 11
   Devices: bt_a2dp
   Streams: STREAM_DTMF 
- VOLUME GROUP tts:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 2, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 5
   Devices: speaker
   Streams: STREAM_TTS 
- VOLUME GROUP accessibility:
   Muted: false
   Min: 1
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 13, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 6
   Devices: bt_a2dp
   Streams: STREAM_ACCESSIBILITY 
- VOLUME GROUP assistant:
   Muted: false
   Min: 0
   Max: 15
   Current: 1 (earpiece): 15, 2 (speaker): 13, 20 (bt_sco_hs): 12, 80 (bt_a2dp): 10, 100 (bt_a2dp_hp): 2, 4000000 (usb_headset): 4, 20000000 (ble_headset): 2, 20000002 (ble_broadcast): 2, 40000000 (default): 5
   Devices: bt_a2dp
   Streams: STREAM_ASSISTANT 
- VOLUME GROUP AUDIO_STREAM_REROUTING:
   Muted: false
   Min: 0
   Max: 25
   Current: 40000000 (default): 8
   Devices: bt_a2dp
   Streams: UNKNOWN_STREAM_12 
- VOLUME GROUP AUDIO_STREAM_PATCH:
   Muted: false
   Min: 0
   Max: 25
   Current: 40000000 (default): 8
   Devices: bt_a2dp
   Streams: UNKNOWN_STREAM_13 

Ringer mode: 
- mode (internal) = VIBRATE
- mode (external) = VIBRATE
- zen mode:ZEN_MODE_OFF
- ringer mode affected streams = 0x1a6 (STREAM_SYSTEM,STREAM_RING,STREAM_NOTIFICATION,STREAM_SYSTEM_ENFORCED,STREAM_DTMF)
- ringer mode muted streams = 0x1a6 (STREAM_SYSTEM,STREAM_RING,STREAM_NOTIFICATION,STREAM_SYSTEM_ENFORCED,STREAM_DTMF)
- delegate = ZenModeHelper

Audio mode: 
- Requested mode = MODE_NORMAL
- Actual mode = MODE_NORMAL
- Mode owner: 
   None
- Mode owner stack: 
   Empty

Audio routes:
  mMainType=0x0
  mBluetoothName=CMF Buds 2a

Other state:
  mUseVolumeGroupAliases=false
  mVolumeController=VolumeController(android.os.BinderProxy@be271b5,mVisible=false)
  mEnableCsd=false
  mSafeMediaVolumeState=SAFE_MEDIA_VOLUME_ACTIVE
  mSafeMediaVolumeIndex=100
  mSafeMediaVolumeIndex[4]=100
  mSafeMediaVolumeIndex[8]=100
  mSafeMediaVolumeIndex[128]=-1
  mSafeMediaVolumeIndex[256]=-1
  mSafeMediaVolumeIndex[67108864]=60
  mSafeMediaVolumeIndex[536870912]=-1
  mSafeMediaVolumeIndex[536870914]=-1
  mSafeMediaVolumeDbfs=-37.0
  mMusicActiveMs=0
  mMcc=432
  mPendingVolumeCommand=null

Events log: CSD updates

  sIndependentA11yVolume=false
  mCameraSoundForced=false
  mHasVibrator=true
  mVolumePolicy=VolumePolicy[volumeDownToEnterSilent=false,volumeUpToExitSilent=false,doNotDisturbWhenSilent=false,vibrateToSilentDebounce=400]
  mAvrcpAbsVolSupported=true
  mBtScoOnByApp=false
  mIsSingleVolume=false
  mUseFixedVolume=false
  mNotifAliasRing=false
  mFixedVolumeDevices=0x200000
  mFullVolumeDevices=0x40000,0x40001
  absolute volume devices=
  adjust-only absolute volume devices=
  pre-scale for bluetooth absolute volume = disabled
  mExtVolumeController=null
  mHdmiAudioSystemClient=null
  mHdmiPlaybackClient=null
  mHdmiTvClient=null
  mHdmiSystemAudioSupported=false
  mHdmiCecVolumeControlEnabled=false
  mIsCallScreeningModeSupported=false
  mic mute FromSwitch=false FromRestrictions=false FromApi=false from system=false
  mMasterMute=false
  No accessibility service Uids.
  Assistant service UIDs:
  - 10205
  supportsBluetoothVariableLatency=false
  isBluetoothVariableLatencyEnabled=true

Audio policies:
android.media.audiopolicy.AudioPolicyConfig:
0 AudioMix, reg:32:ap:0
 Uid Device Affinities:
 UserId Device Affinities:
 Proxy:
   is focus policy= false
   media projection= null

Events log: dynamic policy events (logged when command received by AudioService)
08-19 14:48:58:142 registerAudioPolicy for android.media.audiopolicy.AudioPolicy$1@8905e94 u/pid:1000/5094 with config:reg:32:ap:0

PlaybackActivityMonitor dump time: 15:47:04

  playback listeners:
 PlayMonitorClient:S uid:1000 pid:5094
 PlayMonitorClient:S uid:1000 pid:5094
 PlayMonitorClient:S uid:1002 pid:14508



  players:
(not logged)  AudioPlaybackConfiguration piid:143 deviceId:0 type:android.media.SoundPool u/pid:1000/5094 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}
  AudioPlaybackConfiguration piid:151 deviceId:0 type:android.media.SoundPool u/pid:10154/5343 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}

  ducked players piids:

  faded out players piids:

  muted player piids due to call/ring:

  banned uids:


  muted players (piids) awaiting device connection:


  current piid to portId map:


Events log: playback activity as reported through PlayerBase
08-19 14:48:59:432 new player piid:143 uid/pid:1000/5094 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
08-19 14:49:01:883 new player piid:151 uid/pid:10154/5343 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null session:0
08-19 14:49:17:444 new player piid:159 uid/pid:10189/6406 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null session:0
08-19 14:49:24:667 releasing player piid:159, uid:0
08-19 14:49:30:950 new player piid:167 uid/pid:1000/5094 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:209
08-19 14:49:30:950 player piid:167 new AudioAttributes:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null
08-19 14:49:31:360 player piid:167 event:started
08-19 14:49:31:678 port updated portId:25 mapped to player piid:167
08-19 14:49:31:797 player piid:167 format update:FormatInfo{isSpatialized=false, channelMask=0x3, sampleRate=48000}
08-19 14:49:31:813 player piid:167 event:device updated deviceId:2
08-19 14:49:32:758 player piid:167 event:stopped
08-19 14:49:32:760 releasing player piid:167, uid:1000
08-19 14:49:37:713 new player piid:175 uid/pid:10189/8456 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null session:0
08-19 14:50:07:653 releasing player piid:175, uid:0
08-19 14:50:23:826 new player piid:183 uid/pid:10229/11803 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:273
08-19 14:50:23:827 player piid:183 new AudioAttributes:AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_MUSIC flags=0x800 tags= bundle=null
08-19 14:51:20:528 call: muting piid:183 uid:10229
08-19 14:51:26:051 new player piid:191 uid/pid:10189/13392 type:android.media.SoundPool attr:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null session:0
08-19 14:51:38:969 call: unmuting piid:183
08-19 14:52:03:315 call: muting piid:183 uid:10229
08-19 14:52:14:270 new player piid:199 uid/pid:1000/5094 type:android.media.MediaPlayer attr:AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null session:417
08-19 14:52:14:271 player piid:199 new AudioAttributes:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null
08-19 14:52:14:457 player piid:199 event:started
08-19 14:52:14:577 port updated portId:45 mapped to player piid:199
08-19 14:52:14:665 player piid:199 format update:FormatInfo{isSpatialized=false, channelMask=0x3, sampleRate=48000}
08-19 14:52:14:692 player piid:199 event:device updated deviceId:2
08-19 14:52:15:572 player piid:199 event:stopped
08-19 14:52:15:574 releasing player piid:199, uid:1000
08-19 14:52:15:865 call: unmuting piid:183
08-19 14:59:16:443 releasing player piid:183, uid:0
08-19 15:00:45:915 releasing player piid:191, uid:0

  allowed capture policies:

RecordActivityMonitor dump time: 15:47:04


Events log: recording activity received by AudioService

AudioDeviceBroker:
  Message handler (watch for unhandled messages):
    Handler (com.android.server.audio.AudioDeviceBroker$BrokerHandler) {50dc04a} @ 3516557
      Looper (AudioDeviceBroker, tid 127) {c8e2f4d}
        (MessageQueue is using Legacy implementation)
        (Total messages: 0, polling=true, quitting=false)

  BECOMING_NOISY_INTENT_DEVICES_SET=
 0x400 0x800 0x8000000 0x20000000 0x80 0x100 0x200 0x2000 0x4000 0x4000000 0x20000001 0x20000 0x20000002 0x4 0x8
  Preferred devices for strategy:

  Non-default devices for strategy:

  Connected devices:
    [DeviceInfo: type:0x80 (bt_a2dp) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 4000000 group:-1 peer addr: peer identity addr: disabled modes: {}]
    [DeviceInfo: type:0x20 (bt_sco_hs) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 0 group:-1 peer addr: peer identity addr: disabled modes: {}]
    [DeviceInfo: type:0x80000008 (bt_sco_hs) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 0 group:-1 peer addr: peer identity addr: disabled modes: {}]

  APM Connected device (A2DP sink only):
     type:0x80 (bt_a2dp) addr:0x80:3C:B0:ED:D9:F5:5E

  Preferred devices for capture preset:

  Applied devices roles for strategies (from API):

  Applied devices roles for strategies (internal):

  Applied devices roles for presets (from API):

  Applied devices roles for presets (internal:

devices:

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:68:CC bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x20 addr: XX:XX:XX:XX:68:CC bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:87:7F bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x40 addr: XX:XX:XX:XX:87:7F bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:4F:9F bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x20 addr: XX:XX:XX:XX:4F:9F bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:46:78 bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x20 addr: XX:XX:XX:XX:46:78 bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 8 internal type: 0x80 addr: XX:XX:XX:XX:10:8A bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false

	type: 7 internal type: 0x20 addr: XX:XX:XX:XX:10:8A bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false


  Communication route clients:

  Computed Preferred communication device: null

  Applied Preferred communication device: null
  Active communication device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[]
  mCommunicationStrategyId: 1015
  mAccessibilityStrategyId: 1018

  mAudioModeOwner: AudioModeInfo: mMode=MODE_NORMAL, mPid=0, mUid=0

  mScoManagedByAudio: false

  mBluetoothHeadset: android.bluetooth.BluetoothHeadset@29098b
  mBluetoothHeadsetDevice: XX:XX:XX:XX:F5:5E
  mBluetoothHeadsetDevice.DeviceClass: AUDIO_VIDEO_WEARABLE_HEADSET
  mScoAudioState: SCO_STATE_INACTIVE
  mScoAudioMode: SCO_MODE_VIRTUAL_CALL

  mHearingAid: android.bluetooth.BluetoothHearingAid@fe8fb26

  mLeAudio: null
  mA2dp: android.bluetooth.BluetoothA2dp@ee39a68
  mAvrcpAbsVolSupported: true

SoundEffects:
  Message handler (watch for unhandled messages):
  Handler (com.android.server.audio.SoundEffectsHelper$SfxHandler) {aad9bbb} @ 3516562
    Looper (AS.SfxWorker, tid 129) {f0078d8}
      (MessageQueue is using Legacy implementation)
      (Total messages: 0, polling=true, quitting=false)
  Default attenuation (dB): -6
Events log: Sound Effects Loading
08-19 14:48:59:430 effects loading started
08-19 14:49:00:060 effect Effect_Tick.ogg loaded
08-19 14:49:00:077 effect KeypressStandard.ogg loaded
08-19 14:49:00:155 effect KeypressSpacebar.ogg loaded
08-19 14:49:00:214 effect KeypressDelete.ogg loaded
08-19 14:49:00:247 effect KeypressReturn.ogg loaded
08-19 14:49:00:352 effect KeypressInvalid.ogg loaded
08-19 14:49:00:353 effects loading completed



Event logs:
Events log: phone state (logged after successful call to AudioSystem.setPhoneState(int, int))
08-19 14:49:25:686 setMode(MODE_IN_CALL) from package=com.android.server.telecom pid=5094 selected mode=MODE_IN_CALL by pid=5094
08-19 14:49:33:101 setMode(MODE_NORMAL) from package=com.android.server.telecom pid=5094 selected mode=MODE_NORMAL by pid=0
08-19 14:51:21:004 setMode(MODE_IN_CALL) from package=com.android.server.telecom pid=5094 selected mode=MODE_IN_CALL by pid=5094
08-19 14:51:38:851 setMode(MODE_NORMAL) from package=com.android.server.telecom pid=5094 selected mode=MODE_NORMAL by pid=0
08-19 14:52:03:654 setMode(MODE_IN_CALL) from package=com.android.server.telecom pid=5094 selected mode=MODE_IN_CALL by pid=5094
08-19 14:52:15:840 setMode(MODE_NORMAL) from package=com.android.server.telecom pid=5094 selected mode=MODE_NORMAL by pid=0


Events log: wired/A2DP/hearing aid device connection
08-19 14:51:37:304 BluetoothActiveDeviceChanged for A2DP, device update null -> XX:XX:XX:XX:F5:5E
08-19 14:51:37:309 BluetoothActiveDeviceChanged for A2DP, device update XX:XX:XX:XX:F5:5E -> XX:XX:XX:XX:F5:5E
08-19 14:51:37:310 msg: MSG_L_BT_ACTIVE_DEVICE_CHANGE_EXT BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0
08-19 14:51:37:519 SCO sink device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:51:37:649 SCO source device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:51:37:653 BT connected:BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0 codec=AUDIO_FORMAT_AAC
08-19 14:51:38:022 A2DP sink device addr=XX:XX:XX:XX:F5:5E now available
08-19 14:51:38:036 onBluetoothDeviceConfigChange addr=3C:B0:ED:D9:F5:5E event=DEVICE_CONFIG_CHANGE
08-19 14:51:38:044 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false
08-19 14:51:38:046 setCommunicationRouteForClient for uid: 1000 device: null isPrivileged: true from API: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:51:38:050 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:51:38:512 removePreferredDevicesForStrategy strat:1020
08-19 14:51:38:884 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false
08-19 14:51:38:954 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
08-19 14:52:03:699 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
08-19 14:52:04:654 BT profile service: disconnecting HEADSET profile
08-19 14:52:04:654 BT profile HEADSET disconnected
08-19 14:52:04:654 BT profile service: disconnecting A2DP profile
08-19 14:52:04:698 BT profile service: disconnecting HEARING_AID profile
08-19 14:52:04:796 SCO sink device addr=3C:B0:ED:D9:F5:5E made unavailable
08-19 14:52:04:947 SCO source device addr=3C:B0:ED:D9:F5:5E made unavailable
08-19 14:52:04:962 BT profile A2DP disconnected
08-19 14:52:04:967 BT profile HEARING_AID disconnected
08-19 14:52:04:968 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: setCommunicationDevice() from u/pid:1000/5094
08-19 14:52:04:969 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: setCommunicationDevice() from u/pid:1000/5094
08-19 14:52:05:286 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: resetBluetoothSco
08-19 14:52:05:286 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: resetBluetoothSco
08-19 14:52:05:287 broadcast ACTION_AUDIO_BECOMING_NOISY
08-19 14:52:05:973 BT profile service: connecting HEADSET profile
08-19 14:52:05:974 BT profile service: connecting A2DP profile
08-19 14:52:05:977 BT profile service: connecting HEARING_AID profile
08-19 14:52:06:083 A2DP device addr=XX:XX:XX:XX:F5:5E made unavailable
08-19 14:52:06:156 BT profile HEADSET connected to proxy android.bluetooth.BluetoothHeadset@29098b
08-19 14:52:06:177 BT profile A2DP connected to proxy android.bluetooth.BluetoothA2dp@ee39a68
08-19 14:52:06:222 BT profile HEARING_AID connected to proxy android.bluetooth.BluetoothHearingAid@fe8fb26
08-19 14:52:15:863 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: setNewModeOwner
08-19 14:52:15:863 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: setNewModeOwner
08-19 14:52:15:866 setCommunicationRouteForClient for uid: 1000 device: null isPrivileged: true from API: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:52:15:866 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:52:29:781 BluetoothActiveDeviceChanged for A2DP, device update null -> XX:XX:XX:XX:F5:5E
08-19 14:52:29:785 msg: MSG_L_BT_ACTIVE_DEVICE_CHANGE_EXT BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0
08-19 14:52:29:785 BluetoothActiveDeviceChanged for A2DP, device update XX:XX:XX:XX:F5:5E -> XX:XX:XX:XX:F5:5E
08-19 14:52:29:799 BT connected:BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0 codec=AUDIO_FORMAT_AAC
08-19 14:52:30:247 A2DP sink device addr=XX:XX:XX:XX:F5:5E now available
08-19 14:52:30:265 onBluetoothDeviceConfigChange addr=3C:B0:ED:D9:F5:5E event=DEVICE_CONFIG_CHANGE
08-19 14:52:30:273 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false
08-19 14:52:30:346 removePreferredDevicesForStrategy strat:1020
08-19 14:52:34:318 SCO sink device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:52:34:357 SCO source device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:52:34:367 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false


Events log: force use (logged before setForceUse() is executed)
08-19 14:49:34:069 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:34:071 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:54:476 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094 src:onSetBtActiveDevice
08-19 14:51:21:513 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:21:612 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:22:906 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:22:914 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:37:659 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094 src:onSetBtActiveDevice
08-19 14:51:38:511 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:39:114 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:51:39:154 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:04:171 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:04:269 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:05:286 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:05:287 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:16:006 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:16:054 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:16:055 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:52:16:076 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094
08-19 14:52:29:801 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094 src:onSetBtActiveDevice


Events log: volume changes (logged when command received by AudioService)
08-19 14:49:04:749 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, muted)
08-19 14:49:04:757 onSetBtActiveDevice dev:0x80 volIdx:120
08-19 14:49:04:975 setStreamVolume(stream:STREAM_MUSIC index:16 flags:0x41 oldIndex:12) from com.android.bluetooth
08-19 14:49:04:985 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:49:04:985 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:49:05:034 sending VOLUME_CHANGED stream:STREAM_MUSIC index:16 (was:12) aliased streams: STREAM_ASSISTANT:10 STREAM_ACCESSIBILITY:10 STREAM_TTS:10 
08-19 14:49:05:089 setStreamVolume(stream:STREAM_MUSIC index:16 flags:0x40 oldIndex:16) from com.android.bluetooth
08-19 14:49:05:116 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, unmuted)
08-19 14:49:06:793 sending VOLUME_CHANGED stream:STREAM_MUSIC index:3 (was:16) aliased streams: STREAM_ASSISTANT:2 STREAM_ACCESSIBILITY:2 STREAM_TTS:2 
08-19 14:49:54:470 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, muted)
08-19 14:49:54:479 onSetBtActiveDevice dev:0x80 volIdx:160
08-19 14:49:54:908 setStreamVolume(stream:STREAM_MUSIC index:16 flags:0x40 oldIndex:16) from com.android.bluetooth
08-19 14:49:55:021 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:49:55:022 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:49:55:063 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, unmuted)
08-19 14:51:37:309 setStreamVolume(stream:STREAM_VOICE_CALL index:15 flags:0x0 oldIndex:10) from com.android.bluetooth
08-19 14:51:37:319 sending VOLUME_CHANGED stream:STREAM_VOICE_CALL index:15 (was:10) aliased streams: STREAM_DTMF:15 
08-19 14:51:37:336 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, muted)
08-19 14:51:37:660 onSetBtActiveDevice dev:0x80 volIdx:160
08-19 14:51:38:516 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:51:38:516 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:51:38:856 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:51:38:856 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:51:38:952 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, unmuted)
08-19 14:52:29:797 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, muted)
08-19 14:52:29:800 onSetBtActiveDevice dev:0x80 volIdx:160
08-19 14:52:30:265 setStreamVolume(stream:STREAM_MUSIC index:16 flags:0x40 oldIndex:16) from com.android.bluetooth
08-19 14:52:30:284 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:52:30:286 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:52:30:290 setDeviceVolumeBehavior: dev:bt_a2dp addr:XX:XX:XX:XX:F5:5E behavior:DEVICE_VOLUME_BEHAVIOR_ABSOLUTE pack:com.android.bluetooth
08-19 14:52:30:291 avrcpSupportsAbsoluteVolume addr=XX:XX:XX:XX:F5:5E support=true
08-19 14:52:30:402 VolumeStreamState.muteInternally(stream:STREAM_MUSIC, unmuted)


Events log: mute commands
08-19 14:48:57:431 RingerZenMutedStreams 0x0 from onInitStreamsAndVolumes
08-19 14:48:57:432 RingerZenMutedStreams 0x100 from muteRingerModeStreams
08-19 14:48:57:432 STREAM_DTMF muting by muteRingerModeStreams
08-19 14:48:57:432 RingerZenMutedStreams 0x180 from muteRingerModeStreams
08-19 14:48:57:432 STREAM_SYSTEM_ENFORCED muting by muteRingerModeStreams
08-19 14:48:57:433 RingerZenMutedStreams 0x1a0 from muteRingerModeStreams
08-19 14:48:57:433 STREAM_NOTIFICATION muting by muteRingerModeStreams
08-19 14:48:57:435 RingerZenMutedStreams 0x1a4 from muteRingerModeStreams
08-19 14:48:57:435 STREAM_RING muting by muteRingerModeStreams
08-19 14:48:57:438 RingerZenMutedStreams 0x1a6 from muteRingerModeStreams
08-19 14:48:57:438 STREAM_SYSTEM muting by muteRingerModeStreams
08-19 14:49:25:858 RingerZenMutedStreams 0xa6 from muteRingerModeStreams
08-19 14:49:25:890 STREAM_DTMF unmuting by muteRingerModeStreams
08-19 14:49:33:267 RingerZenMutedStreams 0x1a6 from muteRingerModeStreams
08-19 14:49:33:267 STREAM_DTMF muting by muteRingerModeStreams
08-19 14:51:21:051 RingerZenMutedStreams 0xa6 from muteRingerModeStreams
08-19 14:51:21:051 STREAM_DTMF unmuting by muteRingerModeStreams
08-19 14:51:38:878 RingerZenMutedStreams 0x1a6 from muteRingerModeStreams
08-19 14:51:38:878 STREAM_DTMF muting by muteRingerModeStreams
08-19 14:52:03:691 RingerZenMutedStreams 0xa6 from muteRingerModeStreams
08-19 14:52:03:691 STREAM_DTMF unmuting by muteRingerModeStreams
08-19 14:52:15:858 RingerZenMutedStreams 0x1a6 from muteRingerModeStreams
08-19 14:52:15:858 STREAM_DTMF muting by muteRingerModeStreams


Supported System Usages:
	USAGE_CALL_ASSISTANT



Spatial audio:
mHasSpatializerEffect:false (effect present)
isSpatializerEnabled:false (routing dependent)
SpatializerHelper:
	mState:1
	mSpatLevel:0
	mCapableSpatLevel:0
	mIsHeadTrackingSupported:false
	supported head tracking modes:
	mDesiredHeadTrackingMode:HEAD_TRACKING_MODE_RELATIVE_WORLD
	mActualHeadTrackingMode:HEAD_TRACKING_MODE_UNSUPPORTED
	headtracker available:false
	supports binaural:false / transaural:false
	mSpatOutput:0
	has FEATURE_AUDIO_SPATIAL_HEADTRACKING_LOW_LATENCY:false
Events log: spatial audio
08-19 14:48:57:466 init effectExpected=false
08-19 14:48:57:466 init(): setting state to STATE_NOT_SUPPORTED due to effect not expected
08-19 14:48:57:466 setFeatureEnabled(false) was featureEnabled:false
08-19 14:49:05:007 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_sco addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:49:10:605 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:49:54:965 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_sco addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:49:58:317 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:51:38:888 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:51:38:962 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_sco addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:52:30:280 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_sco addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
08-19 14:52:34:371 removeCompatibleAudioDevice: dev=AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]



Loudness alignment:

Registered clients:


Events log: Loudness updates
08-19 14:49:16:597 Loudness client with pid 6344 died
08-19 14:49:22:930 Loudness client with pid 6386 died
08-19 14:49:26:876 Loudness client with pid 6369 died
08-19 14:49:54:939 Loudness client with pid 8398 died
08-19 14:50:06:675 Loudness client with pid 8402 died
08-19 14:50:10:332 Loudness client with pid 8404 died
08-19 14:59:16:033 Loudness client with pid 13384 died
08-19 14:59:16:330 Loudness client with pid 12941 died


Absolute voume devices:
Device type: 0x80, driving stream 3
Device type: 0x8000000, driving stream 3
Device type: 0x20000000, driving stream 3
Device type: 0x20000001, driving stream 3
Device type: 0x20000002, driving stream 3

AudioSystemAdapter:
 last cache clear time: 08-19 14:52:34:318
 mDevicesForAttrCache:
	AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x801 tags= bundle=null forVolume: true stream: STREAM_SYSTEM(1)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANCE_ACCESSIBILITY content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ACCESSIBILITY(10)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION_RINGTONE content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_RING(2)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ALARM content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ALARM(4)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_ASSISTANT content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null forVolume: true stream: STREAM_ASSISTANT(11)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_NOTIFICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_NOTIFICATION(5)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_VOICE_CALL(0)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_VOICE_COMMUNICATION_SIGNALLING content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_DTMF(8)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_UNKNOWN flags=0x800 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name: profiles:[] descriptors:[]
	AudioAttributes: usage=USAGE_UNKNOWN content=CONTENT_TYPE_UNKNOWN flags=0x808 tags= bundle=null forVolume: true stream: STREAM_MUSIC(3)
		AudioDeviceAttributes: role:output type:speaker addr: name: profiles:[] descriptors:[]

[9] BLUETOOTH MANAGER HFP SECTION
============================================================
'grep' is not recognized as an internal or external command,
operable program or batch file.
