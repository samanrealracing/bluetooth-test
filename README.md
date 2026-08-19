============================================================ 
A21S - HFP / SCO / BLUETOOTH AUDIO HAL CHECK 
============================================================ 
Date: Wed 08/19/2026 
Time: 14:52:05.26 
 

============================================================
01 BUILD
============================================================
SM-A217F
a21s
15
35
lineage_a21s-userdebug 15 AP4A.250205.002 61e53241d0
22.1-20250401-NIGHTLY-a21s

============================================================
02 BLUETOOTH SETTINGS
============================================================
1
null
null

============================================================
03 BLUETOOTH APEX
============================================================
total 40
drwxr-xr-x  7 system system  4096 1970-01-01 03:30 .
drwxr-xr-x 69 root   root    1420 2026-08-19 14:48 ..
-rw-r--r--  1 system system   180 1970-01-01 03:30 apex_manifest.pb
drwxr-xr-x  3 root   shell   4096 1970-01-01 03:30 app
drwxr-xr-x  6 root   shell   4096 1970-01-01 03:30 etc
drwxr-xr-x  2 root   shell   4096 1970-01-01 03:30 javalib
drwxr-xr-x  2 root   shell   4096 1970-01-01 03:30 lib64
drwx------  2 root   root   16384 1970-01-01 03:30 lost+found
total 52
drwxr-xr-x 3 root   shell   4096 1970-01-01 03:30 .
drwxr-xr-x 6 root   shell   4096 1970-01-01 03:30 ..
-rw-r--r-- 1 system system  2618 1970-01-01 03:30 bt_did.conf
-rw-r--r-- 1 system system  2633 1970-01-01 03:30 bt_stack.conf
-rw-r--r-- 1 system system 31755 1970-01-01 03:30 interop_database.conf
drwxr-xr-x 2 root   shell   4096 1970-01-01 03:30 le_audio

============================================================
04 BLUETOOTH CONFIG CONTENT
============================================================
/apex/com.android.btservices/etc/bluetooth/interop_database.conf
/apex/com.android.btservices/etc/bluetooth/bt_did.conf
/apex/com.android.btservices/etc/bluetooth/bt_stack.conf
/apex/com.android.btservices/etc/bluetooth/le_audio/audio_set_scenarios.bfbs
/apex/com.android.btservices/etc/bluetooth/le_audio/audio_set_configurations.json
/apex/com.android.btservices/etc/bluetooth/le_audio/audio_set_configurations.bfbs
/apex/com.android.btservices/etc/bluetooth/le_audio/audio_set_scenarios.json

============================================================
05 BLUETOOTH AUDIO FILES - VENDOR
============================================================
/vendor/etc/bluetooth_audio_policy_configuration.xml
/vendor/etc/vintf/manifest/bluetooth_audio.xml

============================================================
06 BLUETOOTH AUDIO FILES - SYSTEM
============================================================

============================================================
07 AUDIO HAL LIBRARIES
============================================================
/system/lib64/libeffectsconfig.so

============================================================
08 HIDL BLUETOOTH AUDIO
============================================================
/system/lib64/android.hardware.audio@5.0-util.so
/system/lib64/android.hardware.audio@5.0.so
/system/lib64/android.hardware.audio@6.0-util.so
/system/lib64/android.hardware.audio@6.0.so

============================================================
09 AIDL AUDIO SERVICES
============================================================
17	android.hardware.bluetooth.audio.IBluetoothAudioProviderFactory/default: []
63	audio: [android.media.IAudioService]
74	bluetooth_manager: [android.bluetooth.IBluetoothManager]
150	media.aaudio: [aaudio.IAAudioService]
151	media.audio_flinger: [android.media.IAudioFlingerService]
152	media.audio_policy: [android.media.IAudioPolicyService]

============================================================
10 HAL SERVICE MANIFEST
============================================================
/vendor/etc/vintf/manifest.xml
/vendor/etc/vintf/manifest/vendor.samsung.hardware.radio_manifest_2_33.xml
/vendor/etc/vintf/manifest/android.hardware.wifi.hostapd.xml
/vendor/etc/vintf/manifest/android.hardware.health-service.samsung.xml
/vendor/etc/vintf/manifest/android.hardware.wifi-service.xml
/vendor/etc/vintf/manifest/android.hardware.usb.gadget-service.samsung.xml
/vendor/etc/vintf/manifest/android.hardware.light-service.samsung.xml
/vendor/etc/vintf/manifest/vendor.lineage.fastcharge@1.0-service.samsung.xml
/vendor/etc/vintf/manifest/bluetooth_audio.xml
/vendor/etc/vintf/manifest/vendor.samsung.hardware.sehradio_manifest_2_33.xml
/vendor/etc/vintf/manifest/android.hardware.nfc@1.2-service.samsung.xml
/vendor/etc/vintf/manifest/memtrack.xml
/vendor/etc/vintf/manifest/android.hardware.power-service.pixel.xml
/vendor/etc/vintf/manifest/vendor.samsung.hardware.thermal@1.0-manifest.xml
/vendor/etc/vintf/manifest/android.hardware.sensors-samsung-multihal.xml
/vendor/etc/vintf/manifest/android.hardware.wifi.supplicant.xml
/vendor/etc/vintf/manifest/android.hardware.camera.provider-service.samsung.xml
/vendor/etc/vintf/manifest/android.hardware.vibrator-service.samsung.xml
/vendor/etc/vintf/manifest/android.hardware.drm-service.clearkey.xml
/vendor/etc/vintf/manifest/android.hardware.cas@1.2-service.xml
/vendor/etc/vintf/manifest/android.hardware.biometrics.fingerprint-service.samsung.xml
/vendor/etc/vintf/manifest/manifest_android.hardware.drm@1.4-service.widevine.xml
/vendor/etc/vintf/manifest/vendor.samsung.hardware.radio.exclude.slsi.xml
/vendor/etc/vintf/manifest/android.hardware.usb-service.samsung.xml
/vendor/etc/vintf/compatibility_matrix.xml
/system/etc/vintf/compatibility_matrix.202404.xml
/system/etc/vintf/manifest.xml
/system/etc/vintf/compatibility_matrix.7.xml
/system/etc/vintf/compatibility_matrix.6.xml
/system/etc/vintf/compatibility_matrix.device.xml
/system/etc/vintf/manifest/android.frameworks.stats-service.xml
/system/etc/vintf/manifest/android.system.suspend-service.xml
/system/etc/vintf/manifest/android.system.keystore2-service.xml
/system/etc/vintf/manifest/manifest_android.frameworks.cameraservice.service.xml
/system/etc/vintf/manifest/android.system.net.netd-service.xml
/system/etc/vintf/manifest/manifest_services_android.frameworks.vibrator.xml
/system/etc/vintf/manifest/manifest_services.xml
/system/etc/vintf/manifest/manifest_media_c2_software.xml
/system/etc/vintf/compatibility_matrix.8.xml
/system/etc/vintf/compatibility_matrix.5.xml
/system_ext/etc/vintf/manifest.xml
/system_ext/etc/vintf/manifest/android.hidl.allocator@1.0-service.xml
/odm/etc/vintf/manifest_hcesimese.xml
/odm/etc/vintf/manifest_hce.xml
/odm/etc/vintf/manifest_hceese.xml
/odm/etc/vintf/manifest_hcesim.xml

============================================================
11 BLUETOOTH SERVICE
============================================================
17	android.hardware.bluetooth.audio.IBluetoothAudioProviderFactory/default: []
74	bluetooth_manager: [android.bluetooth.IBluetoothManager]

============================================================
12 BLUETOOTH MANAGER
============================================================
Bluetooth Status
  enabled: true
  state: ON
  address: XX:XX:XX:XX:82:10
  name: Galaxy A21s
  time since enabled: 00:03:01.715

Enable log:
  08-19 14:49:00.341 	Package [android] requested to [Enable]. 	Reason is SYSTEM_BOOT
  08-19 14:49:29.148 	Package [BluetoothSystemServer] requested to [Disable]. 	Reason is CRASH
  08-19 14:49:29.552 	Package [BluetoothSystemServer] requested to [Enable]. 	Reason is RESTARTED
  08-19 14:51:22.308 	Package [BluetoothSystemServer] requested to [Disable]. 	Reason is CRASH
  08-19 14:51:22.710 	Package [BluetoothSystemServer] requested to [Enable]. 	Reason is RESTARTED

Bluetooth crashed 2 times
  08-19 14:49:29.106
  08-19 14:51:22.308

Number of Ble app registered: 0

BluetoothManagerService:
  mEnable:true
  mQuietEnable:false
  mEnableExternal:true
  mQuietEnableExternal:false

🚩Flag dump:
	[■]: a2dp_aidl_encoding_interval
	[■]: a2dp_async_allow_low_latency
	[ ]: a2dp_broadcast_connection_state_when_turned_off
	[■]: a2dp_check_lea_iso_channel
	[■]: a2dp_fix_codec_type_in_java
	[ ]: a2dp_ignore_started_when_responder
	[■]: a2dp_service_looper
	[ ]: a2dp_variable_aac_capability
	[ ]: abs_volume_sdp_conflict
	[■]: adm_always_fallback_to_available_device
	[■]: adm_fallback_when_wired_audio_disconnected
	[■]: allow_switching_hid_and_hogp
	[■]: android_headtracker_service
	[■]: android_os_identifier
	[■]: api_get_connection_state_using_identity_address
	[■]: asha_encrypted_l2c_coc
	[■]: asymmetric_phy_for_unidirectional_cis
	[■]: audio_port_binder_inherit_rt
	[ ]: audio_routing_centralization
	[ ]: auto_connect_on_multiple_hfp_when_no_a2dp_device
	[ ]: av_stream_reconfigure_fix
	[■]: avdt_discover_seps_as_acceptor
	[ ]: avdt_prioritize_mandatory_codec
	[■]: avdtp_error_codes
	[■]: avoid_static_loading_of_native
	[■]: avrcp_connect_a2dp_with_delay
	[■]: avrcp_sdp_records
	[■]: ble_check_data_length_on_legacy_advertising
	[■]: ble_context_map_remove_fix
	[■]: ble_gatt_server_use_address_type_in_connection
	[■]: ble_scan_adv_metrics_redesign
	[ ]: bluetooth_power_telemetry
	[■]: bond_transport_after_bond_cancel_fix
	[■]: break_uhid_polling_early
	[ ]: browsing_refactor
	[ ]: bt_socket_api_l2cap_cid
	[■]: bt_system_context_report
	[ ]: bta_ag_cmd_brsf_allow_uint32
	[ ]: bta_av_setconfig_rej_type_confusion
	[ ]: bta_av_use_peer_codec
	[ ]: bta_dm_defer_device_discovery_state_change_until_rnr_complete
	[■]: bta_dm_discover_both
	[■]: btsec_check_valid_discovery_database
	[■]: cancel_open_discovery_client
	[■]: cancel_pairing_only_on_disconnected_transport
	[■]: channel_sounding
	[ ]: channel_sounding_in_stack
	[■]: choose_wrong_hfp_codec_in_specific_config
	[■]: cleanup_le_only_device_type
	[ ]: clear_auth_collision_state_on_pairing_complete
	[ ]: clear_pairing_state_when_no_devrec
	[ ]: close_hid_if_uhid_ready_too_slow
	[■]: close_hid_only_if_connected
	[■]: device_iot_config_logging
	[ ]: donot_push_error_code_to_app_when_connected
	[ ]: donot_queue_dup_rnr
	[ ]: donot_validate_bond_state_from_profiles
	[ ]: enable_hap_by_default
	[ ]: encrypted_advertising_data
	[ ]: encryption_change_v2
	[ ]: enforce_resolve_system_service_behavior
	[■]: enumerate_gatt_errors
	[■]: fast_bind_to_app
	[ ]: fix_avdt_rconfig_not_setting_l2cap
	[ ]: fix_hfp_qual19
	[■]: fix_le_evt_cancelling_sdp_discovery
	[■]: fix_nonconnectable_scannable_advertisement
	[ ]: fix_sco_command_status_handling
	[ ]: floss_separate_host_privacy_and_llprivacy
	[ ]: gatt_callback_on_failure
	[■]: gatt_cleanup_restricted_handles
	[ ]: gatt_client_dynamic_allocation
	[ ]: gatt_disconnect_fix
	[■]: gatt_fix_device_busy
	[■]: gatt_fix_multiple_direct_connect
	[■]: gatt_rediscover_on_canceled
	[ ]: gatt_server_requests_fix
	[ ]: get_all_element_attributes_empty
	[ ]: get_name_and_address_as_callback
	[ ]: get_state_from_system_server
	[ ]: guest_mode_bond
	[ ]: handle_delivery_sending_failure_events
	[■]: headset_client_am_hf_volume_symmetric
	[■]: headtracker_codec_capability
	[■]: headtracker_sdu_size
	[ ]: hfp_allow_volume_change_without_sco
	[ ]: hfp_client_disconnecting_state
	[ ]: hfp_software_datapath
	[■]: hid_report_queuing
	[■]: identity_address_null_if_not_known
	[ ]: ignore_notify_when_already_connected
	[ ]: improve_create_connection_for_already_connecting_device
	[■]: initiate_multiple_hid_connections
	[ ]: is_sco_managed_by_audio
	[ ]: key_missing_as_ordered_broadcast
	[■]: key_missing_broadcast
	[ ]: key_missing_classic_device
	[ ]: kill_instead_of_exit
	[ ]: l2cap_le_do_not_adjust_min_interval
	[■]: l2cap_p_ccb_check_rewrite
	[ ]: l2cap_tx_complete_cb_info
	[■]: l2cap_update_existing_conn_interval_with_base_interval
	[■]: le_ase_read_multiple_variable
	[■]: le_audio_base_ecosystem_interval
	[ ]: le_audio_support_unidirectional_voice_assistant
	[ ]: le_enc_on_reconnection
	[■]: le_inquiry_duration
	[■]: le_scan_fix_remote_exception
	[ ]: le_scan_msft_support
	[■]: le_scan_use_address_type
	[■]: le_scan_use_uid_for_importance
	[ ]: leaudio_add_aics_support
	[ ]: leaudio_allow_leaudio_only_devices
	[■]: leaudio_allowed_context_mask
	[ ]: leaudio_big_depends_on_audio_state
	[■]: leaudio_broadcast_assistant_peripheral_entrustment
	[■]: leaudio_broadcast_audio_handover_policies
	[■]: leaudio_broadcast_destroy_after_timeout
	[■]: leaudio_broadcast_extract_periodic_scanner_from_state_machine
	[■]: leaudio_broadcast_feature_support
	[■]: leaudio_broadcast_monitor_source_sync_status
	[ ]: leaudio_broadcast_resync_helper
	[■]: leaudio_broadcast_update_metadata_callback
	[■]: leaudio_broadcast_volume_control_for_connected_devices
	[■]: leaudio_broadcast_volume_control_primary_group_only
	[■]: leaudio_broadcast_volume_control_with_set_volume
	[■]: leaudio_call_start_scan_directly
	[■]: leaudio_codec_config_callback_order_fix
	[■]: leaudio_dynamic_spatial_audio
	[■]: leaudio_getting_active_state_support
	[ ]: leaudio_gmap_client
	[■]: leaudio_hal_client_asrc
	[ ]: leaudio_mono_location_errata
	[■]: leaudio_multicodec_aidl_support
	[■]: leaudio_multiple_vocs_instances_api
	[■]: leaudio_no_context_validate_streaming_request
	[ ]: leaudio_set_codec_config_preference
	[■]: leaudio_speed_up_reconfiguration_between_call
	[■]: leaudio_start_request_state_mutex_check
	[■]: leaudio_synchronize_start
	[ ]: leaudio_unicast_no_available_contexts
	[■]: leaudio_use_audio_mode_listener
	[ ]: maintain_call_index_after_conference
	[■]: map_limit_notification
	[■]: mcp_allow_play_without_active_player
	[■]: metadata_api_inactive_audio_device_upon_connection
	[ ]: msft_addr_tracking_quirk
	[■]: name_discovery_for_le_pairing
	[ ]: non_wake_alarm_for_rpa_rotation
	[ ]: nrpa_non_connectable_adv
	[■]: opp_fix_multiple_notifications_issues
	[■]: opp_ignore_content_observer_after_service_stop
	[■]: opp_start_activity_directly_from_notification
	[■]: override_context_to_specify_device_id
	[■]: pairing_name_discovery_addresss_mismatch
	[■]: pairing_on_unknown_transport
	[■]: pan_use_identity_address
	[ ]: phy_to_native
	[ ]: prevent_duplicate_uuid_intent
	[■]: prevent_hogp_reconnect_when_connected
	[■]: progress_acl_scheduler_upon_incoming_connection
	[ ]: queue_dis_requests
	[■]: randomize_device_level_media_ids
	[ ]: read_le_appearance
	[ ]: refactor_saving_messages_and_metadata
	[■]: remove_address_map_on_unbond
	[ ]: remove_dup_pairing_response_in_oob_pairing
	[■]: remove_input_device_on_vup
	[ ]: remove_one_time_get_name_and_address
	[■]: reset_after_collision
	[■]: reset_ag_state_on_collision
	[■]: respect_ble_scan_setting
	[ ]: retry_esco_with_zero_retransmission_effort
	[ ]: rfcomm_always_disc_initiator_in_disc_wait_ua
	[■]: rfcomm_always_use_mitm
	[■]: rfcomm_prevent_unnecessary_collisions
	[ ]: rnr_directly_call_gap_over_le
	[ ]: rnr_store_device_type
	[ ]: rnr_validate_page_scan_repetition_mode
	[ ]: run_ble_audio_ticks_in_worker_thread
	[ ]: run_clock_recovery_in_worker_thread
	[■]: save_initial_hid_connection_policy
	[ ]: save_peer_csrk_after_ltk_gen
	[ ]: scan_manager_refactor
	[■]: scan_record_manufacturer_data_merge
	[ ]: sec_dont_clear_keys_on_encryption_err
	[ ]: serialize_hogp_and_dis
	[ ]: set_addressed_player
	[■]: settings_can_control_hap_preset
	[ ]: signal_connecting_on_focus_gain
	[■]: sink_audio_policy_handover
	[ ]: skip_unknown_robust_caching
	[ ]: stack_sdp_detect_nil_property_type
	[■]: stop_on_offload_fail
	[ ]: support_bluetooth_quality_report_v6
	[■]: support_exclusive_manager
	[ ]: support_metadata_device_types_apis
	[■]: suppress_hid_rejection_broadcast
	[ ]: system_server_messenger
	[■]: temporary_pairing_device_properties
	[■]: transmit_smp_packets_before_release
	[■]: unbonded_profile_forbid_fix
	[ ]: uncache_player_when_browsed_player_changes
	[ ]: unified_connection_manager
	[■]: unix_file_socket_creation_failure
	[ ]: update_active_device_in_band_ringtone
	[■]: update_sco_state_correctly_on_rfcomm_disconnect_during_codec_nego
	[ ]: use_encrypt_req_for_av
	[ ]: use_entire_message_handle
	[ ]: use_le_shim_connection_map_guard
	[■]: use_local_oob_extended_command
	[ ]: vcp_mute_unmute
	[■]: wait_for_disconnect_before_unbond


AdapterProperties
  Name: Galaxy A21s
  Address: A8:30:BC:B8:82:10
  ConnectionState: STATE_CONNECTED
  State: ON
  MaxConnectedAudioDevices: 5
  A2dpOffloadEnabled: false
  Discovering: false
  DiscoveryEndMs: 0
  Bonded devices:
    6B:FD:FC:0A:87:7F [BR/EDR][ 0x24041C ] PDSTQS001
    CA:10:33:9A:46:78 [BR/EDR][ 0x340404 ] BT DONGLE
    42:31:0D:1F:10:8A [BR/EDR][ 0x340404 ] CAR-BT(A0F)
    3C:B0:ED:D9:F5:5E [ DUAL ][ 0x240404 ] CMF Buds 2a
    60:B9:7C:95:68:CC [BR/EDR][ 0x240404 ] HCW Music

ScanMode: SCAN_MODE_CONNECTABLE
Scan Mode Changes:
    08-19 14:51:23.947 (processProfileServiceStateChanged) SCAN_MODE_CONNECTABLE

sSnoopLogSettingAtEnable = EMPTY
sDefaultSnoopLogSettingAtEnable = null

Enabled Profile Services:
  GATT
  A2DP
  AVRCP
  BATTERY
  HEADSET
  HEARING_AID
  HID_DEVICE
  HID_HOST
  MAP
  OPP
  PAN
  PBAP
  SAP

AdapterState:
 total records=4
 rec[0]: time=08-19 14:51:23.461 processed=OffState org=OffState dest=TurningBleOnState what=3(0x3) BLE_TURN_ON
 rec[1]: time=08-19 14:51:23.563 processed=TurningBleOnState org=TurningBleOnState dest=BleOnState what=7(0x7) BLE_STARTED
 rec[2]: time=08-19 14:51:23.570 processed=BleOnState org=BleOnState dest=TurningOnState what=1(0x1) USER_TURN_ON
 rec[3]: time=08-19 14:51:24.037 processed=TurningOnState org=TurningOnState dest=OnState what=5(0x5) BREDR_STARTED
curState=OnState

SilenceDeviceManager:
  Address            | Is silenced?
  XX:XX:XX:XX:F5:5E  | false

BluetoothDatabase:
  Metadata Changes:

Metadata:
    XX:XX:XX:XX:F5:5E last_active_time=5 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=1|enabled=1), isActiveHfpDevice (true), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null|exclusive_manager=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}
    XX:XX:XX:XX:87:7F last_active_time=0 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=-1|enabled=-1), isActiveHfpDevice (false), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null|exclusive_manager=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}
    XX:XX:XX:XX:46:78 last_active_time=0 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=-1|enabled=-1), isActiveHfpDevice (false), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null|exclusive_manager=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}
    XX:XX:XX:XX:68:CC last_active_time=0 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=-1|enabled=-1), isActiveHfpDevice (false), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null|exclusive_manager=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}
    XX:XX:XX:XX:10:8A last_active_time=0 {profile connection policy(A2DP=100|A2DP_SINK=-1|CSIP_SET_COORDINATOR=-1|HEADSET=100|HEADSET_CLIENT=-1|HID_HOST=-1|PAN=-1|PBAP=-1|PBAP_CLIENT=-1|MAP=-1|MAP_CLIENT=-1|SAP=-1|HAP=-1|HEARING_AID=-1|LE_AUDIO=-1|VOLUME_CONTROL=-1|LE_CALL_CONTROL=-1|LE_BROADCAST_ASSISTANT=-1|BATTERY=-1), optional codec(support=-1|enabled=-1), isActiveHfpDevice (false), custom metadata(manufacturer_name=null|model_name=null|software_version=null|hardware_version=null|companion_app=null|main_icon=null|is_untethered_headset=null|untethered_left_icon=null|untethered_right_icon=null|untethered_case_icon=null|untethered_left_battery=null|untethered_right_battery=null|untethered_case_battery=null|untethered_left_charging=null|untethered_right_charging=null|untethered_case_charging=null|enhanced_settings_ui_uri=null|device_type=null|main_battery=null|main_charging=null|main_low_battery_threshold=null|untethered_left_low_battery_threshold=null|untethered_right_low_battery_threshold=null|untethered_case_low_battery_threshold=null|spatial_audio=null|fastpair_customized=null|le_audio=null|gmcs_cccd=null|gtbs_cccd=null|exclusive_manager=null), hfp client audio policy(callEstablishAudioPolicy=0|connectingTimeAudioPolicy=0|inBandRingtoneAudioPolicy=0)}

Profile: GattService
  mAdvertisingServiceUuids:

Registered App
  Scanner:
  Client:
  Server:


GATT Scanner Map
  Entries: 0

GATT Advertiser Map

GATT Client Map
  Entries: 0

GATT Server Map
  Entries: 0

GATT Handle Map
  Entries: 0
  Requests: 0

Profile: A2dpService
  mActiveDevice: XX:XX:XX:XX:F5:5E
  mMaxConnectedAudioDevices: 5
  codecConfigPriorities:
    SBC: 1001
    AAC: 2001
    aptX: 3001
    aptX HD: 4001
    LDAC: 5001
    Opus: 7001
  mA2dpOffloadEnabled: false
  === A2dpStateMachine for XX:XX:XX:XX:F5:5E (Active) ===
    getConnectionPolicy: 100
    mConnectionState: CONNECTED, mLastConnectionState: CONNECTING
    mIsPlaying: false
    getSupportsOptionalCodecs: 1, getOptionalCodecsEnabled: 1
    mCodecConfig: {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
    mCodecsSelectableCapabilities:
      {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
      {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}
    StateMachine: name=A2dpStateMachine state=Connected
    StateMachineLog:
      A2dpStateMachine:
       total records=5
       rec[0]: time=08-19 14:51:24.162 processed=Disconnected org=Disconnected dest=Connecting what=1(0x1) CONNECT: arg1=0, arg2=0, obj=null
       rec[1]: time=08-19 14:51:30.730 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_CONNECTION_STATE_CHANGED, device:XX:XX:XX:XX:F5:5E, value1:CONNECTING}
       rec[2]: time=08-19 14:51:32.721 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_CODEC_CONFIG_CHANGED, device:XX:XX:XX:XX:F5:5E, value1:0, codecStatus:{mCodecConfig:{codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0},mCodecsLocalCapabilities:[{codecName:LDAC,mCodecType:4,mCodecPriority:5001,mSampleRate:0xf(44100|48000|88200|96000),mBitsPerSample:0x7(16|24|32),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:aptX HD,mCodecType:3,mCodecPriority:4001,mSampleRate:0x3(44100|48000),mBitsPerSample:0x2(24),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:aptX,mCodecType:2,mCodecPriority:3001,mSampleRate:0x3(44100|48000),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}],mCodecsSelectableCapabilities:[{codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}]}}
       rec[3]: time=08-19 14:51:32.770 processed=Connecting org=Connecting dest=Connected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_CONNECTION_STATE_CHANGED, device:XX:XX:XX:XX:F5:5E, value1:CONNECTED}
       rec[4]: time=08-19 14:51:37.312 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=A2dpStackEvent {type:EVENT_TYPE_CODEC_CONFIG_CHANGED, device:XX:XX:XX:XX:F5:5E, value1:0, codecStatus:{mCodecConfig:{codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0},mCodecsLocalCapabilities:[{codecName:LDAC,mCodecType:4,mCodecPriority:5001,mSampleRate:0xf(44100|48000|88200|96000),mBitsPerSample:0x7(16|24|32),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:aptX HD,mCodecType:3,mCodecPriority:4001,mSampleRate:0x3(44100|48000),mBitsPerSample:0x2(24),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:aptX,mCodecType:2,mCodecPriority:3001,mSampleRate:0x3(44100|48000),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}],mCodecsSelectableCapabilities:[{codecName:AAC,mCodecType:1,mCodecPriority:2001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x2(STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}, {codecName:SBC,mCodecType:0,mCodecPriority:1001,mSampleRate:0x1(44100),mBitsPerSample:0x1(16),mChannelMode:0x3(MONO|STEREO),mCodecSpecific1:0,mCodecSpecific2:0,mCodecSpecific3:0,mCodecSpecific4:0}]}}
      curState=Connected

Profile: AvrcpTargetService:
  AVRCP version: 1.6
  List of MediaControllers: size=3
  <Active>   Media Player 1: org.telegram.messenger.web
    MediaController (org.telegram.messenger.web@6353cdf) ‎⁨۲۰۰۰ دلار⁩.m4a, Unknown artist, null
    Current Data:
      Song: { mediaId="currsong" title="‎⁨۲۰۰۰ دلار⁩.m4a" artist="Unknown artist" album="" genre="" duration=1216000 trackPosition=1/1 image=null }
      PlayState: PlaybackState {state=NONE(0), position=0, buffered position=0, speed=1.0, updated=50981, actions=2477828, custom actions=[], active item id=-1, error=null}
      Queue: size=2
        { mediaId="NowPlayingId1" title="‎⁨۲۰۰۰ دلار⁩.m4a" artist="Unknown artist" album="" genre="" duration=1216000 trackPosition=1/2 image=null }
        { mediaId="NowPlayingId0" title="‎⁨۲۰۰۰ دلار⁩.m4a" artist="Unknown artist" album="" genre="" duration=1216000 trackPosition=2/2 image=null }
    BTAudio Playback State change Event:
  
    Media Player 2: org.lineageos.twelve
    MediaController (org.lineageos.twelve@b10d2c) null
    Current Data:
      Song: { mediaId="currsong" title="Not provided" artist="" album="" genre="" duration=0 trackPosition=1/1 image=null }
      PlayState: PlaybackState {state=NONE(0), position=0, buffered position=0, speed=0.0, updated=176704, actions=7339655, custom actions=[Action:mName='Shuffle off, mIcon=2131231092, mExtras=Bundle[mParcelledData.dataSize=164], Action:mName='Repeat off, mIcon=2131231087, mExtras=Bundle[mParcelledData.dataSize=172]], active item id=0, error=null}
      Queue: size=0
    BTAudio Playback State change Event:
  
    Media Player 3: ir.nasim
    MediaController (ir.nasim@96e33f5) null, null, null
    Current Data:
      Song: { mediaId="currsong" title="Not provided" artist="" album="" genre="" duration=0 trackPosition=1/1 image=null }
      PlayState: null
      Queue: size=0
    BTAudio Playback State change Event:
  
  List of Browsers: size=2
    Browsable Package Name: org.telegram.messenger.web
       Cached Media ID's: "__ROOT__", 
  
    Browsable Package Name: org.lineageos.twelve
       Cached Media ID's: "[root]", 
  
  BTAudio Active Player Events:
    08-19 14:51:26.660 setActivePlayer(): setting player to org.telegram.messenger.web
  
  BTAudio Audio Playback State Events:
  
  BTAudio Media Key Events:
  
  AvrcpVolumeManager:
    mCurrentDevice: XX:XX:XX:XX:F5:5E
    Current System Volume: 16
    Device Volume Memory Map:
      Device Address    : Device Name    : Vol : AbsVol
      3C:B0:ED:D9:F5:5E : CMF Buds 2a    :  16 : true
    BTAudio Volume Events:
      08-19 14:51:38.516 switchVolumeDevice: Updating device volume: avrcpVolume=81
      08-19 14:51:38.522 switchVolumeDevice: Updating device volume: avrcpVolume=81
  
  AvrcpCoverArtService:
  	psm = 4097
  	images (0 / 32):
  		Handle   : Hash                              : CoverArt
  	Image bytes: 0
  	clients = []

Profile: BatteryService

Profile: HeadsetService
  mMaxHeadsetConnections: 5
  DefaultMaxHeadsetConnections: 5
  mActiveDevice: XX:XX:XX:XX:F5:5E
  isInbandRingingEnabled: true
  isInbandRingingSupported: true
  mInbandRingingRuntimeDisable: false
  mAudioRouteAllowed: true
  mVoiceRecognitionStarted: false
  mVoiceRecognitionTimeoutEvent: null
  mVirtualCallStarted: false
  mDialingOutTimeoutEvent: null
  mForceScoAudio: false
  AudioManager.isBluetoothScoOn(): false
  Telecom.isInCall(): false
  Telecom.isRinging(): false
  ==== StateMachine for XX:XX:XX:XX:F5:5E ====
    mCurrentDevice: XX:XX:XX:XX:F5:5E
    mCurrentState: Connected
    mPrevState: Connecting
    mConnectionState: 2
    mAudioState: 10
    mNeedDialingOutReply: false
    mSpeakerVolume: 15
    mMicVolume: 0
    mConnectingTimestampMs(uptimeMillis): 188914
    mHsClientAudioPolicy: BluetoothSinkAudioPolicy{mCallEstablishPolicy: 0, mConnectingTimePolicy: 0, mInBandRingtonePolicy: 0}
    StateMachine: name=HeadsetStateMachine state=Connected
    StateMachineLog:
      HeadsetStateMachine:
       total records=20
       rec[0]: time=08-19 14:51:24.058 processed=Disconnected org=Disconnected dest=Connecting what=1(0x1) CONNECT: arg1=0, arg2=0, obj=XX:XX:XX:XX:F5:5E
       rec[1]: time=08-19 14:51:30.722 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=1, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[2]: time=08-19 14:51:30.723 processed=Connecting org=Connecting dest=Disconnected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=0, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[3]: time=08-19 14:51:36.998 processed=Disconnected org=Disconnected dest=Connecting what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=1, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[4]: time=08-19 14:51:37.008 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=2, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[5]: time=08-19 14:51:37.083 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_WBS[17], valInt=2, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[6]: time=08-19 14:51:37.084 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_SWB[21], valInt=0, valInt2=1, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[7]: time=08-19 14:51:37.117 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_AT_CIND[12], valInt=0, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[8]: time=08-19 14:51:37.171 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_NOISE_REDUCTION[9], valInt=0, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[9]: time=08-19 14:51:37.207 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_UNKNOWN_AT[15], valInt=0, valInt2=0, valString=+XAPL=000D-0001-0101,2, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[10]: time=08-19 14:51:37.222 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_BIA[20], valInt=0, valInt2=0, valString=null, valObject=HeadsetAgIndicatorEnableState[service=false, roam=false, signal=false, battery=false], device=XX:XX:XX:XX:F5:5E
       rec[11]: time=08-19 14:51:37.227 processed=Connecting org=Connecting dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_BIND[18], valInt=0, valInt2=0, valString=2, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[12]: time=08-19 14:51:37.252 processed=Connecting org=Connecting dest=Connected what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_CONNECTION_STATE_CHANGED[1], valInt=3, valInt2=0, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[13]: time=08-19 14:51:37.283 processed=Connected org=Connected dest=<null> what=13(0xd) UNKNOWN(13): arg1=1, arg2=0, obj=null
       rec[14]: time=08-19 14:51:37.294 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_BIEV[19], valInt=2, valInt2=65, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[15]: time=08-19 14:51:37.294 processed=Connected org=Connected dest=<null> what=10(0xa) DEVICE_STATE_CHANGED: arg1=0, arg2=0, obj=HeadsetDeviceState[hasCellularService=1, isRoaming=0, signalStrength0, batteryCharge=4]
       rec[16]: time=08-19 14:51:37.294 processed=Connected org=Connected dest=<null> what=10(0xa) DEVICE_STATE_CHANGED: arg1=0, arg2=0, obj=HeadsetDeviceState[hasCellularService=1, isRoaming=0, signalStrength5, batteryCharge=4]
       rec[17]: time=08-19 14:51:37.307 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_VOLUME_CHANGED[6], valInt=1, valInt2=9, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[18]: time=08-19 14:51:37.337 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_VOLUME_CHANGED[6], valInt=0, valInt2=15, valString=null, valObject=null, device=XX:XX:XX:XX:F5:5E
       rec[19]: time=08-19 14:51:37.338 processed=Connected org=Connected dest=<null> what=101(0x65) STACK_EVENT: arg1=0, arg2=0, obj=EVENT_TYPE_UNKNOWN_AT[15], valInt=0, valInt2=0, valString=+XNTSF=B185, valObject=null, device=XX:XX:XX:XX:F5:5E
      curState=Connected

Profile: HearingAidService

Profile: HidDeviceService

Profile: HidHostService
  mInputDevices:

Profile: BluetoothMapService
  mRemoteDevice: null
  mState: 0
  mAppObserver: com.android.bluetooth.map.BluetoothMapAppObserver@52d062f
  mIsWaitingAuthorization: false
  mRemoveTimeoutMsg: false
  mPermission: 0
  mAccountChanged: false
  mBluetoothMnsObexClient: null
  mMasInstanceMap:
    null : MasId: 0 Uri:null SMS/MMS:true
  mEnabledAccounts:

Profile: BluetoothOppService

Profile: PanService
  mMaxPanDevices: 5
  mPanIfName: bt-pan
  mTetherOn: false
  mPanDevices:

Profile: BluetoothPbapService

Profile: SapService

Connection Events:
  08-19 14:51:36.959 CONNECTED    xx:xx:xx:xx:f5:5e
  08-19 14:51:36.959 CONNECTED    xx:xx:xx:xx:f5:5e
  08-19 14:51:36.959 CONNECTED    xx:xx:xx:xx:f5:5e

Bond Events: 
  Total Number of events: 0

Link Key Types:
  xx:xx:xx:xx:87:7f
    BR: UNAUTH_COMB
    LE:
  xx:xx:xx:xx:46:78
    BR: UNAUTH_COMB
    LE:
  xx:xx:xx:xx:10:8a
    BR: UNAUTH_COMB
    LE:
  xx:xx:xx:xx:f5:5e
    BR: UNAUTH_COMB
    LE:
  xx:xx:xx:xx:68:cc
    BR: UNAUTH_COMB
    LE:

AVRCP Native State:
  Devices (0 / 5):

A2DP State:
  TxQueue:
  Counts (enqueue/dequeue/readbuf)                        : 0 / 0 / 0
  Last update time ago in ms (enqueue/dequeue/readbuf)    : 0 / 0 / 0
  Frames per packet (total/max/ave)                       : 0 / 0 / 0
  Counts (flushed/dropped/dropouts)                       : 0 / 0 / 0
  Counts (max dropped)                                    : 0
  Last update time ago in ms (flushed/dropped)            : 0 / 0
  Counts (underflow)                                      : 0
  Bytes (underflow)                                       : 0
  Last update time ago in ms (underflow)                  : 0
  Enqueue deviation counts (overdue/premature)            : 0 / 0
  Enqueue overdue scheduling time in ms (total/max/ave)   : 0 / 0 / 0
  Enqueue premature scheduling time in ms (total/max/ave) : 0 / 0 / 0
  Dequeue deviation counts (overdue/premature)            : 0 / 0
  Dequeue overdue scheduling time in ms (total/max/ave)   : 0 / 0 / 0
  Dequeue premature scheduling time in ms (total/max/ave) : 0 / 0 / 0

A2DP Codecs State:
  Current Codec: AAC

A2DP LDAC State:
  Priority: 5001
  Config: Invalid
  Selectable: Invalid
  Local capability: Rate=44100|48000|88200|96000 Bits=16|24|32 Mode=STEREO
  LDAC quality mode                                       : HIGH
  LDAC transmission bitrate (Kbps)                        : -1
  LDAC saved transmit queue length                        : 0
  Encoder interval (ms): 20
  Effective MTU: 0
  Packet counts (expected/dropped)                        : 0 / 0
  PCM read counts (expected/actual)                       : 0 / 0
  PCM read bytes (expected/actual)                        : 0 / 0

A2DP aptX-HD State:
  Priority: 4001
  Config: Invalid
  Selectable: Invalid
  Local capability: Rate=44100|48000 Bits=24 Mode=STEREO
  Encoder interval (ms): 0
  Effective MTU: 0
  Packet counts (expected/dropped)                        : 0 / 0
  PCM read counts (expected/actual)                       : 0 / 0
  PCM read bytes (expected/actual)                        : 0 / 0

A2DP aptX State:
  Priority: 3001
  Config: Invalid
  Selectable: Invalid
  Local capability: Rate=44100|48000 Bits=16 Mode=STEREO
  Encoder interval (ms): 0
  Effective MTU: 0
  Packet counts (expected/dropped)                        : 0 / 0
  PCM read counts (expected/actual)                       : 0 / 0
  PCM read bytes (expected/actual)                        : 0 / 0

A2DP AAC State:
  Priority: 2001
  Config: Rate=44100 Bits=16 Mode=STEREO
  Selectable: Rate=44100 Bits=16 Mode=STEREO
  Local capability: Rate=44100 Bits=16 Mode=STEREO
  AAC bitrate mode                                        : Constant (0x0)
  Encoder interval (ms): 23
  Effective MTU: 663
  Packet counts (expected/dropped)                        : 0 / 0
  PCM read counts (expected/actual)                       : 0 / 0
  PCM read bytes (expected/actual)                        : 0 / 0

A2DP SBC State:
  Priority: 1001
  Config: Invalid
  Selectable: Rate=44100 Bits=16 Mode=MONO|STEREO
  Local capability: Rate=44100 Bits=16 Mode=MONO|STEREO
  Encoder interval (ms): 20
  Effective MTU: 0
  Packet counts (expected/dropped)                        : 0 / 0
  PCM read counts (expected/actual)                       : 0 / 0
  PCM read bytes (expected/actual)                        : 0 / 0
  Frames counts (expected/dropped)                        : 0 / 0

A2DP Peers State:
  Source: active peer: xx:xx:xx:xx:f5:5e
  Sink: active peer: null
  Peer: xx:xx:xx:xx:f5:5e
    Number of sinks: 2
    Number of sources: 0
    Number of SEPs: 2
    Number of received sinks: 2
    Number of received sources: 0
    Number of supported sinks: 2
    Number of supported sources: 0
    Acceptor: false
    Reconfig needed: false
    Opened: true
    MTU: 667
    UUID to connect: 0x110b
    BTA AV handle: 65

A2DP Source State: Enabled
  Active peer: xx:xx:xx:xx:f5:5e
  Peers:
  Peer: xx:xx:xx:xx:f5:5e
    Connected: true
    Streaming: false
    SEP: 1(Sink)
    State Machine: Opened
    Flags: 0x0(None)
    OpenOnRcTimer: Not scheduled
    BTA Handle: 0x41
    Peer ID: 0
    EDR: true
    Support 3Mbps: false
    Self Initiated Connection: true
    Delay Reporting: 2100 (in 1/10 milliseconds) 
    Codec Preferred: Optional

A2DP Sink State: Disabled

BTA AV State:
  State Machine State: INIT
  SDP A2DP source handle: 65539
  SDP A2DP sink handle: 0
  Features: 0x865b
  SDP handle: 65
  Disabling: false
  SCO occupied: false
  Connected audio channels: 1
  Connected audio channels mask: 0x1
  Registered audio channels mask: 0x3f
  Connected LCBs mask: 0x1
  Offload start pending handle: 0
  Offload started handle: 0

  Link control block: 0 peer: xx:xx:xx:xx:f5:5e
    Connected stream handle mask: 0x2
    Index(+1) to LCB: 1

  BTA ID: 0 peer: xx:xx:xx:xx:f5:5e
    SDP discovery started: false
    SEP ID: 0
      SEP AVDTP handle: 1
      Local SEP type: 0
      Codec: SBC
    SEP ID: 1
      SEP AVDTP handle: 2
      Local SEP type: 0
      Codec: AAC
    SEP ID: 2
      SEP AVDTP handle: 3
      Local SEP type: 0
      Codec: aptX
    SEP ID: 3
      SEP AVDTP handle: 4
      Local SEP type: 0
      Codec: aptX-HD
    SEP ID: 4
      SEP AVDTP handle: 5
      Local SEP type: 0
      Codec: LDAC
    BTA info tag: 0
    API Open peer: 00:00:00:00:00:00
      Use AVRCP: false
      Switch result: 0
      Initiator UUID: 0x0
    Saved API Open peer: xx:xx:xx:xx:f5:5e
      Use AVRCP: true
      Switch result: 0
      Initiator UUID: 0x110a
  Link signalling timer: Not scheduled
  Accept signalling timer: Not scheduled
    L2CAP Channel ID: 67
    Stream MTU: 667
    AVDTP version: 0x103
    Media type: 0
    Congested: true
    Open status: 0
    Channel: 64
    BTA handle: 0x41
    Protocol service capabilities mask: 0x102
    AVDTP handle: 2
    Stream control block index: 0
    State machine state: OPEN(3)
    AVDTP label: 0x0
    Application ID: 0
    Role: 0x0
    Queued L2CAP buffers: 0
    AVRCP allowed: true
    Stream started: false
    Stream call-out started: 0
    AVDTP Reconfig supported: true
    AVDTP Suspend supported: true
    Deregistering: false
    SCO automatic Suspend: false
    Incoming/outgoing connection collusion mask: 0x0
    Wait mask: 0x0
    Don't use RTP header: false
    Intended UUID of Initiator to connect to: 0x110a

AVDTP Stack State:
  AVDTP signalling L2CAP channel MTU: 672

  Channel control block: 0 peer: xx:xx:xx:xx:f5:5e
    Allocated: true
    State: 2
    Link-layer opened: true
    Discover in progress: false
    Congested: false
    Reinitiate connection on idle: false
    Command retransmission count: 0
    BTA AV SCB index: 0

    Stream control block: 1
      SEP codec: AAC
      SEP protocol service capabilities: 0x102
      SEP type: 0x0
      Media type: 0x0
      MTU: 1005
      AVDT SCB handle: 2
      SCB index: 0
      Configured codec: AAC
      Requested codec: AAC
      Transport channel connect timer: Not scheduled
      Channel control block peer: xx:xx:xx:xx:f5:5e
      Allocated: true
      In use: true
      Role: 0x3
      Remove: false
      State: 3
      Peer SEID: 2
      Current event: 43
      Congested: false
      Close response code: 0

Socket Events: 
  Time        	Address          	State             	Role              	Channel   	Type     	ServerName
  14:51:23.831	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	RFCOMM	
  14:51:23.833	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	5         	RFCOMM	
  14:51:23.836	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	L2CAP	
  14:51:23.837	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	4099         	L2CAP	
  14:51:23.846	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	RFCOMM	
  14:51:23.847	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	6         	RFCOMM	
  14:51:23.849	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	L2CAP	
  14:51:23.850	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	4101         	L2CAP	
  14:51:24.168	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	RFCOMM	
  14:51:24.169	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	7         	RFCOMM	
  14:51:24.247	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	RFCOMM	
  14:51:24.248	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	8         	RFCOMM	
  14:51:24.260	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	-2         	L2CAP	
  14:51:24.260	00:00:00:00:00:00	STATE_LISTENING   	ROLE_LISTEN      	4103         	L2CAP	
  14:51:33.734	xx:xx:xx:xx:f5:5e	STATE_CONNECTING   	ROLE_CONNECTION      	-1         	RFCOMM	aeac4a03-dff5-498f-843a-34487cf133eb
  14:51:33.900	xx:xx:xx:xx:f5:5e	STATE_CONNECTED   	ROLE_CONNECTION      	6         	RFCOMM	aeac4a03-dff5-498f-843a-34487cf133eb


AVRCP Target Native Service: 1 devices
    xx:xx:xx:xx:f5:5e <Active>
    Current Volume: 81
    Current Browsed Player ID: -1
    Registered Notifications:
        Play Status
    Last Play State: stack::gatt    last 2 tcb state transitions:
stack::gatt    2026-08-19 14:51:36.958 xx:xx:xx:xx:f5:5e, BT_TRANSPORT_BR_EDR, state: GATT_CH_CFG, No ACL holders
stack::gatt    2026-08-19 14:51:36.958 xx:xx:xx:xx:f5:5e, BT_TRANSPORT_BR_EDR, state: GATT_CH_OPEN, No ACL holders
TCB (GATT_MAX_PHY_CHANNEL: 8) in_use: 1
  id: 0  address: xx:xx:xx:xx:f5:5e  transport: BT_TRANSPORT_BR_EDR  ch_state: GATT_CH_OPEN, No ACL holders

BTA_GATTC_CB state BTA_GATTC_STATE_ENABLED 
 ->conn_track (GATT_MAX_PHY_CHANNEL=16)
  -- used: 0
 ->bg_track (BTA_GATTC_KNOWN_SR_MAX=255)
  -- used: 0
 ->cl_rcb (BTA_GATTC_CL_MAX=32)
  client_if: 4  app uuids: 08647fca-0a8c-f75e-4eb2-0cf375d1561b  clcb_num: 0
  client_if: 5  app uuids: bc37dbd8-4e55-0f80-7ef7-0f46db5224ec  clcb_num: 0
  client_if: 6  app uuids: 976cfc05-c7a6-882c-fbd1-e2467ebf5005  clcb_num: 0
  -- used: 3
 ->clcb (BTA_GATTC_CLCB_MAX=512)
  -- used: 0
 ->known_server (BTA_GATTC_KNOWN_SR_MAX=255)
  -- used: 0


Bluetooth Iot Config:
  Config Source: Original file
  Devices loaded: 9
  File created/tagged: 2026-07-27 03:51:54

Bluetooth HF Client BTA Statistics

Bluetooth Wakelock Statistics:
  Is acquired                    : false
  Acquired/released count        : 4 / 4
  Acquired/released error count  : 0 / 0
  Last acquire/release error code: 0 / 0
  Last acquired time (ms)        : 12
  Acquired time min/max/avg (ms) : 12 / 729 / 193
  Total acquired time (ms)       : 774
  Total run time (ms)            : 29062

Bluetooth Alarms Statistics:
  Total Alarms: 0

Coordinated Set Service Client:

Hearing Access Service Client:
  no instance

Hearing Aid Manager:
  Hearing Aid Audio HAL:
    Counts (underflow)                                      : 0
    Bytes (underflow)                                       : 0
    Last update time ago in ms (underflow)                  : 0

Device Groups Manager:
  Not initialized 
LeAudio Manager: 
  Not initialized 
  LE AudioHalClient:
    Counts (underflow)                                      : 0
    Bytes (underflow)                                       : 0
    Last update time ago in ms (underflow)                  : 0

 AudioSetConfigurationProvider not initialized: config provider: 0, pimpl: 0 
  ----------------
   ISO Manager:
    Available credits: 0
    Controller buffer size: 0
    Num of ISO traffic callbacks: 1
    CISes:
    BISes:
  ----------------
 
Le Audio Broadcaster:

Volume Control Manager:


connection_manager state:
	no Low Energy connection attempts

BT Quality Report Events: 
Event queue is empty.
 ----- shim::legacy::pan -----
shim::legacy::pan Connections:0 roles configured:C.N[0x5] current:...[0x0] previous:...[0x0]
shim::legacy::pan service_name_user:"Android Network User"
shim::legacy::pan service_name_nap:"Android Network Access Point"
 ----- shim::legacy::hid -----
shim::legacy::hid status:BTIF_HH_ENABLED num_devices:0
shim::legacy::hid status:BTIF_HH_ENABLED
 ----- shim::legacy::bta::dm -----
shim::legacy::bta::dm  last 0 discovery state transitions
shim::legacy::bta::dm  current bta_dm_discovery_state:BTA_DM_DISCOVER_IDLE
shim::legacy::bta::dm  last 1 search state transitions
shim::legacy::bta::dm    2026-08-19 14:51:33.730 state:       BTA_DM_SEARCH_IDLE event:BTA_DM_API_SEARCH_CANCEL_EVT
shim::legacy::bta::dm  current bta_dm_search_state:BTA_DM_SEARCH_IDLE
shim::legacy::bta::dm  last 0 gatt history entries
 ----- shim::legacy::sdp -----
shim::legacy::sdp max_attribute_list_size:1008 max_records_per_search:21
shim::legacy::sdp peer:xx:xx:xx:xx:f5:5e discovery_state:SDP_DISC_WAIT_SEARCH_ATTR
shim::legacy::sdp   connection_state:tSDP_STATE::IDLE(0x0) connection_flags:0x01 mtu:192 l2cap_cid:75
shim::legacy::sdp peer:xx:xx:xx:xx:f5:5e discovery_state:SDP_DISC_WAIT_SEARCH_ATTR
shim::legacy::sdp   connection_state:tSDP_STATE::IDLE(0x0) connection_flags:0x01 mtu:0 l2cap_cid:70
 ----- shim::record -----
shim::record 001 xx:xx:xx:xx:87:7f BR_EDR cod:2400-4-1c remote_info:UNKNOWN        sm4:0x00 SecureConn:F name:"PDSTQS001"sec_prop:bredr_linkkey_known:T,le_linkkey_known:F,bond_type:BOND_TYPE_PERSISTENT,bredr_linkkey_type:UNAUTH_COMB,ble_enc_key_size:0,bredr_authenticated:F,le_authenticated:F,16_digit_key_authenticated:F,bredr_encrypted:F,le_encrypted:F
shim::record 002 xx:xx:xx:xx:46:78 BR_EDR cod:3400-4-4 remote_info:UNKNOWN        sm4:0x00 SecureConn:F name:"BT DONGLE"sec_prop:bredr_linkkey_known:T,le_linkkey_known:F,bond_type:BOND_TYPE_PERSISTENT,bredr_linkkey_type:UNAUTH_COMB,ble_enc_key_size:0,bredr_authenticated:F,le_authenticated:F,16_digit_key_authenticated:F,bredr_encrypted:F,le_encrypted:F
shim::record 003 xx:xx:xx:xx:10:8a BR_EDR cod:3400-4-4 remote_info:UNKNOWN        sm4:0x00 SecureConn:F name:"CAR-BT(A0F)"sec_prop:bredr_linkkey_known:T,le_linkkey_known:F,bond_type:BOND_TYPE_PERSISTENT,bredr_linkkey_type:UNAUTH_COMB,ble_enc_key_size:0,bredr_authenticated:F,le_authenticated:F,16_digit_key_authenticated:F,bredr_encrypted:F,le_encrypted:F
shim::record 004 xx:xx:xx:xx:f5:5e BR_EDR cod:2400-4-4 remote_info:13-00003-01602 sm4:0x11 SecureConn:F name:"CMF Buds 2a"sec_prop:bredr_linkkey_known:T,le_linkkey_known:F,bond_type:BOND_TYPE_PERSISTENT,bredr_linkkey_type:UNAUTH_COMB,ble_enc_key_size:16,bredr_authenticated:T,le_authenticated:F,16_digit_key_authenticated:F,bredr_encrypted:T,le_encrypted:F
shim::record 005 xx:xx:xx:xx:68:cc BR_EDR cod:2400-4-4 remote_info:UNKNOWN        sm4:0x00 SecureConn:F name:"HCW Music"sec_prop:bredr_linkkey_known:T,le_linkkey_known:F,bond_type:BOND_TYPE_PERSISTENT,bredr_linkkey_type:UNAUTH_COMB,ble_enc_key_size:0,bredr_authenticated:F,le_authenticated:F,16_digit_key_authenticated:F,bredr_encrypted:F,le_encrypted:F
 ----- shim::legacy::l2cap -----
shim::legacy::l2cap link_state:LST_CONNECTED(0x4)
shim::legacy::l2cap handle:0x0003
shim::legacy::l2cap   active channel lcid:0x0042 rcid:0x018d is_ecoc:false in_use:true
shim::legacy::l2cap   active channel lcid:0x0043 rcid:0x018e is_ecoc:false in_use:true
shim::legacy::l2cap   active channel lcid:0x0045 rcid:0x0190 is_ecoc:false in_use:true
shim::legacy::l2cap   active channel lcid:0x0048 rcid:0x0193 is_ecoc:false in_use:true
shim::legacy::l2cap   active channel lcid:0x004a rcid:0x0195 is_ecoc:false in_use:true
 ----- shim::btm -----
shim::btm  2026-08-19 14:51:23.504 Initialized btm history
shim::btm  2026-08-19 14:51:23.763 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:2 scn:2 dlci:4 mtu:990
shim::btm  2026-08-19 14:51:23.780 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:3 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.780 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:4 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.780 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:5 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.780 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:6 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.781 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:7 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.781 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:8 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.781 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:9 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.781 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:10 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.782 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:11 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.782 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:12 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.782 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:13 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:23.782 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:14 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:23.816 PAN    Registered               : 00:00:00:00:00:00 
shim::btm  2026-08-19 14:51:23.817 PAN    Role change              : 00:00:00:00:00:00 role:0x5
shim::btm  2026-08-19 14:51:23.833 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:15 scn:5 dlci:10 mtu:990
shim::btm  2026-08-19 14:51:23.847 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:16 scn:6 dlci:12 mtu:990
shim::btm  2026-08-19 14:51:23.948 SCAN   Classic updated          : 00:00:00:00:00:00 inquiry_scan_enable:F page_scan_enable:F
shim::btm  2026-08-19 14:51:23.948 SCAN   Classic updated          : 00:00:00:00:00:00 inquiry_scan_enable:F page_scan_enable:T
shim::btm  2026-08-19 14:51:24.059 RFCOMM Server stopped           : 00:00:00:00:00:00 handle:3 scn:3 dlci:6 is_server:true
shim::btm  2026-08-19 14:51:24.059 RFCOMM Server stopped           : 00:00:00:00:00:00 handle:4 scn:4 dlci:8 is_server:true
shim::btm  2026-08-19 14:51:24.060 ACL    Initiated connection     : xx:xx:xx:xx:f5:5e classic
shim::btm  2026-08-19 14:51:24.169 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:17 scn:7 dlci:14 mtu:990
shim::btm  2026-08-19 14:51:24.248 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:18 scn:8 dlci:16 mtu:990
shim::btm  2026-08-19 14:51:30.713 ACL    Connection failed        : xx:xx:xx:xx:f5:5e classic reason:CONNECTION_ACCEPT_TIMEOUT(0x10)
shim::btm  2026-08-19 14:51:30.720 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:19 scn:3 dlci:6 mtu:256
shim::btm  2026-08-19 14:51:30.720 RFCOMM Server started           : ff:ff:ff:ff:ff:ff handle:20 scn:4 dlci:8 mtu:256
shim::btm  2026-08-19 14:51:30.730 ACL    Initiated connection     : xx:xx:xx:xx:f5:5e classic
shim::btm  2026-08-19 14:51:32.414 ACL    Connection successful    : xx:xx:xx:xx:f5:5e classic Local initiated
shim::btm  2026-08-19 14:51:32.415 ACL    Role change              : xx:xx:xx:xx:f5:5e classic New_role:CENTRAL(0x00) status:SUCCESS(0x00)
shim::btm  2026-08-19 14:51:32.567 SEC    Encryption success       : xx:xx:xx:xx:f5:5e status:HCI_SUCCESS transport:BT_TRANSPORT_BR_EDR is_encrypted:T
shim::btm  2026-08-19 14:51:32.767 A2DP   Stream opened            : xx:xx:xx:xx:f5:5e BTA_AV_OPEN_EVT(0x2)
shim::btm  2026-08-19 14:51:33.730 API    Cancel discovery         : 00:00:00:00:00:00 
shim::btm  2026-08-19 14:51:33.812 RFCOMM Connection opened        : xx:xx:xx:xx:f5:5e handle:21 scn:6 dlci:12 mtu:990
shim::btm  2026-08-19 14:51:36.994 RFCOMM Server stopped           : 00:00:00:00:00:00 handle:5 scn:3 dlci:6 is_server:true
shim::btm  2026-08-19 14:51:45.983 ACL    Power mode change        : xx:xx:xx:xx:f5:5e immediate:sniff[0x02] ==> immediate:active[0x00]
shim::legacy::dumpsys Dumping shim legacy targets:1
shim::stack Stack information ᛒᚼ
shim::stack Classic inquiry:disabled
shim::stack Le scan:disabled
shim::stack Last 0 inquiry scans:
 ----- shim::acl -----
shim::acl Shadow le accept list              size:0   controller_max_size:60
shim::acl Shadow le address resolution list  size:0   controller_max_size:25
shim::acl remote_addr:xx:xx:xx:xx:f5:5e handle:0x0003 transport:BT_TRANSPORT_BR_EDR
shim::acl     link_up_issued: true
shim::acl     flush_timeout:0x0000
shim::acl     link_supervision_timeout:5.000 sec
shim::acl     disconnect_reason:0x00
shim::acl     peer_lmp_features[0] valid:true data:0xbf 0xee 0x4d 0xfa 0xd8 0x3d 0x7b 0x87 
shim::acl     peer_lmp_features[1] valid:true data:0x03 0x00 0x00 0x00 0x00 0x00 0x00 0x00 
shim::acl     peer_lmp_features[2] valid:true data:0x10 0x02 0x00 0x00 0x00 0x00 0x00 0x00 
shim::acl     [classic] link_policy:0x0x0005 : role_switch  sniff_mode 
shim::acl     [classic] sniff_subrating:false
shim::acl     pkt_types_mask:0xcc18
shim::acl     role:central
 ----- Filtering as Developer -----
{
  title: "----- Gd Dumpsys ------",
  wakelock_manager_data: {
    title: "Bluetooth Wakelock Statistics",
    is_acquired: false,
    is_native: true,
    acquired_count: 1,
    released_count: 1,
    acquired_error_count: 0,
    released_error_count: 0,
    last_acquire_error_code: 0,
    last_release_error_code: 0,
    last_acquired_timestamp_millis: 256,
    last_released_timestamp_millis: 175316,
    last_interval_millis: 256,
    max_interval_millis: 256,
    min_interval_millis: 256,
    avg_interval_millis: 256,
    total_interval_millis: 256,
    total_time_since_reset_millis: 39002
  },
  shim_dumpsys_data: {
    title: "----- Shim Dumpsys -----",
    number_of_bundled_schemas: 6
  },
  hci_acl_manager_dumpsys_data: {
    title: "----- Acl Manager Dumpsys -----",
    le_filter_accept_list_count: 0,
    le_filter_accept_list: [

    ],
    le_connectability_state: "ConnectabilityState::DISARMED",
    le_create_connection_timeout_alarms_count: 0
  },
  hci_controller_dumpsys_data: {
    title: "----- Hci Controller Dumpsys -----",
    local_version_information: {
      hci_version: "V_5_0(0x09)",
      hci_revision: 8290,
      lmp_version: "V_5_0(0x09)",
      manufacturer_name: 117,
      lmp_subversion: 8290
    },
    acl_buffer_size: {
      data_packet_length: 1021,
      total_num_packets: 20
    },
    sco_buffer_size: {
      data_packet_length: 0,
      total_num_packets: 0
    },
    iso_buffer_size: {
      data_packet_length: 0,
      total_num_packets: 0
    },
    le_buffer_size: {
      data_packet_length: 251,
      total_num_packets: 10
    },
    le_accept_list_size: 60,
    le_resolving_list_size: 25,
    le_maximum_data_length: {
      supported_max_tx_octets: 251,
      supported_max_tx_time: 2704,
      supported_max_rx_octets: 251,
      supported_max_rx_time: 2704
    },
    le_maximum_advertising_data_length: 1650,
    le_suggested_default_data_length: 27,
    le_number_supported_advertising_sets: 16,
    le_periodic_advertiser_list_size: 32,
    local_supported_commands: [
      {
        index: 0,
        value: 255
      },
      {
        index: 1,
        value: 255
      },
      {
        index: 2,
        value: 255
      },
      {
        index: 3,
        value: 3
      },
      {
        index: 4,
        value: 206
      },
      {
        index: 5,
        value: 255
      },
      {
        index: 6,
        value: 255
      },
      {
        index: 7,
        value: 255
      },
      {
        index: 8,
        value: 255
      },
      {
        index: 9,
        value: 255
      },
      {
        index: 10,
        value: 231
      },
      {
        index: 11,
        value: 255
      },
      {
        index: 12,
        value: 243
      },
      {
        index: 13,
        value: 15
      },
      {
        index: 14,
        value: 232
      },
      {
        index: 15,
        value: 254
      },
      {
        index: 16,
        value: 63
      },
      {
        index: 17,
        value: 247
      },
      {
        index: 18,
        value: 131
      },
      {
        index: 19,
        value: 255
      },
      {
        index: 20,
        value: 28
      },
      {
        index: 21,
        value: 0
      },
      {
        index: 22,
        value: 4
      },
      {
        index: 23,
        value: 0
      },
      {
        index: 24,
        value: 97
      },
      {
        index: 25,
        value: 247
      },
      {
        index: 26,
        value: 255
      },
      {
        index: 27,
        value: 255
      },
      {
        index: 28,
        value: 127
      },
      {
        index: 29,
        value: 56
      },
      {
        index: 30,
        value: 0
      },
      {
        index: 31,
        value: 0
      },
      {
        index: 32,
        value: 254
      },
      {
        index: 33,
        value: 252
      },
      {
        index: 34,
        value: 255
      },
      {
        index: 35,
        value: 255
      },
      {
        index: 36,
        value: 255
      },
      {
        index: 37,
        value: 255
      },
      {
        index: 38,
        value: 255
      },
      {
        index: 39,
        value: 7
      },
      {
        index: 40,
        value: 0
      },
      {
        index: 41,
        value: 8
      },
      {
        index: 42,
        value: 0
      },
      {
        index: 43,
        value: 0
      },
      {
        index: 44,
        value: 0
      },
      {
        index: 45,
        value: 0
      },
      {
        index: 46,
        value: 0
      },
      {
        index: 47,
        value: 0
      },
      {
        index: 48,
        value: 0
      },
      {
        index: 49,
        value: 0
      },
      {
        index: 50,
        value: 0
      },
      {
        index: 51,
        value: 0
      },
      {
        index: 52,
        value: 0
      },
      {
        index: 53,
        value: 0
      },
      {
        index: 54,
        value: 0
      },
      {
        index: 55,
        value: 0
      },
      {
        index: 56,
        value: 0
      },
      {
        index: 57,
        value: 0
      },
      {
        index: 58,
        value: 0
      },
      {
        index: 59,
        value: 0
      },
      {
        index: 60,
        value: 0
      },
      {
        index: 61,
        value: 0
      },
      {
        index: 62,
        value: 0
      },
      {
        index: 63,
        value: 0
      }
    ],
    extended_lmp_features_array: [
      9753670738334711487,
      2,
      768
    ],
    le_local_supported_features: 134248959,
    le_supported_states: 4398046511103,
    vendor_capabilities: {
      is_supported: 1,
      max_advt_instances: 16,
      offloaded_resolution_of_private_address: 0,
      total_scan_results_storage: 16384,
      max_irk_list_sz: 0,
      filtering_support: 1,
      max_filter: 32,
      activity_energy_info_support: 1,
      version_supported: 24576,
      total_num_of_advt_tracked: 12,
      extended_scan_support: 1,
      debug_logging_supported: 0,
      le_address_generation_offloading_support: 0,
      a2dp_source_offload_capability_mask: 0,
      bluetooth_quality_report_support: 1
    }
  }
}

============================================================
13 BLUETOOTH PROFILE STATE
============================================================
/system/bin/sh: HEADSET: inaccessible or not found
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: connected: inaccessible or not found
/system/bin/sh: state: inaccessible or not found
/system/bin/sh: audio: inaccessible or not found
/system/bin/sh: disconnect: inaccessible or not found
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: profile: inaccessible or not found

============================================================
14 AUDIO SERVICE
============================================================
Events log: audio services lifecycle
08-19 14:48:57:145 AudioService()

Message handler (watch for unhandled messages):
  Handler (com.android.server.audio.AudioService$AudioHandler) {cfca9ec} @ 214503
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

MediaFocusControl dump time: 14:52:02

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
   Current: 1 (earpiece): 15, 2 (speaker): 15, 20 (bt_sco_hs): 15, 40 (bt_sco_carkit): 8, 80 (bt_a2dp): 11, 40000000 (default): 11
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

PlaybackActivityMonitor dump time: 14:52:02

  playback listeners:
 PlayMonitorClient:S uid:1000 pid:5094
 PlayMonitorClient:S uid:1000 pid:5094
 PlayMonitorClient:S uid:1002 pid:13305



  players:
(not logged)  AudioPlaybackConfiguration piid:143 deviceId:0 type:android.media.SoundPool u/pid:1000/5094 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}
  AudioPlaybackConfiguration piid:151 deviceId:0 type:android.media.SoundPool u/pid:10154/5343 state:idle attr:AudioAttributes: usage=USAGE_ASSISTANCE_SONIFICATION content=CONTENT_TYPE_SONIFICATION flags=0x800 tags= bundle=null sessionId:0 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}
  AudioPlaybackConfiguration piid:183 deviceId:0 type:android.media.MediaPlayer u/pid:10229/11803 state:idle attr:AudioAttributes: usage=USAGE_MEDIA content=CONTENT_TYPE_MUSIC flags=0x800 tags= bundle=null sessionId:273 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}
  AudioPlaybackConfiguration piid:191 deviceId:0 type:android.media.SoundPool u/pid:10189/13392 state:idle attr:AudioAttributes: usage=USAGE_VOICE_COMMUNICATION content=CONTENT_TYPE_SPEECH flags=0x800 tags= bundle=null sessionId:0 mutedState:none  FormatInfo{isSpatialized=false, channelMask=0x0, sampleRate=0}

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

  allowed capture policies:

RecordActivityMonitor dump time: 14:52:02


Events log: recording activity received by AudioService

AudioDeviceBroker:
  Message handler (watch for unhandled messages):
    Handler (com.android.server.audio.AudioDeviceBroker$BrokerHandler) {50dc04a} @ 214514
      Looper (AudioDeviceBroker, tid 127) {c8e2f4d}
        (MessageQueue is using Legacy implementation)
        (Total messages: 0, polling=true, quitting=false)

  BECOMING_NOISY_INTENT_DEVICES_SET=
 0x400 0x800 0x8000000 0x20000000 0x80 0x100 0x200 0x2000 0x4000 0x4000000 0x20000001 0x20000 0x20000002 0x4 0x8
  Preferred devices for strategy:

  Non-default devices for strategy:

  Connected devices:
    [DeviceInfo: type:0x20 (bt_sco_hs) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 0 group:-1 peer addr: peer identity addr: disabled modes: {}]
    [DeviceInfo: type:0x80000008 (bt_sco_hs) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 0 group:-1 peer addr: peer identity addr: disabled modes: {}]
    [DeviceInfo: type:0x80 (bt_a2dp) name:CMF Buds 2a addr:XX:XX:XX:XX:F5:5E identity addr:XX:XX:XX:XX:F5:5E codec: 4000000 group:-1 peer addr: peer identity addr: disabled modes: {}]

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
  Active communication device: AudioDeviceAttributes: role:output type:bt_a2dp addr:XX:XX:XX:XX:F5:5E name:CMF Buds 2a profiles:[{ENCODING_PCM_16BIT, sampling rates=[44100, 48000, 88200, 96000], channel masks=0x0C, encapsulation type=0}] descriptors:[]
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
  Handler (com.android.server.audio.SoundEffectsHelper$SfxHandler) {aad9bbb} @ 214519
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


Events log: wired/A2DP/hearing aid device connection
08-19 14:49:33:343 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: setNewModeOwner
08-19 14:49:33:344 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: setNewModeOwner
08-19 14:49:33:394 setCommunicationRouteForClient for uid: 1000 device: null isPrivileged: true from API: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:49:33:405 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: clearCommunicationDevice() from u/pid:1000/5094
08-19 14:49:54:420 BluetoothActiveDeviceChanged for A2DP, device update null -> XX:XX:XX:XX:F5:5E
08-19 14:49:54:423 BluetoothActiveDeviceChanged for A2DP, device update XX:XX:XX:XX:F5:5E -> XX:XX:XX:XX:F5:5E
08-19 14:49:54:429 msg: MSG_L_BT_ACTIVE_DEVICE_CHANGE_EXT BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0
08-19 14:49:54:474 BT connected:BtDeviceInfo: device=XX:XX:XX:XX:F5:5E state=2 prof=2 supprNoisy=true volume=16 isLeOutput=false eventSource=AudioService audioSystemDevice=128 musicDevice=0 codec=AUDIO_FORMAT_AAC
08-19 14:49:54:878 A2DP sink device addr=XX:XX:XX:XX:F5:5E now available
08-19 14:49:54:917 onBluetoothDeviceConfigChange addr=3C:B0:ED:D9:F5:5E event=DEVICE_CONFIG_CHANGE
08-19 14:49:54:960 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false
08-19 14:49:55:030 removePreferredDevicesForStrategy strat:1020
08-19 14:49:58:242 SCO sink device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:49:58:288 SCO source device addr=3C:B0:ED:D9:F5:5E now available
08-19 14:49:58:309 synchronizeDeviceProfilesInInventory synced device pair ads1=type: 7 internal type: 0x20 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false ads2=type: 8 internal type: 0x80 addr: XX:XX:XX:XX:F5:5E bt audio type: AUDIO_DEVICE_CATEGORY_UNKNOWN enabled: false HT: false HTenabled: false
08-19 14:51:21:068 updateCommunicationRoute, preferredCommunicationDevice: null eventSource: setNewModeOwner
08-19 14:51:22:332 BT profile service: disconnecting HEADSET profile
08-19 14:51:22:332 BT profile service: disconnecting A2DP profile
08-19 14:51:22:332 BT profile service: disconnecting HEARING_AID profile
08-19 14:51:22:332 BT profile HEADSET disconnected
08-19 14:51:22:456 SCO sink device addr=3C:B0:ED:D9:F5:5E made unavailable
08-19 14:51:22:558 SCO source device addr=3C:B0:ED:D9:F5:5E made unavailable
08-19 14:51:22:563 BT profile A2DP disconnected
08-19 14:51:22:570 BT profile HEARING_AID disconnected
08-19 14:51:22:571 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: setCommunicationDevice() from u/pid:1000/5094
08-19 14:51:22:572 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: setCommunicationDevice() from u/pid:1000/5094
08-19 14:51:22:912 setCommunicationRouteForClient for uid: 1000 device: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] isPrivileged: true from API: resetBluetoothSco
08-19 14:51:22:913 updateCommunicationRoute, preferredCommunicationDevice: AudioDeviceAttributes: role:output type:earpiece addr: name:SM-A217F profiles:[{ENCODING_PCM_16BIT, sampling rates=[48000], channel masks=0x04, encapsulation type=0}] descriptors:[] eventSource: resetBluetoothSco
08-19 14:51:22:913 broadcast ACTION_AUDIO_BECOMING_NOISY
08-19 14:51:23:693 A2DP device addr=XX:XX:XX:XX:F5:5E made unavailable
08-19 14:51:24:065 BT profile service: connecting HEADSET profile
08-19 14:51:24:066 BT profile HEADSET connected to proxy android.bluetooth.BluetoothHeadset@29098b
08-19 14:51:24:069 BT profile service: connecting A2DP profile
08-19 14:51:24:072 BT profile service: connecting HEARING_AID profile
08-19 14:51:24:076 BT profile A2DP connected to proxy android.bluetooth.BluetoothA2dp@ee39a68
08-19 14:51:24:079 BT profile HEARING_AID connected to proxy android.bluetooth.BluetoothHearingAid@fe8fb26
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


Events log: force use (logged before setForceUse() is executed)
08-19 14:49:01:027 setForceUse(FOR_ENCODED_SURROUND, FORCE_NONE) due to readPersistedSettings
08-19 14:49:01:233 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:04:755 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094 src:onSetBtActiveDevice
08-19 14:49:26:483 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:26:815 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:29:974 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:29:976 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
08-19 14:49:33:342 setForceUse(FOR_MEDIA, FORCE_NONE) due to setBluetoothA2dpOn(true) from u/pid:1000/5094
08-19 14:49:33:748 setForceUse(FOR_VIBRATE_RINGING, FORCE_NONE) due to muteRingerModeStreams() from u/pid:1000/5094
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



Loudness alignment:

Registered clients:


Events log: Loudness updates
08-19 14:49:16:597 Loudness client with pid 6344 died
08-19 14:49:22:930 Loudness client with pid 6386 died
08-19 14:49:26:876 Loudness client with pid 6369 died
08-19 14:49:54:939 Loudness client with pid 8398 died
08-19 14:50:06:675 Loudness client with pid 8402 died
08-19 14:50:10:332 Loudness client with pid 8404 died


Absolute voume devices:
Device type: 0x80, driving stream 3
Device type: 0x8000000, driving stream 3
Device type: 0x20000000, driving stream 3
Device type: 0x20000001, driving stream 3
Device type: 0x20000002, driving stream 3

AudioSystemAdapter:
 last cache clear time: 08-19 14:51:39:154
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

============================================================
15 AUDIO HAL RELATED STATE
============================================================
/system/bin/sh: audio: inaccessible or not found
/system/bin/sh: HFP: inaccessible or not found
/system/bin/sh: HAL: inaccessible or not found
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: earpiece: inaccessible or not found
/system/bin/sh: communication: inaccessible or not found
/system/bin/sh: speaker: inaccessible or not found

============================================================
16 AUDIO POLICY
============================================================
Supported System Usages:
  AUDIO_USAGE_CALL_ASSISTANT
UID Policy:
	mObserverRegistered=True
	Assistants UIDs: 
		UID[0]=10205
	Active Assistants UIDs: 
		No UIDs present.
	Accessibility UIDs: 
		No UIDs present.
	Input Method Service UID=10139
	Is RTT Enabled: False
AudioCommandThread: 0x7260d46770
- Commands:
   Command Time        Wait pParam
  Last Command
   00      000190.757  0    0x71d0d58d00
OutputCommandThread: 0x7260d45590
- Commands:
   Command Time        Wait pParam
  Last Command
   05      000193.366  0    0x71d0d5af20

AudioPolicyManager Dump: 0x71a0d4b790
 Primary Output I/O handle: 13
 Phone state: AUDIO_MODE_NORMAL
 Force use for communications: 0
 Force use for media: 0
 Force use for record: 0
 Force use for dock: 9
 Force use for system: 0
 Force use for HDMI system audio: 0
 Force use for encoded surround output: 0
 Force use for vibrate ringing: 0
 TTS output not available
 Master mono: off
 Communication Strategy id: 1015
 Config source: /vendor/etc/audio_policy_configuration.xml

 Available output devices (4):
  1. Port ID: 2; "Earpiece"; {AUDIO_DEVICE_OUT_EARPIECE, @:}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 48000
         channel masks: 0x0001
         AUDIO_ENCAPSULATION_TYPE_NONE
  2. Port ID: 3; "Speaker"; {AUDIO_DEVICE_OUT_SPEAKER, @:}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 48000
         channel masks: 0x0003
         AUDIO_ENCAPSULATION_TYPE_NONE
  3. Port ID: 36; "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
     Encapsulation modes: 0, metadata types: 0
     "CMF Buds 2a"
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 48000
         channel masks: 0x0003
         AUDIO_ENCAPSULATION_TYPE_NONE
  4. Port ID: 39; "BT A2DP Out"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
     Encapsulation modes: 0, metadata types: 0
     "CMF Buds 2a"
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 44100, 48000, 88200, 96000
         channel masks: 0x0003
         AUDIO_ENCAPSULATION_TYPE_NONE

 Available input devices (5):
  1. Port ID: 10; "Built-In Mic"; {AUDIO_DEVICE_IN_BUILTIN_MIC, @:bottom}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
         channel masks: 0x000c, 0x0010, 0x0030
         AUDIO_ENCAPSULATION_TYPE_NONE
  2. Port ID: 37; "Bt Sco Headset Mic"; {AUDIO_DEVICE_IN_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
     Encapsulation modes: 0, metadata types: 0
     "CMF Buds 2a"
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
         channel masks: 0x000c, 0x0010, 0x0030
         AUDIO_ENCAPSULATION_TYPE_NONE
  3. Port ID: 11; "Voice Call Mic"; {AUDIO_DEVICE_IN_TELEPHONY_RX, @:}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
         channel masks: 0x000c, 0x0010, 0x0030
         AUDIO_ENCAPSULATION_TYPE_NONE
  4. Port ID: 12; "Built-In Back Mic"; {AUDIO_DEVICE_IN_BACK_MIC, @:back}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
         channel masks: 0x000c, 0x0010, 0x0030
         AUDIO_ENCAPSULATION_TYPE_NONE
  5. Port ID: 14; "Remote Submix In"; {AUDIO_DEVICE_IN_REMOTE_SUBMIX, @:0}
     Encapsulation modes: 0, metadata types: 0
   - Profiles (1):
      1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
         sampling rates: 48000
         channel masks: 0x000c
         AUDIO_ENCAPSULATION_TYPE_NONE

 Hardware modules (4):
  1. Handle: 10; "primary"
   - Output MixPorts (3):
      1. "primary-out"; 0x0002 (AUDIO_OUTPUT_FLAG_PRIMARY)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 48000
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (8):
        1. Port ID: 2; "Earpiece"; {AUDIO_DEVICE_OUT_EARPIECE, @:}
           Encapsulation modes: 0, metadata types: 0
        2. Port ID: 3; "Speaker"; {AUDIO_DEVICE_OUT_SPEAKER, @:}
           Encapsulation modes: 0, metadata types: 0
        3. "Wired Headset"; {AUDIO_DEVICE_OUT_WIRED_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        4. "Wired Headphone"; {AUDIO_DEVICE_OUT_WIRED_HEADPHONE, @:}
           Encapsulation modes: 0, metadata types: 0
        5. "Bt Sco"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO, @:}
           Encapsulation modes: 0, metadata types: 0
        6. Port ID: 36; "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
           Encapsulation modes: 0, metadata types: 0
           "CMF Buds 2a"
        7. "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        8. "Bt Sco Car Kit"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_CARKIT, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 1
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
      2. "deep-buffer"; 0x0008 (AUDIO_OUTPUT_FLAG_DEEP_BUFFER)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 48000
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (8):
        1. Port ID: 2; "Earpiece"; {AUDIO_DEVICE_OUT_EARPIECE, @:}
           Encapsulation modes: 0, metadata types: 0
        2. Port ID: 3; "Speaker"; {AUDIO_DEVICE_OUT_SPEAKER, @:}
           Encapsulation modes: 0, metadata types: 0
        3. "Wired Headset"; {AUDIO_DEVICE_OUT_WIRED_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        4. "Wired Headphone"; {AUDIO_DEVICE_OUT_WIRED_HEADPHONE, @:}
           Encapsulation modes: 0, metadata types: 0
        5. "Bt Sco"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO, @:}
           Encapsulation modes: 0, metadata types: 0
        6. Port ID: 36; "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
           Encapsulation modes: 0, metadata types: 0
           "CMF Buds 2a"
        7. "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        8. "Bt Sco Car Kit"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_CARKIT, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 1
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
      3. "fast"; 0x0004 (AUDIO_OUTPUT_FLAG_FAST)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 48000
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (8):
        1. Port ID: 2; "Earpiece"; {AUDIO_DEVICE_OUT_EARPIECE, @:}
           Encapsulation modes: 0, metadata types: 0
        2. Port ID: 3; "Speaker"; {AUDIO_DEVICE_OUT_SPEAKER, @:}
           Encapsulation modes: 0, metadata types: 0
        3. "Wired Headset"; {AUDIO_DEVICE_OUT_WIRED_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        4. "Wired Headphone"; {AUDIO_DEVICE_OUT_WIRED_HEADPHONE, @:}
           Encapsulation modes: 0, metadata types: 0
        5. "Bt Sco"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO, @:}
           Encapsulation modes: 0, metadata types: 0
        6. Port ID: 36; "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
           Encapsulation modes: 0, metadata types: 0
           "CMF Buds 2a"
        7. "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        8. "Bt Sco Car Kit"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_CARKIT, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 1
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Input MixPorts (1):
      1. "primary-in"; 0x0000 (AUDIO_INPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
             channel masks: 0x000c, 0x0010, 0x0030
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (8):
        1. Port ID: 10; "Built-In Mic"; {AUDIO_DEVICE_IN_BUILTIN_MIC, @:bottom}
           Encapsulation modes: 0, metadata types: 0
        2. Port ID: 37; "Bt Sco Headset Mic"; {AUDIO_DEVICE_IN_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
           Encapsulation modes: 0, metadata types: 0
           "CMF Buds 2a"
        3. "Bt Sco Headset Mic"; {AUDIO_DEVICE_IN_BLUETOOTH_SCO_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        4. "Wired Headset Mic"; {AUDIO_DEVICE_IN_WIRED_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        5. "Aux Device In"; {AUDIO_DEVICE_IN_HDMI, @:}
           Encapsulation modes: 0, metadata types: 0
        6. Port ID: 11; "Voice Call Mic"; {AUDIO_DEVICE_IN_TELEPHONY_RX, @:}
           Encapsulation modes: 0, metadata types: 0
        7. Port ID: 12; "Built-In Back Mic"; {AUDIO_DEVICE_IN_BACK_MIC, @:back}
           Encapsulation modes: 0, metadata types: 0
        8. "FM Mic"; {AUDIO_DEVICE_IN_FM_TUNER, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Declared devices (15):
    1. Port ID: 2; "Earpiece"; {AUDIO_DEVICE_OUT_EARPIECE, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0001
           AUDIO_ENCAPSULATION_TYPE_NONE
    2. Port ID: 3; "Speaker"; {AUDIO_DEVICE_OUT_SPEAKER, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    3. "Wired Headset"; {AUDIO_DEVICE_OUT_WIRED_HEADSET, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    4. "Wired Headphone"; {AUDIO_DEVICE_OUT_WIRED_HEADPHONE, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    5. "Bt Sco"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    6. "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    7. "Bt Sco Car Kit"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_CARKIT, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    8. "Aux Device Out"; {AUDIO_DEVICE_OUT_HDMI, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 44100, 48000, 64000, 88200, 96000, 128000, 176400, 192000
           channel masks: 0x0001, 0x0003, 0x000b, 0x0033, 0x0037, 0x003f, 0x013f, 0x063f
           AUDIO_ENCAPSULATION_TYPE_NONE
    9. Port ID: 10; "Built-In Mic"; {AUDIO_DEVICE_IN_BUILTIN_MIC, @:bottom}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
           channel masks: 0x000c, 0x0010, 0x0030
           AUDIO_ENCAPSULATION_TYPE_NONE
    10. "Bt Sco Headset Mic"; {AUDIO_DEVICE_IN_BLUETOOTH_SCO_HEADSET, @:}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
    11. "Wired Headset Mic"; {AUDIO_DEVICE_IN_WIRED_HEADSET, @:}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
    12. "Aux Device In"; {AUDIO_DEVICE_IN_HDMI, @:}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
    13. Port ID: 11; "Voice Call Mic"; {AUDIO_DEVICE_IN_TELEPHONY_RX, @:}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
    14. Port ID: 12; "Built-In Back Mic"; {AUDIO_DEVICE_IN_BACK_MIC, @:back}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
    15. "FM Mic"; {AUDIO_DEVICE_IN_FM_TUNER, @:}
        Encapsulation modes: 0, metadata types: 0
      - Profiles (1):
         1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
            sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
            channel masks: 0x000c, 0x0010, 0x0030
            AUDIO_ENCAPSULATION_TYPE_NONE
   - Dynamic devices (2):
    1. Port ID: 36; "Bt Sco Headset"; {AUDIO_DEVICE_OUT_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
       Encapsulation modes: 0, metadata types: 0
       "CMF Buds 2a"
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    2. Port ID: 37; "Bt Sco Headset Mic"; {AUDIO_DEVICE_IN_BLUETOOTH_SCO_HEADSET, @:3C:B0:ED:D9:F5:5E}
       Encapsulation modes: 0, metadata types: 0
       "CMF Buds 2a"
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 8000, 11025, 12000, 16000, 22050, 24000, 32000, 44100, 48000
           channel masks: 0x000c, 0x0010, 0x0030
           AUDIO_ENCAPSULATION_TYPE_NONE
   - Audio Routes (8):
      1. Mix; Sink: "Earpiece"
         Sources: "primary-out", "deep-buffer", "fast"
      2. Mix; Sink: "Speaker"
         Sources: "primary-out", "deep-buffer", "fast"
      3. Mix; Sink: "Wired Headset"
         Sources: "primary-out", "deep-buffer", "fast"
      4. Mix; Sink: "Wired Headphone"
         Sources: "primary-out", "deep-buffer", "fast"
      5. Mix; Sink: "Bt Sco"
         Sources: "primary-out", "deep-buffer", "fast"
      6. Mix; Sink: "Bt Sco Headset"
         Sources: "primary-out", "deep-buffer", "fast"
      7. Mix; Sink: "Bt Sco Car Kit"
         Sources: "primary-out", "deep-buffer", "fast"
      8. Mix; Sink: "primary-in"
         Sources: "Built-In Mic", "Built-In Back Mic", "Wired Headset Mic", "Bt Sco Headset Mic", "Aux Device In", "Voice Call Mic", "FM Mic"
  2. Handle: 18; "bluetooth"
   - Output MixPorts (2):
      1. "a2dp output"; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
       - Profiles (3):
          1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
             AUDIO_ENCAPSULATION_TYPE_NONE
          2. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_PCM_16_BIT (0x1)
             AUDIO_ENCAPSULATION_TYPE_NONE
          3. ""; [dynamic format]; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 44100
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (3):
        1. Port ID: 39; "BT A2DP Out"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
           Encapsulation modes: 0, metadata types: 0
           "CMF Buds 2a"
        2. "BT A2DP Headphones"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_HEADPHONES, @:}
           Encapsulation modes: 0, metadata types: 0
        3. "BT A2DP Speaker"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_SPEAKER, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 1
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
       - mixerBehaviors: 0
      2. "hearing aid output"; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 16000, 24000
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (1):
        1. "BT Hearing Aid Out"; {AUDIO_DEVICE_OUT_HEARING_AID, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Declared devices (4):
    1. Port ID: 39; "BT A2DP Out"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Encapsulation modes: 0, metadata types: 0
       "CMF Buds 2a"
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 44100, 48000, 88200, 96000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    2. "BT A2DP Headphones"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_HEADPHONES, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 44100, 48000, 88200, 96000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    3. "BT A2DP Speaker"; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP_SPEAKER, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 44100, 48000, 88200, 96000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    4. "BT Hearing Aid Out"; {AUDIO_DEVICE_OUT_HEARING_AID, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
   - Audio Routes (4):
      1. Mix; Sink: "BT A2DP Out"
         Sources: "a2dp output"
      2. Mix; Sink: "BT A2DP Headphones"
         Sources: "a2dp output"
      3. Mix; Sink: "BT A2DP Speaker"
         Sources: "a2dp output"
      4. Mix; Sink: "BT Hearing Aid Out"
         Sources: "hearing aid output"
  3. Handle: 26; "usb"
   - Output MixPorts (2):
      1. "usb_accessory output"; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 44100
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (1):
        1. "USB Host Out"; {AUDIO_DEVICE_OUT_USB_ACCESSORY, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
      2. "usb_device output"; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (3):
        1. "USB DGTL Dock Out"; {AUDIO_DEVICE_OUT_DGTL_DOCK_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
        2. "USB Device Out"; {AUDIO_DEVICE_OUT_USB_DEVICE, @:}
           Encapsulation modes: 0, metadata types: 0
        3. "USB Headset Out"; {AUDIO_DEVICE_OUT_USB_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
       - mixerBehaviors: 0
   - Input MixPorts (1):
      1. "usb_device input"; 0x0000 (AUDIO_INPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (2):
        1. "USB Device In"; {AUDIO_DEVICE_IN_USB_DEVICE, @:}
           Encapsulation modes: 0, metadata types: 0
        2. "USB Headset In"; {AUDIO_DEVICE_IN_USB_HEADSET, @:}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Declared devices (6):
    1. "USB DGTL Dock Out"; {AUDIO_DEVICE_OUT_DGTL_DOCK_HEADSET, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
    2. "USB Host Out"; {AUDIO_DEVICE_OUT_USB_ACCESSORY, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 44100
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    3. "USB Device Out"; {AUDIO_DEVICE_OUT_USB_DEVICE, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
    4. "USB Headset Out"; {AUDIO_DEVICE_OUT_USB_HEADSET, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
    5. "USB Device In"; {AUDIO_DEVICE_IN_USB_DEVICE, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
    6. "USB Headset In"; {AUDIO_DEVICE_IN_USB_HEADSET, @:}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; [dynamic format][dynamic channels][dynamic rates]; AUDIO_FORMAT_DEFAULT (0x0)
           AUDIO_ENCAPSULATION_TYPE_NONE
   - Audio Routes (5):
      1. Mix; Sink: "USB Host Out"
         Sources: "usb_accessory output"
      2. Mix; Sink: "USB DGTL Dock Out"
         Sources: "usb_device output"
      3. Mix; Sink: "USB Device Out"
         Sources: "usb_device output"
      4. Mix; Sink: "USB Headset Out"
         Sources: "usb_device output"
      5. Mix; Sink: "usb_device input"
         Sources: "USB Device In", "USB Headset In"
  4. Handle: 34; "r_submix"
   - Output MixPorts (1):
      1. "r_submix output"; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 48000
             channel masks: 0x0003
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (1):
        1. "Remote Submix Out"; {AUDIO_DEVICE_OUT_REMOTE_SUBMIX, @:0}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Input MixPorts (1):
      1. "r_submix input"; 0x0000 (AUDIO_INPUT_FLAG_NONE)
       - Profiles (1):
          1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
             sampling rates: 48000
             channel masks: 0x000c
             AUDIO_ENCAPSULATION_TYPE_NONE
       - Supported devices (1):
        1. Port ID: 14; "Remote Submix In"; {AUDIO_DEVICE_IN_REMOTE_SUBMIX, @:0}
           Encapsulation modes: 0, metadata types: 0
       - maxOpenCount: 1; curOpenCount: 0
       - maxActiveCount: 1; curActiveCount: 0
       - recommendedMuteDurationMs: 0 ms
   - Declared devices (2):
    1. "Remote Submix Out"; {AUDIO_DEVICE_OUT_REMOTE_SUBMIX, @:0}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x0003
           AUDIO_ENCAPSULATION_TYPE_NONE
    2. Port ID: 14; "Remote Submix In"; {AUDIO_DEVICE_IN_REMOTE_SUBMIX, @:0}
       Encapsulation modes: 0, metadata types: 0
     - Profiles (1):
        1. ""; AUDIO_FORMAT_PCM_16_BIT (0x1)
           sampling rates: 48000
           channel masks: 0x000c
           AUDIO_ENCAPSULATION_TYPE_NONE
   - Audio Routes (2):
      1. Mix; Sink: "Remote Submix Out"
         Sources: "r_submix output"
      2. Mix; Sink: "r_submix input"
         Sources: "Remote Submix In"

 Outputs (5):
  1. Port ID: 1; I/O handle: 13; IOProfile name:primary-out; Latency: 80; 0x0002 (AUDIO_OUTPUT_FLAG_PRIMARY)
     AUDIO_FORMAT_PCM_16_BIT; 48000; Channel mask: 0x3
     Devices: {AUDIO_DEVICE_OUT_EARPIECE, @:}
     Global active count: 0
   - Product Strategies (1):
      id 1015: - ActivityCount: 0, StopTime: 64681507915, 
   - Volume Activities (14):
      id 1: - ActivityCount: 0, StopTime: 64681507915, , Volume: -42.000, MuteCount: 00
      id 2: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 3: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 4: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 5: - ActivityCount: 0, StopTime: 0, , Volume: -8.000, MuteCount: 00
      id 6: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 7: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 8: - ActivityCount: 0, StopTime: 0, , Volume: -11.118, MuteCount: 00
      id 9: - ActivityCount: 0, StopTime: 0, , Volume: -6.000, MuteCount: 00
      id 10: - ActivityCount: 0, StopTime: 0, , Volume: -96.000, MuteCount: 01
      id 11: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 12: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 13: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 14: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
  2. Port ID: 5; I/O handle: 21; IOProfile name:deep-buffer; Latency: 80; 0x0008 (AUDIO_OUTPUT_FLAG_DEEP_BUFFER)
     AUDIO_FORMAT_PCM_16_BIT; 48000; Channel mask: 0x3
     Devices: {AUDIO_DEVICE_OUT_SPEAKER, @:}
     Global active count: 0
   - Volume Activities (14):
      id 1: - ActivityCount: 0, StopTime: 0, , Volume: -24.000, MuteCount: 00
      id 2: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 3: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 4: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 5: - ActivityCount: 0, StopTime: 0, , Volume: -8.000, MuteCount: 00
      id 6: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 7: - ActivityCount: 0, StopTime: 0, , Volume: -24.000, MuteCount: 00
      id 8: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 9: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 10: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 01
      id 11: - ActivityCount: 0, StopTime: 0, , Volume: -5.950, MuteCount: 00
      id 12: - ActivityCount: 0, StopTime: 0, , Volume: -5.950, MuteCount: 00
      id 13: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 14: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
  3. Port ID: 7; I/O handle: 29; IOProfile name:fast; Latency: 50; 0x0004 (AUDIO_OUTPUT_FLAG_FAST)
     AUDIO_FORMAT_PCM_16_BIT; 48000; Channel mask: 0x3
     Devices: {AUDIO_DEVICE_OUT_EARPIECE, @:}
     Global active count: 0
   - Product Strategies (1):
      id 1021: - ActivityCount: 0, StopTime: 191372757286, 
   - Volume Activities (14):
      id 1: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 2: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 3: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 4: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 5: - ActivityCount: 0, StopTime: 0, , Volume: -8.000, MuteCount: 00
      id 6: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 7: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 8: - ActivityCount: 0, StopTime: 0, , Volume: -11.118, MuteCount: 00
      id 9: - ActivityCount: 0, StopTime: 191372757286, , Volume: -758.000, MuteCount: 00
      id 10: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 01
      id 11: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 12: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 13: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 14: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
   - AudioTrack clients (1):
      1. Port ID: 24; Session ID: 201; uid 1001; State: Inactive
         AUDIO_FORMAT_PCM_16_BIT; 0; Channel mask: 0x1
         Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VOICE_COMMUNICATION_SIGNALLING Source: AUDIO_SOURCE_INVALID Flags: 0x100 Tags:  }
         Stream: 8; Flags: 00000004; Refcount: 0; InternalMute: No
         DAP Primary Mix: 0x0
  4. Port ID: 41; I/O handle: 93; IOProfile name:a2dp output; Latency: 256; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
     AUDIO_FORMAT_PCM_16_BIT; 44100; Channel mask: 0x3
     Devices: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
     Global active count: 0
   - Volume Activities (14):
      id 1: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 2: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 3: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 4: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 5: - ActivityCount: 0, StopTime: 0, , Volume: -14.000, MuteCount: 00
      id 6: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 7: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 8: - ActivityCount: 0, StopTime: 0, , Volume: -27.412, MuteCount: 00
      id 9: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 10: - ActivityCount: 0, StopTime: 0, , Volume: -96.000, MuteCount: 00
      id 11: - ActivityCount: 0, StopTime: 0, , Volume: -15.300, MuteCount: 00
      id 12: - ActivityCount: 0, StopTime: 0, , Volume: -14.450, MuteCount: 00
      id 13: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 14: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
  5. Port ID: 43; I/O handle: 101; Latency: 256; 0x0000 (AUDIO_OUTPUT_FLAG_NONE)
     AUDIO_FORMAT_PCM_16_BIT; 44100; Channel mask: 0x3
     Devices: {AUDIO_DEVICE_OUT_EARPIECE, @:;AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
     Global active count: 0
   - Volume Activities (14):
      id 1: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 2: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 3: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 4: - ActivityCount: 0, StopTime: 0, , Volume: -758.000, MuteCount: 00
      id 5: - ActivityCount: 0, StopTime: 0, , Volume: -14.000, MuteCount: 00
      id 6: - ActivityCount: 0, StopTime: 0, , Volume: -764.000, MuteCount: 00
      id 7: - ActivityCount: 0, StopTime: 0, , Volume: -42.000, MuteCount: 00
      id 8: - ActivityCount: 0, StopTime: 0, , Volume: -27.412, MuteCount: 00
      id 9: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 10: - ActivityCount: 0, StopTime: 0, , Volume: -96.000, MuteCount: 00
      id 11: - ActivityCount: 0, StopTime: 0, , Volume: -15.300, MuteCount: 00
      id 12: - ActivityCount: 0, StopTime: 0, , Volume: -14.450, MuteCount: 00
      id 13: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00
      id 14: - ActivityCount: 0, StopTime: 0, , Volume: 0.000, MuteCount: 00

 Inputs (0):

 Total Effects CPU: 0.000000 MIPS, Total Effects memory: 0 KB, Max memory used: 166 KB
 - Effects (1):
  1. Effect ID: 11; Attached to I/O handle: 93; Session: 0;
     Music Effect? yes; "DAX3_S_3.7.2.0_r1"; Disabled; Active

 Audio Patches (4):
  1. owner uid 1041; handle  4; af handle 252
     [src  1] Mix Port ID: 1; I/O handle: 13;
     [sink 1] Device Port ID: 2; {AUDIO_DEVICE_OUT_EARPIECE, @:}
  2. owner uid 1041; handle  6; af handle 20
     [src  1] Mix Port ID: 5; I/O handle: 21;
     [sink 1] Device Port ID: 3; {AUDIO_DEVICE_OUT_SPEAKER, @:}
  3. owner uid 1041; handle  8; af handle 244
     [src  1] Mix Port ID: 7; I/O handle: 29;
     [sink 1] Device Port ID: 2; {AUDIO_DEVICE_OUT_EARPIECE, @:}
  4. owner uid 1041; handle 42; af handle 196
     [src  1] Mix Port ID: 41; I/O handle: 93;
     [sink 1] Device Port ID: 39; {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}

 Audio Policy Mix:

 Audio sources (0):
 AllowedCapturePolicies:
 Preferred mixer audio configuration:

Policy Engine dump:
  Product Strategies dump:
    -STRATEGY_REROUTING (id: 9)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 13 stream: AUDIO_STREAM_REROUTING
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VIRTUAL_SOURCE Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags: reserved_internal_strategy }

    -STRATEGY_PATCH (id: 10)
      Selected Device: {AUDIO_DEVICE_OUT_SPEAKER, @:}
       Group: 14 stream: AUDIO_STREAM_PATCH
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags: reserved_internal_strategy }

    -STRATEGY_PHONE (id: 1015)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 1 stream: AUDIO_STREAM_VOICE_CALL
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VOICE_COMMUNICATION Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 7 stream: AUDIO_STREAM_BLUETOOTH_SCO
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_INVALID Flags: 0x4 Tags:  }

    -STRATEGY_SONIFICATION (id: 1016)
      Selected Device: {AUDIO_DEVICE_OUT_SPEAKER, AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 3 stream: AUDIO_STREAM_RING
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION_TELEPHONY_RINGTONE Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 5 stream: AUDIO_STREAM_ALARM
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ALARM Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }

    -STRATEGY_ENFORCED_AUDIBLE (id: 1017)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 8 stream: AUDIO_STREAM_ENFORCED_AUDIBLE
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_INVALID Flags: 0x1 Tags:  }

    -STRATEGY_ACCESSIBILITY (id: 1018)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 11 stream: AUDIO_STREAM_ACCESSIBILITY
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_ACCESSIBILITY Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }

    -STRATEGY_SONIFICATION_RESPECTFUL (id: 1019)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 6 stream: AUDIO_STREAM_NOTIFICATION
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 6 stream: AUDIO_STREAM_NOTIFICATION
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION_EVENT Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }

    -STRATEGY_MEDIA (id: 1020)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 12 stream: AUDIO_STREAM_ASSISTANT
        Attributes: { Content type: AUDIO_CONTENT_TYPE_SPEECH Usage: AUDIO_USAGE_ASSISTANT Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 4 stream: AUDIO_STREAM_MUSIC
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_MEDIA Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 4 stream: AUDIO_STREAM_MUSIC
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_GAME Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 4 stream: AUDIO_STREAM_MUSIC
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANT Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 4 stream: AUDIO_STREAM_MUSIC
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_NAVIGATION_GUIDANCE Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }
       Group: 4 stream: AUDIO_STREAM_MUSIC
        Attributes: { Any }
       Group: 2 stream: AUDIO_STREAM_SYSTEM
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_SONIFICATION Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }

    -STRATEGY_DTMF (id: 1021)
      Selected Device: {AUDIO_DEVICE_OUT_BLUETOOTH_A2DP, @:3C:B0:ED:D9:F5:5E}
       Group: 9 stream: AUDIO_STREAM_DTMF
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VOICE_COMMUNICATION_SIGNALLING Source: AUDIO_SOURCE_INVALID Flags: 0x0 Tags:  }

    -STRATEGY_TRANSMITTED_THROUGH_SPEAKER (id: 1022)
      Selected Device: {AUDIO_DEVICE_OUT_SPEAKER, @:}
       Group: 10 stream: AUDIO_STREAM_TTS
        Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_INVALID Flags: 0x8 Tags:  }

  Device role per product strategy dump:

  Device role per capture preset dump:

  Volume Groups dump:
    -voice_call (id: 1)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_VOICE_CALL(0)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VOICE_COMMUNICATION Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  0, -4200),  ( 33, -2800),  ( 66, -1400),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0, -2400),  ( 33, -1600),  ( 66,  -800),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0, -2700),  ( 33, -1800),  ( 66,  -900),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          01         07         0001 : 07, 0002 : 07, 0010 : 03, 0020 : 07, 0040 : 04, 0080 : 07, 40000000 : 03, 


    -system (id: 2)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_SYSTEM(1)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_SONIFICATION Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -3000),  ( 33, -2600),  ( 66, -2200),  (100, -1800) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -5100),  ( 57, -2800),  ( 71, -2500),  ( 85, -2300),  (100, -2100) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -2400),  ( 33, -1800),  ( 66, -1200),  (100,  -600) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         07         0002 : 00, 0020 : 00, 0080 : 00, 40000000 : 00, 


    -ring (id: 3)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_RING(2)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION_TELEPHONY_RINGTONE Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         07         0002 : 00, 0020 : 00, 0080 : 00, 40000000 : 00, 


    -music (id: 4)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_MUSIC(3)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_MEDIA Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
                    { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_GAME Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
                    { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANT Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
                    { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_NAVIGATION_GUIDANCE Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
                    { Any }
       DEVICE_CATEGORY_HEADSET : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         25         0001 : 25, 0002 : 22, 0020 : 20, 0080 : 16, 0100 : 03, 4000000 : 06, 20000000 : 03, 20000002 : 03, 40000000 : 08, 


    -alarm (id: 5)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_ALARM(4)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ALARM Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  0, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  0, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  0, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          01         07         0002 : 04, 40000000 : 06, 


    -notification (id: 6)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_NOTIFICATION(5)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
                    { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_NOTIFICATION_EVENT Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -4680),  ( 42, -2070),  ( 85,  -540),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -4950),  ( 33, -3350),  ( 66, -1700),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         07         0002 : 00, 0080 : 00, 40000000 : 00, 


    -bluetooth_sco (id: 7)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_BLUETOOTH_SCO(6)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_DEFAULT Flags: 0x4 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  0, -4200),  ( 33, -2800),  ( 66, -1400),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0, -2400),  ( 33, -1600),  ( 66,  -800),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0, -4200),  ( 33, -2800),  ( 66, -1400),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         15         40000000 : 00, 


    -enforced_audible (id: 8)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_ENFORCED_AUDIBLE(7)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_DEFAULT Flags: 0x1 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -3000),  ( 33, -2600),  ( 66, -2200),  (100, -1800) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -3400),  ( 71, -2400),  (100, -2000) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -2400),  ( 33, -1800),  ( 66, -1200),  (100,  -600) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         07         0002 : 05, 0020 : 05, 0080 : 05, 40000000 : 05, 


    -dtmf (id: 9)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_DTMF(8)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VOICE_COMMUNICATION_SIGNALLING Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -3000),  ( 33, -2600),  ( 66, -2200),  (100, -1800) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -4000),  ( 71, -2400),  (100, -1400) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -2400),  ( 33, -1800),  ( 66, -1200),  (100,  -600) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -2100),  (100, -1000) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         15         0001 : 00, 0002 : 00, 0010 : 00, 0020 : 00, 0040 : 00, 0080 : 00, 40000000 : 00, 


    -tts (id: 10)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_TTS(9)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_DEFAULT Flags: 0x8 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  0, -9600),  (100, -9600) }
       DEVICE_CATEGORY_SPEAKER : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0, -9600),  (100, -9600) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  0, -9600),  (100, -9600) }
       DEVICE_CATEGORY_HEARING_AID : { (  0, -9600),  (100, -9600) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         15         0001 : 15, 0002 : 02, 0020 : 12, 0080 : 10, 0100 : 02, 4000000 : 04, 20000000 : 02, 20000002 : 02, 40000000 : 05, 


    -accessibility (id: 11)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_ACCESSIBILITY(10)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_ASSISTANCE_ACCESSIBILITY Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  0, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  0, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  0, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          01         15         0001 : 15, 0002 : 13, 0020 : 12, 0080 : 10, 0100 : 02, 4000000 : 04, 20000000 : 02, 20000002 : 02, 40000000 : 06, 


    -assistant (id: 12)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_ASSISTANT(11)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_SPEECH Usage: AUDIO_USAGE_ASSISTANT Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags:  }
       DEVICE_CATEGORY_HEADSET : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  1, -5800),  ( 20, -4000),  ( 60, -1700),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  1, -12700),  ( 20, -8000),  ( 60, -4000),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         15         0001 : 15, 0002 : 13, 0020 : 12, 0080 : 10, 0100 : 02, 4000000 : 04, 20000000 : 02, 20000002 : 02, 40000000 : 05, 


    -AUDIO_STREAM_REROUTING (id: 13)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_REROUTING(12)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_VIRTUAL_SOURCE Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags: reserved_internal_strategy }
       DEVICE_CATEGORY_HEADSET : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  0,     0),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         01         40000000 : 00, 


    -AUDIO_STREAM_PATCH (id: 14)
      Volume Curves Streams/Attributes, Curve points Streams for device category (index, attenuation in millibel)
       Streams: AUDIO_STREAM_PATCH(13)  
       Attributes: { Content type: AUDIO_CONTENT_TYPE_UNKNOWN Usage: AUDIO_USAGE_UNKNOWN Source: AUDIO_SOURCE_DEFAULT Flags: 0x0 Tags: reserved_internal_strategy }
       DEVICE_CATEGORY_HEADSET : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_SPEAKER : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_EARPIECE : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_EXT_MEDIA : { (  0,     0),  (100,     0) }
       DEVICE_CATEGORY_HEARING_AID : { (  0,     0),  (100,     0) }
        Can be muted  Index Min  Index Max  Index Cur [device : index]...
        true          00         01         40000000 : 00, 


Absolute volume devices with driving streams:
   - device type: 0x20000002, driving stream 4
   - device type: 0x20000000, driving stream 4
   - device type: 0x80, driving stream 4
   - device type: 0x20000001, driving stream 4
   - device type: 0x8000000, driving stream 4
Allow playback capture log:
  Package manager errors: 0
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.providers.settings
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.keychain
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.dynsystem
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.server.telecom
  - uid= 1000, allowPlaybackCapture=true , packageName=org.lineageos.dap
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.location.fused
  - uid= 1000, allowPlaybackCapture=true , packageName=org.lineageos.setupwizard
  - uid= 1000, allowPlaybackCapture=true , packageName=org.lineageos.lineagesettings
  - uid= 1000, allowPlaybackCapture=true , packageName=lineageos.platform
  - uid= 1000, allowPlaybackCapture=true , packageName=org.lineageos.lineageparts
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.settings
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.localtransport
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.DeviceAsWebcam
  - uid= 1000, allowPlaybackCapture=true , packageName=com.android.inputdevices
  - uid= 1000, allowPlaybackCapture=true , packageName=android
  - uid= 1000, allowPlaybackCapture=true , packageName=org.lineageos.settings.doze
  - uid= 1001, allowPlaybackCapture=true , packageName=com.android.ons
  - uid= 1001, allowPlaybackCapture=true , packageName=com.android.providers.telephony
  - uid= 1001, allowPlaybackCapture=true , packageName=com.android.mms.service
  - uid= 1001, allowPlaybackCapture=true , packageName=com.android.phone
  - uid= 1001, allowPlaybackCapture=true , packageName=com.android.stk
Spatializer no supportted on this device

IAudioPolicyService binder call profile
2 setDeviceConnectionState n=15 ave=129.704 std=114.814 min=10.3816 max=395.721
5 setPhoneState n=4 ave=410.348 std=135.091 min=276.358 max=578.37
6 setForceUse n=26 ave=0.527281 std=1.4017 min=0.052884 max=7.18319
8 getOutput n=2 ave=0.674171 std=0.116972 min=0.591459 max=0.756883
17 setDeviceAbsoluteVolumeEnabled n=28 ave=12.1124 std=61.0839 min=0.134614 max=323.766
18 initStreamVolume n=11 ave=0.0863066 std=0.00730536 min=0.079538 max=0.105153
19 setStreamVolumeIndex n=1597 ave=1.3658 std=1.70498 min=0.382614 max=40.2653
21 setVolumeIndexForAttributes n=95 ave=1.04372 std=0.763678 min=0.208961 max=5.76088
23 getMaxVolumeIndexForAttributes n=17 ave=0.0663764 std=0.038692 min=0.032499 max=0.147729
24 getMinVolumeIndexForAttributes n=17 ave=0.0541842 std=0.0234059 min=0.02946 max=0.09973
26 getDevicesForAttributes n=376 ave=11.4187 std=52.9045 min=0.173191 max=520.328
32 isStreamActive n=15 ave=1.60879 std=2.84226 min=0.077653 max=10.2637
33 isStreamActiveRemotely n=4 ave=1.13864 std=1.60345 min=0.088613 max=3.47673
40 setSupportedSystemUsages n=1 ave=0.079152 min=0.079152 max=0.079152
42 getOffloadSupport n=2 ave=0.13769 std=0.0297536 min=0.116651 max=0.158729
44 listAudioPorts n=526 ave=21.3529 std=59.2929 min=0.043152 max=465.784
49 listAudioPatches n=520 ave=11.6301 std=48.7957 min=0.034191 max=358.385
51 registerClient n=20 ave=0.343114 std=0.652572 min=0.105498 max=2.96577
52 setAudioPortCallbacksEnabled n=38 ave=0.0552891 std=0.0213519 min=0.023537 max=0.120614
53 setAudioVolumeGroupCallbacksEnabled n=20 ave=0.0526946 std=0.0431353 min=0.01596 max=0.211845
57 registerPolicyMixes n=1 ave=0.139229 min=0.139229 max=0.139229
66 setMasterMono n=2 ave=0.061633 std=0.0130815 min=0.052383 max=0.070883
68 getStreamVolumeDB n=11 ave=0.111016 std=0.0418578 min=0.06023 max=0.191999
71 getHwOffloadFormatsSupportedForBluetoothMedia n=3 ave=39.1782 std=67.6268 min=0.128998 max=117.267
73 setAssistantServicesUids n=3 ave=0.0696143 std=0.00503586 min=0.063999 max=0.07373
74 setActiveAssistantServicesUids n=2 ave=0.05296 std=0.0172435 min=0.040767 max=0.065153
75 setA11yServicesUids n=11 ave=0.365358 std=0.97176 min=0.047191 max=3.29469
76 setCurrentImeUid n=1 ave=0.083691 min=0.083691 max=0.083691
77 isHapticPlaybackSupported n=1 ave=0.112421 min=0.112421 max=0.112421
80 listAudioProductStrategies n=9 ave=6.72889 std=17.0495 min=0.255806 max=52.1185
81 getProductStrategyFromAudioAttributes n=1 ave=0.113498 min=0.113498 max=0.113498
82 listAudioVolumeGroups n=1 ave=0.345421 min=0.345421 max=0.345421
84 setRttEnabled n=2 ave=0.0398065 std=0.0087561 min=0.033615 max=0.045998
85 isCallScreenModeSupported n=1 ave=0.034923 min=0.034923 max=0.034923
86 setDevicesRoleForStrategy n=4 ave=157.352 std=62.0018 min=101.107 max=219.479
88 clearDevicesRoleForStrategy n=4 ave=115.111 std=128.2 min=8.51408 max=272.653
95 registerSoundTriggerCaptureStateListener n=1 ave=0.231691 min=0.231691 max=0.231691
1598311760 dump n=3 ave=11.2159 std=7.04348 min=6.19477 max=19.2674
1598968902 getInterfaceDescriptor n=6 ave=0.0562482 std=0.013217 min=0.042921 max=0.072113

============================================================
17 AUDIO FLINGER
============================================================
Libraries NOT loaded:
Libraries loaded:
 Library dap
  path: /vendor/lib/soundfx/libswdap.so
  (no effects)
 Library pre_processing
  path: /vendor/lib/soundfx/libaudiopreprocessing.so
  Noise Suppression / The Android Open Source Project
    UUID: c06c8400-8e06-11e0-9cb6-0002a5d5c51b
    TYPE: 58b4b260-8e06-11e0-aa8e-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000203
  Acoustic Echo Canceler / The Android Open Source Project
    UUID: bb392ec0-8d4d-11e0-a896-0002a5d5c51b
    TYPE: 7b491460-8d4d-11e0-bd61-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000203
  Automatic Gain Control / The Android Open Source Project
    UUID: aa8130e0-66fc-11e0-bad0-0002a5d5c51b
    TYPE: 0a8abfe0-654c-11e0-ba26-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000203
 Library dynamics_processing
  path: /vendor/lib/soundfx/libdynproc.so
  Dynamics Processing / The Android Open Source Project
    UUID: e0e6539b-1781-7261-676f-6d7573696340
    TYPE: 7261676f-6d75-7369-6364-28e2fd3ac39e
    apiVersion: 00020000
    flags: 00000050
 Library loudness_enhancer
  path: /vendor/lib/soundfx/libldnhncr.so
  Loudness Enhancer / The Android Open Source Project
    UUID: fa415329-2034-4bea-b5dc-5b381c8d1e2c
    TYPE: fe3199be-aed0-413f-87bb-11260eb63cf1
    apiVersion: 00020000
    flags: 00000008
 Library soundalive_sec
  path: /vendor/lib/soundfx/libaudiosaplus_sec.so
  (no effects)
 Library myspace
  path: /vendor/lib/soundfx/libmyspace.so
  (no effects)
 Library mysound
  path: /vendor/lib/soundfx/libmysound.so
  (no effects)
 Library downmix
  path: /vendor/lib/soundfx/libdownmix.so
  Multichannel Downmix To Stereo / The Android Open Source Project
    UUID: 93f04452-e4fe-41cc-91f9-e475b6d1d69f
    TYPE: 381e49cc-a858-4aa2-87f6-e8388e7601b2
    apiVersion: 00020000
    flags: 00000008
 Library visualizer
  path: /vendor/lib/soundfx/libvisualizer.so
  Visualizer / The Android Open Source Project
    UUID: d069d9e0-8329-11df-9168-0002a5d5c51b
    TYPE: e46b26a0-dddd-11db-8afd-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000008
 Library reverb
  path: /vendor/lib/soundfx/libreverbwrapper.so
  Insert Preset Reverb / NXP Software Ltd.
    UUID: 172cdf00-a3bc-11df-a72f-0002a5d5c51b
    TYPE: 47382d60-ddd8-11db-bf3a-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000048
  Auxiliary Preset Reverb / NXP Software Ltd.
    UUID: f29a1400-a3bb-11df-8ddc-0002a5d5c51b
    TYPE: 47382d60-ddd8-11db-bf3a-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000001
  Insert Environmental Reverb / NXP Software Ltd.
    UUID: c7a511a0-a3bb-11df-860e-0002a5d5c51b
    TYPE: c2e5d5f0-94bd-4763-9cac-4e234d06839e
    apiVersion: 00020000
    flags: 00000048
  Auxiliary Environmental Reverb / NXP Software Ltd.
    UUID: 4a387fc0-8ab3-11df-8bad-0002a5d5c51b
    TYPE: c2e5d5f0-94bd-4763-9cac-4e234d06839e
    apiVersion: 00020000
    flags: 00000001
 Library bundle
  path: /vendor/lib/soundfx/libbundlewrapper.so
  Volume / NXP Software Ltd.
    UUID: 119341a0-8469-11df-81f9-0002a5d5c51b
    TYPE: 09e8ede0-ddde-11db-b4f6-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000050
  Equalizer / NXP Software Ltd.
    UUID: ce772f20-847d-11df-bb17-0002a5d5c51b
    TYPE: 0bed4300-ddd6-11db-8f34-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000048
  Virtualizer / NXP Software Ltd.
    UUID: 1d4033c0-8557-11df-9f2d-0002a5d5c51b
    TYPE: 37cc2c00-dddd-11db-8577-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000250
  Dynamic Bass Boost / NXP Software Ltd.
    UUID: 8631f300-72e2-11df-b57e-0002a5d5c51b
    TYPE: 0634f220-ddd4-11db-a0fc-0002a5d5c51b
    apiVersion: 00020000
    flags: 00000248
 Library offload
  path: /vendor/lib/soundfx/libaudioeffectoffload.so
  Offload_VolumeMonitor / Samsung
    UUID: 052a63b0-f95a-11e9-8f0b-362b9e155667
    TYPE: f15b944b-0202-451e-a6ff-c61f11beda02
    apiVersion: 00020000
    flags: 00020210
 Library proxy
  path: /vendor/lib/soundfx/libeffectproxy.so
  DAX3_S_3.7.2.0_r1 / Dolby Laboratories
    UUID: 9d4921da-8225-4f29-aefa-39537a04bcaa
    TYPE: 46d279d9-9be7-453d-9d7c-ef937f675587
    apiVersion: 00020000
    flags: 01440288
  MySpace / Samsung
    UUID: 1c91fca0-664a-11e4-b8c2-0002a5d5c51b
    TYPE: b6c0ace0-655a-11e4-9801-0002a5d5c51b
    apiVersion: 00020000
    flags: 00400210
  MySound / Samsung
    UUID: 37155c20-50bb-11e3-9fac-0002a5d5c51b
    TYPE: d2bc05e0-50b0-11e2-bcfd-0800200c9a66
    apiVersion: 00020000
    flags: 00400200
  SoundAlivePlus / Samsung
    UUID: 05227ea0-50bb-11e3-ac69-0002a5d5c51b
    TYPE: c4da1d1f-7cdf-42e2-ba60-efc7eb3508a3
    apiVersion: 00020000
    flags: 00400240
XML effect configuration loaded successfully.
Client Allocators:
Client: 5094
Primary: 
Dedicated Pool Allocator Dump:
  HeapID    Size  Offset   Order   Name
       8   36864       0       0   Track ID: 66
Secondary: 
Primary: 
Large Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Secondary: 
Small Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Client: 5515
Primary: 
Dedicated Pool Allocator Dump:
  HeapID    Size  Offset   Order   Name
      10    4096       0       0   Effect ID: 11 Session ID: 0 

Secondary: 
Primary: 
Large Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Secondary: 
Small Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Client: 5539
Primary: 
Dedicated Pool Allocator Dump:
  HeapID    Size  Offset   Order   Name
       9    4096       0       0   Track ID: 58
Secondary: 
Primary: 
Large Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Secondary: 
Small Shared Allocator Dump:
  HeapID    Size  Offset   Order   Name
Notification Clients:
   pid    uid  name
  4876   1041  audioserver
  4945   1013  media
  5094   1000  android.uid.system
  5515   1000  android.uid.system
  5539   1001  android.uid.phone
  6232  10156  org.lineageos.audiofx
  6413  10233  org.telegram.messenger.web
 11803  10229  com.nothing.smartcenter
 12042  10211  com.google.android.tts
 12941  10238  app.revanced.android.youtube
 13384  10131  org.lineageos.twelve
 13385  10225  app.rbmain.a
 13390  10218  com.google.android.youtube
 13392  10189  ir.nasim
Global session refs:
  session  cnt     pid    uid  name
      201    1    5539   1001  android.uid.phone
      273    1   11803  10229  com.nothing.smartcenter
      369    1    5094   1000  android.uid.system
Hardware status: 0
Vibrator infos(size=1):
  - AudioVibratorInfo{id: 0, resonantFrequency: nan, qFactor: nan, maxAmplitude: nan}
Bluetooth latency modes are enabled

Output thread 0x738b673880, name AudioOut_D, tid 5056, type 0 (MIXER):
  I/O handle: 13
  Standby: yes
  Sample rate: 48000 Hz
  HAL frame count: 960
  HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  HAL buffer size: 3840 bytes
  Channel count: 2
  Channel mask: 0x00000003 (front-left, front-right)
  Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  Processing frame size: 4 bytes
  Pending config events: none
  Output devices: 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
  Input device: 0 (AUDIO_DEVICE_NONE)
  Audio source: 0 (AUDIO_SOURCE_DEFAULT)
  Timestamp stats: n=179 disc=2 cold=0 nRdy=0 err=14 rate=0.999999 jitterMs(ave=0.711428 std=9.64186 min=-0.031654 max=130.875) localSR(48000.1, 3.77667e-10) correctedJitterMs(ave=0.884032 std=2.57606 min=-0.0197183 max=19.7704)
  Timestamp corrected: no
  Last write occurred (msecs): 147613
  Master volume: 1.000000
  Master mute: off
  Mixer channel Mask: 0x3 (front-left, front-right)
  Normal frame count: 960
  Total writes: 188
  Delayed writes: 0
  Blocked in write: no
  Suspend count: 0
  Fast track availMask=0xfe
  Standby delay ns=3000000000
  AudioStreamOut: 0x7160d5d530 flags 0x2 (AUDIO_OUTPUT_FLAG_PRIMARY)
  Frames written: 180480
  Suspended frames: 0
  Hal stream dump:

Audio Stream Out(2)::dump
	Mutex: locked
	output devices 1
	output flgas: 2
	output sample rate: 48000
	output channel mask: 3
	output format: 1
	output audio usage: 0
	output standby state: 0
	output backend_mode: 0
      Signal power history (resolution: 1000.0 ms):
       08-19 14:49:31.943: [  -39.8 ] sum(10.0)
      Signal power history (resolution: 50.0 ms):
       08-19 14:49:31.943: [  -30.3  -33.6  -33.5  -37.7  -42.2  -46.1  -50.2  -54.5  -58.4  -62.3
       08-19 14:49:32.445:    -66.6  -70.7  -75.5  -79.9  -87.2 ] sum(10.0)

    -24.6 -|
    -30.3 -|*
    -36.0 -| ***
    -41.7 -|    *
    -47.4 -|     **
    -53.0 -|       *
    -58.7 -|        *
    -64.4 -|         **
    -70.1 -|           *
    -75.8 -|            *
    -81.5 -|             *
    -87.2 -|              *
    -92.8 -|
    -98.5 -|
           |_______________


  Thread throttle time (msecs): 0
  AudioMixer tracks: 
  Master mono: off
  Master balance: 0.000000 (balance 0 channelCount 2 volumes: 1 1)
  No FastMixer
Bluetooth latency modes are not enabled
HAL does not support Bluetooth latency modes
Supported latency modes: { }
  Stream volumes in dB: 0:-42, 1:-inf, 2:-inf, 3:-inf, 4:-8, 5:-inf, 6:-42, 7:-11, 8:-6, 9:-96, 10:0, 11:0, 12:0, 13:0, 14:0
  Normal mixer raw underrun counters: partial=0 empty=0
  1 Tracks of which 0 are active
    Type     Id Active Client Session Port Id S  Flags   Format Chn mask  SRate ST Usg CT  G db  L dB  R dB  VS dB  PortVol dB   Server FrmCnt  FrmRdy F Underruns  Flushed BitPerfect InternalMute   Latency
             65     no   4876       0       0 I  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   2652       0 I         0        0      false        false       new
  1 Effect Chains
    1 effects for session 0
	In buffer                   Out buffer                     Active tracks:
	0x7270d51020 -> 0x738bcb9000   0x738bcb9000 -> 0x7270d51020   0
	Effect ID 11:
		Session State Registered Internal Enabled Suspended:
		00000   000   y          n        n       n
		Descriptor:
		- UUID: 9d4921da-8225-4f29-aefa-39537a04bcaa
		- TYPE: 46d279d9-9be7-453d-9d7c-ef937f675587
		- apiVersion: 00000000
		- flags: 01440288 (conn. mode: insert, insert pref: first, volume mgmt: requires indication, device indication: requires updates, input mode: not set, output mode: not set, mode indication: required, offloadable)
		- name: DAX3_S_3.7.2.0_r1
		- implementor: Dolby Laboratories
		1 Clients:
			  Pid Priority Ctrl Locked client server
			 5515        0  yes    yes      0      0
		Status Engine:
		000    0x7190d53e40
		- data: float
		- Input configuration:
			Buffer     Frames  Smp rate Channels Format
			0x738bcb9000 00960   48000    00000003      5 (AUDIO_FORMAT_PCM_FLOAT)
		- Output configuration:
			Buffer     Frames  Smp rate Channels Format
			0x738bcb9000 00960   48000    00000003      5 (AUDIO_FORMAT_PCM_FLOAT)
		- HAL buffers:
			In(0x7270d51020 -> 0x738bcb9000) InConversion(nullptr) Out(0x738bcb9000 -> 0x7270d51020) OutConversion(nullptr)
	Effect ID 11 HAL dump:
  Local log:
   08-19 14:48:47.259 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x2 (AUDIO_DEVICE_OUT_SPEAKER)
   08-19 14:49:25.628 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x2 (AUDIO_DEVICE_OUT_SPEAKER) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:29.372 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:29.497 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:29.823 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:29.943 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:30.673 removeTrack_l (0x72d0d4afb0)          56     no   4876       0       0 T  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   2652       0 I         0        0      false        false       new
   08-19 14:49:30.782 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:31.748 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:49:31.766 AT::add       (0x72d0d4cff0)          59     no   5094     209      25 A  0x000 00000001 00000003  48000  0   2  1  -inf     0     0     0          -42 00000000  24000       0 f         0        0      false        false       new
   08-19 14:49:32.764 AT::remove    (0x72d0d4cff0)          59     no   5094     209      25 S  0x600 00000001 00000003  48000  0   2  1  -8.7     0     0     0          -42 00008CA0  24000       0 f         0        0      false        false   85.77 k
   08-19 14:49:32.821 removeTrack_l (0x72d0d4cff0)          59     no   5094     209      25 T  0x600 00000001 00000003  48000  0   2  1  -8.7     0     0     0          -42 00008CA0  24000       0 f         0        0      false        false   85.77 k
   08-19 14:49:33.071 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:20.971 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:22.449 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:22.540 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:22.751 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:22.856 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:23.587 removeTrack_l (0x72d0d47c30)          61     no   4876       0       0 T  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   2652       0 I         0        0      false        false       new
   08-19 14:51:23.688 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:37.449 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:37.629 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:37.970 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.236 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.406 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.838 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)

Output thread 0x738b5a5880, name AudioOut_15, tid 5061, type 0 (MIXER):
  I/O handle: 21
  Standby: yes
  Sample rate: 48000 Hz
  HAL frame count: 960
  HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  HAL buffer size: 3840 bytes
  Channel count: 2
  Channel mask: 0x00000003 (front-left, front-right)
  Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  Processing frame size: 4 bytes
  Pending config events: none
  Output devices: 0x2 (AUDIO_DEVICE_OUT_SPEAKER)
  Input device: 0 (AUDIO_DEVICE_NONE)
  Audio source: 0 (AUDIO_SOURCE_DEFAULT)
  Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
  Timestamp corrected: no
  Master volume: 1.000000
  Master mute: off
  Mixer channel Mask: 0x3 (front-left, front-right)
  Normal frame count: 960
  Total writes: 0
  Delayed writes: 0
  Blocked in write: no
  Suspend count: 0
  Fast track availMask=0xfe
  Standby delay ns=3000000000
  AudioStreamOut: 0x7160d5dd50 flags 0x8 (AUDIO_OUTPUT_FLAG_DEEP_BUFFER)
  Frames written: 0
  Suspended frames: 0
  Hal stream dump:

Audio Stream Out(8)::dump
	Mutex: locked
	output devices 2
	output flgas: 8
	output sample rate: 48000
	output channel mask: 3
	output format: 1
	output audio usage: 0
	output standby state: 0
	output backend_mode: 0
      Signal power history: (none)
      Signal power history: (none)
  Thread throttle time (msecs): 0
  AudioMixer tracks: 
  Master mono: off
  Master balance: 0.000000 (balance 0 channelCount 2 volumes: 1 1)
  No FastMixer
Bluetooth latency modes are not enabled
HAL does not support Bluetooth latency modes
Supported latency modes: { }
  Stream volumes in dB: 0:-24, 1:-inf, 2:-inf, 3:-inf, 4:-8, 5:-inf, 6:-24, 7:-inf, 8:0, 9:0, 10:-5.9, 11:-5.9, 12:0, 13:0, 14:0
  Normal mixer raw underrun counters: partial=0 empty=0
  0 Tracks
  0 Effect Chains
  Local log:
   08-19 14:48:47.345 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x2 (AUDIO_DEVICE_OUT_SPEAKER)

Output thread 0x738b393880, name AudioOut_1D, tid 5063, type 0 (MIXER):
  I/O handle: 29
  Standby: yes
  Sample rate: 48000 Hz
  HAL frame count: 240
  HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  HAL buffer size: 960 bytes
  Channel count: 2
  Channel mask: 0x00000003 (front-left, front-right)
  Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
  Processing frame size: 8 bytes
  Pending config events: none
  Output devices: 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
  Input device: 0 (AUDIO_DEVICE_NONE)
  Audio source: 0 (AUDIO_SOURCE_DEFAULT)
  Timestamp stats: n=548 disc=0 cold=0 nRdy=0 err=3 rate=0.99999 jitterMs(ave=0.000107225 std=0.0864645 min=-1.39492 max=1.28027) localSR(47999.8, 2.53706e-09) correctedJitterMs(ave=0.000191565 std=0.00819177 min=-0.0221803 max=0.0511023)
  Timestamp corrected: no
  Last write occurred (msecs): 20839
  Process time ms stats: ave=0.197342 std=0.59505 min=0.052923 max=4.52196
  Hal write jitter ms stats: ave=0.0231365 std=0.368389 min=-1.47265 max=3.163
  Threadloop write latency stats: ave=53.8728 std=3.83899 min=46.0888 max=74.179
  Monopipe write pipe depth stats: ave=1445.08 std=44.8665 min=1440 max=1920
  Master volume: 1.000000
  Master mute: off
  Mixer channel Mask: 0x3 (front-left, front-right)
  Normal frame count: 960
  Total writes: 400
  Delayed writes: 0
  Blocked in write: no
  Suspend count: 0
  Fast track availMask=0xfa
  Standby delay ns=3000000000
  AudioStreamOut: 0x7160d5e570 flags 0x4 (AUDIO_OUTPUT_FLAG_FAST)
  Frames written: 384000
  Suspended frames: 0
  PipeSink frames written: 384000
  Hal stream dump:

Audio Stream Out(4)::dump
	Mutex: locked
	output devices 1
	output flgas: 4
	output sample rate: 48000
	output channel mask: 3
	output format: 1
	output audio usage: 0
	output standby state: 0
	output backend_mode: 0
      Signal power history (resolution: 1000.0 ms):
       08-19 14:51:34.470: [  -31.7  -31.7  -31.7  -23.0 ] sum(28.3)
      Signal power history (resolution: 50.0 ms):
       08-19 14:51:34.470: [  -28.7  -28.8  -28.7  -28.7  -28.8  -28.7  -28.8  -28.7  -28.7  -28.8
       08-19 14:51:34.970:    -47.7 ] sum(18.1)
       08-19 14:51:35.470: [  -28.7  -28.8  -28.7  -28.7  -28.8  -28.7  -28.8  -28.7  -28.7  -28.8
       08-19 14:51:35.970:    -43.9 ] sum(18.1)
       08-19 14:51:36.470: [  -28.7  -28.8  -28.7  -28.7  -28.8  -28.7  -28.8  -28.7  -28.7  -28.8
       08-19 14:51:36.970:    -47.7 ] sum(18.1)
       08-19 14:51:37.470: [  -20.0  -20.0  -20.0  -20.0  -20.0  -19.9  -20.0  -20.0  -20.0  -20.0
       08-19 14:51:37.970:    -35.2 ] sum(26.8)

    -17.2 -|           |           |           |
    -19.9 -|           |           |           |**********
    -22.7 -|           |           |           |
    -25.5 -|           |           |           |
    -28.3 -|********** |********** |********** |
    -31.0 -|           |           |           |
    -33.8 -|           |           |           |          *
    -36.6 -|           |           |           |
    -39.4 -|           |           |           |
    -42.1 -|           |           |           |
    -44.9 -|           |          *|           |
    -47.7 -|          *|           |          *|
    -50.5 -|           |           |           |
    -53.2 -|           |           |           |
           |_______________________________________________


  Thread throttle time (msecs): 0
  AudioMixer tracks: 
  Master mono: off
  Master balance: 0.000000 (0.000000)
  FastMixer thread 0x738b20e7c0 tid=5062  FastMixer command=COLD_IDLE writeSequence=3202 framesWritten=384240
            numTracks=1 writeErrors=0 underruns=0 overruns=0
            sampleRate=48000 frameCount=240 measuredWarmup=36.3 ms, warmupCycles=5
            mixPeriod=5.00 ms latency=10.00 ms
  FastMixer Timestamp stats: n=1596 disc=0 cold=0 nRdy=0 err=0 rate=0.999985 jitterMs(ave=4.55092e-05 std=0.08283 min=-1.38762 max=1.35515) localSR(48000.9, 5.055e-09) correctedJitterMs(ave=3.28013e-05 std=0.008663 min=-0.021654 max=0.028154)
  Simple moving statistics over last 8.0 seconds:
    wall clock time in ms per mix cycle:
      mean=5.00 min=2.63 max=7.59 stddev=0.24
    raw CPU load in us per mix cycle:
      mean=242 min=0 max=1077 stddev=130
  Distribution of mix cycle times in ms for the tails (> ~3 stddev outliers):
    left tail: mean=2.63 min=2.63 max=2.63 stddev=0.00
    right tail: mean=7.59 min=7.59 max=7.59 stddev=0.00
  Fast tracks: sMaxFastTracks=8 activeMask=0x1
  Index Active Full Partial Empty  Recent Ready    Written
      0    yes  572       0     0    full  1200     382800
      1     no  798       0   200   empty     0     191520
      2     no    0       0     0    full     0          0
      3     no    0       0     0    full     0          0
      4     no    0       0     0    full     0          0
      5     no    0       0     0    full     0          0
      6     no    0       0     0    full     0          0
      7     no    0       0     0    full     0          0
Bluetooth latency modes are not enabled
HAL does not support Bluetooth latency modes
Supported latency modes: { }
  Stream volumes in dB: 0:-42, 1:-inf, 2:-inf, 3:-inf, 4:-8, 5:-inf, 6:-42, 7:-11, 8:-inf, 9:0, 10:0, 11:0, 12:0, 13:0, 14:0
  Normal mixer raw underrun counters: partial=0 empty=0
  1 Tracks of which 0 are active
    Type     Id Active Client Session Port Id S  Flags   Format Chn mask  SRate ST Usg CT  G db  L dB  R dB  VS dB  PortVol dB   Server FrmCnt  FrmRdy F Underruns  Flushed BitPerfect InternalMute   Latency
    F2       58     no   5539     201      24 I  0x004 00000001 00000001  48000  8   3  0  -inf   -10   -10     0            0 00000000    240       0 I         0        0      false        false       new
  0 Effect Chains
  Local log:
   08-19 14:48:47.402 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x2 (AUDIO_DEVICE_OUT_SPEAKER)
   08-19 14:49:30.870 removeTrack_l (0x72d0d48f90) F1       57     no   5094     193      23 T  0x200 00000001 00000001  48000  8   3  0  -inf   -10   -10     0         -inf 00000000    240       0 I         0        0      false        false       new
   08-19 14:51:34.345 removeTrack_l (0x72d0d49c70) F1       62     no   5094     305      34 T  0x200 00000001 00000001  48000  8   3  0  -inf   -10   -10     0            0 00000000    240       0 I         0        0      false        false       new
   08-19 14:51:34.401 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x2 (AUDIO_DEVICE_OUT_SPEAKER) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:34.416 AT::add       (0x72d0d49c70) F1       63     no   5094     361      35 A  0x000 00000001 00000001  48000  8   3  0  -inf   -10   -10     0            0 00000000    240       0 f         0        0      false        false       new
   08-19 14:51:37.496 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.016 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.296 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:38.476 CFG_EVENT_CREATE_AUDIO_PATCH: old device 0x1 (AUDIO_DEVICE_OUT_EARPIECE) new device 0x1 (AUDIO_DEVICE_OUT_EARPIECE)
   08-19 14:51:39.457 AT::remove    (0x72d0d49c70) F1       63     no   5094     361      35 A  0x00D 00000001 00000001  48000  8   3  0  -inf   -10   -10     0            0 0002EC20    240       0 f     48000        0      false        false   10.00 t
   08-19 14:51:41.450 removeTrack_l (0x72d0d49c70) F1       63     no   5094     361      35 T  0x20D 00000001 00000001  48000  8   3  0  -inf   -10   -10     0            0 0002EC20    240       0 f     48000        0      false        false   10.00 t
   08-19 14:51:42.443 threadLoop_standby: framesWritten:384000  suspendedFrames:0  monoPipeWritten:384000  monoPipeLeft:960
   08-19 14:51:42.443 threadLoop_standby: BOOTTIME offset 0
ExtendedTimestamp[0]  position: 0  time: -1
ExtendedTimestamp[1]  position: 384000  time: 194339125014
ExtendedTimestamp[2]  position: 382320  time: 194356261822
ExtendedTimestamp[3]  position: 384000  time: 194339125014
ExtendedTimestamp[4]  position: 381840  time: 194346284899

Output thread 0x7387acc880, name AudioOut_5D, tid 14038, type 0 (MIXER):
  I/O handle: 93
  Standby: yes
  Sample rate: 44100 Hz
  HAL frame count: 1014
  HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  HAL buffer size: 4056 bytes
  Channel count: 2
  Channel mask: 0x00000003 (front-left, front-right)
  Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
  Processing frame size: 8 bytes
  Pending config events: none
  Output devices: 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP)
  Input device: 0 (AUDIO_DEVICE_NONE)
  Audio source: 0 (AUDIO_SOURCE_DEFAULT)
  Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
  Timestamp corrected: no
  Master volume: 1.000000
  Master mute: off
  Mixer channel Mask: 0x3 (front-left, front-right)
  Normal frame count: 1024
  Total writes: 0
  Delayed writes: 0
  Blocked in write: no
  Suspend count: 1
  Fast track availMask=0xfe
  Standby delay ns=3000000000
  AudioStreamOut: 0x7160d67440 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
  Frames written: 0
  Suspended frames: 0
  PipeSink frames written: 0
  Hal stream dump:
      Signal power history: (none)
      Signal power history: (none)
  Thread throttle time (msecs): 0
  AudioMixer tracks: 
  Master mono: off
  Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=14037  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
            numTracks=0 writeErrors=0 underruns=0 overruns=0
            sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
            mixPeriod=nan ms latency=0.00 ms
  FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
  No FastMixer statistics available currently
  Fast tracks: sMaxFastTracks=8 activeMask=0
  Index Active Full Partial Empty  Recent Ready    Written
      0     no    0       0     0    full     0          0
      1     no    0       0     0    full     0          0
      2     no    0       0     0    full     0          0
      3     no    0       0     0    full     0          0
      4     no    0       0     0    full     0          0
      5     no    0       0     0    full     0          0
      6     no    0       0     0    full     0          0
      7     no    0       0     0    full     0          0
Bluetooth latency modes are not enabled
HAL does not support Bluetooth latency modes
Supported latency modes: { }
  Stream volumes in dB: 0:-42, 1:-inf, 2:-inf, 3:-inf, 4:-14, 5:-inf, 6:-42, 7:-27, 8:0, 9:-96, 10:-15, 11:-14, 12:0, 13:0, 14:0
  Normal mixer raw underrun counters: partial=0 empty=0
  2 Tracks of which 0 are active
    Type     Id Active Client Session Port Id S  Flags   Format Chn mask  SRate ST Usg CT  G db  L dB  R dB  VS dB  PortVol dB   Server FrmCnt  FrmRdy F Underruns  Flushed BitPerfect InternalMute   Latency
             64     no   4876       0       0 I  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   3072       0 I         0        0      false        false       new
             66     no   5094     369      44 I  0x000 00000001 00000001  44100  8   3  0  -inf   -10   -10     0            0 00000000  11286       0 I         0        0      false        false       new
  0 Effect Chains
  Local log:
   08-19 14:51:37.849 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP)

Output thread 0x7387a65830, name AudioOut_65, tid 14046, type 2 (DUPLICATING):
  I/O handle: 101
  Standby: yes
  Sample rate: 44100 Hz
  HAL frame count: 1014
  HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
  HAL buffer size: 8112 bytes
  Channel count: 2
  Channel mask: 0x00000003 (front-left, front-right)
  Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
  Processing frame size: 8 bytes
  Pending config events: none
  Output devices:  (Empty device types)
  Input device: 0 (AUDIO_DEVICE_NONE)
  Audio source: 0 (AUDIO_SOURCE_DEFAULT)
  Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
  Timestamp corrected: no
  Master volume: 1.000000
  Master mute: off
  Mixer channel Mask: 0x3 (front-left, front-right)
  Normal frame count: 1024
  Total writes: 0
  Delayed writes: 0
  Blocked in write: no
  Suspend count: 0
  Fast track availMask=0xfe
  Standby delay ns=3000000000
  AudioStreamOut: 0x7160d67440 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
  Frames written: 0
  Suspended frames: 0
  Hal stream dump:
      Signal power history: (none)
      Signal power history: (none)
  Thread throttle time (msecs): 0
  AudioMixer tracks: 
  Master mono: off
  Master balance: 0.000000 (balance 0 channelCount 2 volumes: 1 1)
  No FastMixer
Bluetooth latency modes are not enabled
HAL does not support Bluetooth latency modes
Supported latency modes: { LOW }
  2 OutputTracks: (64 : 0x7387b10fe8, 93) (65 : 0x738b6b7fe8, 13)
  Stream volumes in dB: 0:-42, 1:-inf, 2:-inf, 3:-inf, 4:-14, 5:-inf, 6:-42, 7:-27, 8:0, 9:-96, 10:-15, 11:-14, 12:0, 13:0, 14:0
  Normal mixer raw underrun counters: partial=0 empty=0
  0 Tracks
  0 Effect Chains
  Local log:

AudioDevice HAL::dump
	Mutex: locked
1. Common part
	Audio Mode: 2
	Audio Previous Mode: 0
	Backend Quality current Mode : 0
	tx_data_inversion: False
	DEX STATION connected: False
	DEX PAD connected: 0

2. About Call part
	Call Active: 1
	RealCall: False
	VoLTE state: False
	Previous VoLTE state: False
	current modem: 0
	Voice Volume: 1.000000
	Voice Volume Max Index: 5
	Mute Voice: RX unmute, TX unmute
	wb_amr: 0
	dual_mic: True
	HAC mode: False
	extra volume: False
	call forwarding: False
	TTY mode: 16
	ringback state: False
	Call memo Enabled: 0x10
	Support Adapt Sound Call Param: False
	Mic Mute: False
	All Sound Mute: False

3. About Communications part
	Voip wificalling: False
	CSVT Call: False

4. About Connectivity part
	Bluetooth_nrec: -1
	Bluetooth samplerate: 0

5. About Device Routing part
	Audio Playback Usage Mode: none
	Audio Capture Usage Mode: none

6. About Offload Playback part

7. About Factory Test part
	Loopback Out Device: 0
	Loopback In Device: 0
	Factory mode: False
	is RMS Enable: False
	factory loopback mode: 0
	internal_loopback: False

8. Dual Speaker Checking part


9. FM Radio part
	FM Radio State: FM_OFF
	FM Radio Source: FM_USB_SOURCE
	FM Radio via BT: False
	FM Radio Volume: 0.000000

Audio Ril::dump
	ConnectedRild: 0, 0
	Register Callback State: 0, -1
	MultiSim Mode: 1
	Current Modem: 0

Audio Stream Out(2)::dump
	Mutex: locked
	output devices 1
	output flgas: 2
	output sample rate: 48000
	output channel mask: 3
	output format: 1
	output audio usage: 0
	output standby state: 0
	output backend_mode: 0


proxy_fw_dump 
	spk_mute_for_tv_voip : False

Calliope snapshot:
Calliope snapshot done

USB audio module:
  No output streams.

  No input streams.

Reroute submix audio module:
 route[0], rate=0 addr=[]
 route[1], rate=0 addr=[]
 route[2], rate=0 addr=[]
 route[3], rate=0 addr=[]
 route[4], rate=0 addr=[]
 route[5], rate=0 addr=[]
 route[6], rate=0 addr=[]
 route[7], rate=0 addr=[]
 route[8], rate=0 addr=[]
 route[9], rate=48000 addr=[]

Patches:
  Patch 20: No software bridge (thread 0x0 => thread 0x0) thread 0x738b5e9fe8 num sinks (1) first device type 00000002
  Patch 196: No software bridge (thread 0x0 => thread 0x0) thread 0x7387b10fe8 num sinks (1) first device type 00000080
  Patch 244: No software bridge (thread 0x0 => thread 0x0) thread 0x738b3d7fe8 num sinks (1) first device type 00000001
  Patch 252: No software bridge (thread 0x0 => thread 0x0) thread 0x738b6b7fe8 num sinks (1) first device type 00000001

Device Effects:

Sound Dose:
CSD is disabled
Rejected setParameters:

App setParameters:

System setParameters:
    08-19 14:48:57.158 UID  1000, 1 KVP received: BT_SCO=off
    08-19 14:48:57.162 UID  1000, 1 KVP received: A2dpSuspended=false
    08-19 14:48:57.163 UID  1000, 1 KVP received: LeAudioSuspended=false
    08-19 14:48:57.959 UID  1000, 1 KVP received: screen_state=on
    08-19 14:48:57.961 UID  1000, 1 KVP received: screen_state=on
    08-19 14:49:25.413 UID  1000, 1 KVP received: A2dpSuspended=true
    08-19 14:49:25.429 UID  1000, 1 KVP received: LeAudioSuspended=true
    08-19 14:49:29.616 UID  1000, 1 KVP received: A2dpSuspended=false
    08-19 14:49:29.618 UID  1000, 1 KVP received: LeAudioSuspended=false
    08-19 14:49:29.623 UID  1000, 1 KVP received: A2dpSuspended=true
    08-19 14:49:54.879 UID  1000, 1 KVP received: A2dpSuspended=false
    08-19 14:50:45.572 UID  1000, 1 KVP received: screen_state=off
    08-19 14:50:45.704 UID  1000, 1 KVP received: screen_state=off
    08-19 14:50:57.632 UID  1000, 1 KVP received: screen_state=on
    08-19 14:50:57.716 UID  1000, 1 KVP received: screen_state=on
    08-19 14:51:20.554 UID  1000, 1 KVP received: A2dpSuspended=true
    08-19 14:51:20.601 UID  1000, 1 KVP received: LeAudioSuspended=true
    08-19 14:51:22.558 UID  1000, 1 KVP received: A2dpSuspended=false
    08-19 14:51:22.561 UID  1000, 1 KVP received: LeAudioSuspended=false
    08-19 14:51:22.567 UID  1000, 1 KVP received: A2dpSuspended=true
    08-19 14:51:38.022 UID  1000, 1 KVP received: A2dpSuspended=false
Historical Thread Log 08-19 14:48:47.421 - 
- Input thread 0x7389813b18, name AudioIn_E, tid 5065, type 3 (RECORD):
-   I/O handle: 14
-   Standby: no
-   Sample rate: 48000 Hz
-   HAL frame count: 960
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 3840 bytes
-   Channel count: 2
-   Channel mask: 0x0000000c (left, right)
-   Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   Processing frame size: 4 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   AudioStreamIn: 0x7160d5d940 flags 0 (AUDIO_INPUT_FLAG_NONE)
-   Frames read: 0
-   No active record clients
-   Hal stream dump:
- Audio Stream Input::dump
- 	input Mutex: locked
- 	input devices: -2147483644
- 	input source: 1
- 	input flags: 0
- 	input sample rate: 48000
- 	input channel mask: 12
- 	input format: 1
- 	input audio usage: 1
- 	inut standby state: 0
-       Signal power history: (none)
-       Signal power history: (none)
-   Fast capture thread: no
-   Fast track available: no
-   FastCapture not initialized
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:48:47.449 - 
- Input thread 0x7389813b18, name AudioIn_16, tid 5071, type 3 (RECORD):
-   I/O handle: 22
-   Standby: no
-   Sample rate: 48000 Hz
-   HAL frame count: 1024
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4096 bytes
-   Channel count: 2
-   Channel mask: 0x0000000c (left, right)
-   Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   Processing frame size: 4 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   AudioStreamIn: 0x7160d5ef20 flags 0 (AUDIO_INPUT_FLAG_NONE)
-   Frames read: 0
-   No active record clients
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Fast capture thread: no
-   Fast track available: no
-   FastCapture not initialized
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:49:04.780 - 
- Output thread 0x7387acc880, name AudioOut_25, tid 5898, type 0 (MIXER):
-   I/O handle: 37
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4056 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d5eca0 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   PipeSink frames written: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=5897  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
-             numTracks=0 writeErrors=0 underruns=0 overruns=0
-             sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
-             mixPeriod=nan ms latency=0.00 ms
-   FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   No FastMixer statistics available currently
-   Fast tracks: sMaxFastTracks=8 activeMask=0
-   Index Active Full Partial Empty  Recent Ready    Written
-       0     no    0       0     0    full     0          0
-       1     no    0       0     0    full     0          0
-       2     no    0       0     0    full     0          0
-       3     no    0       0     0    full     0          0
-       4     no    0       0     0    full     0          0
-       5     no    0       0     0    full     0          0
-       6     no    0       0     0    full     0          0
-       7     no    0       0     0    full     0          0
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { LOW }
-   Stream volumes in dB: 0:-inf, 1:-inf, 2:-inf, 3:-inf, 4:-inf, 5:-inf, 6:-inf, 7:-inf, 8:-inf, 9:-inf, 10:-inf, 11:-inf, 12:-inf, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
  0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:49:10.580 - 
- Input thread 0x7387c82b18, name AudioIn_1E, tid 6168, type 3 (RECORD):
-   I/O handle: 30
-   Standby: yes
-   Sample rate: 48000 Hz
-   HAL frame count: 960
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 3840 bytes
-   Channel count: 2
-   Channel mask: 0x0000000c (left, right)
-   Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   Processing frame size: 4 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   AudioStreamIn: 0x7160d5f3d0 flags 0 (AUDIO_INPUT_FLAG_NONE)
-   Frames read: 0
-   No active record clients
-   Hal stream dump:
- Audio Stream Input::dump
- 	input Mutex: locked
- 	input devices: -2147483640
- 	input source: 1
- 	input flags: 0
- 	input sample rate: 48000
- 	input channel mask: 12
- 	input format: 1
- 	input audio usage: 1
- 	inut standby state: 0
-       Signal power history: (none)
-       Signal power history: (none)
-   Fast capture thread: no
-   Fast track available: no
-   FastCapture not initialized
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:49:30.669 - 
- Output thread 0x7387a65830, name AudioOut_35, tid 5905, type 2 (DUPLICATING):
-   I/O handle: 53
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 8112 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d5eca0 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (balance 0 channelCount 2 volumes: 1 1)
-   No FastMixer
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { LOW }
-   2 OutputTracks: (55 : 0x7387b10fe8, 45) (56 : 0x738b6b7fe8, 13)
-   Stream volumes in dB: 0:-24, 1:-inf, 2:-inf, 3:-48, 4:-8, 5:-inf, 6:-24, 7:-30, 8:0, 9:0, 10:-52, 11:-47, 12:0, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:49:30.695 - 
- Output thread 0x7387acc880, name AudioOut_2D, tid 5901, type 0 (MIXER):
-   I/O handle: 45
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4056 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d5eca0 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   PipeSink frames written: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=5900  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
-             numTracks=0 writeErrors=0 underruns=0 overruns=0
-             sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
-             mixPeriod=nan ms latency=0.00 ms
-   FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   No FastMixer statistics available currently
-   Fast tracks: sMaxFastTracks=8 activeMask=0
-   Index Active Full Partial Empty  Recent Ready    Written
-       0     no    0       0     0    full     0          0
-       1     no    0       0     0    full     0          0
-       2     no    0       0     0    full     0          0
-       3     no    0       0     0    full     0          0
-       4     no    0       0     0    full     0          0
-       5     no    0       0     0    full     0          0
-       6     no    0       0     0    full     0          0
-       7     no    0       0     0    full     0          0
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { }
-   Stream volumes in dB: 0:-42, 1:-7.2e+02, 2:-7.2e+02, 3:-48, 4:-7.2e+02, 5:-inf, 6:-42, 7:-27, 8:0, 9:-96, 10:-52, 11:-47, 12:0, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:
-    08-19 14:49:04.945 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP)
-    08-19 14:49:30.673 removeTrack_l (0x72d0d47c30)          55     no   4876       0       0 T  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   3072       0 I         0        0      false        false       new
-    08-19 14:49:30.685 CFG_EVENT_RELEASE_AUDIO_PATCH: old device 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP) new device  (Empty device types)

Historical Thread Log 08-19 14:49:54.601 - 
- Output thread 0x7387acc880, name AudioOut_3D, tid 10029, type 0 (MIXER):
-   I/O handle: 61
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4056 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d66540 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   PipeSink frames written: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=10028  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
-             numTracks=0 writeErrors=0 underruns=0 overruns=0
-             sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
-             mixPeriod=nan ms latency=0.00 ms
-   FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   No FastMixer statistics available currently
-   Fast tracks: sMaxFastTracks=8 activeMask=0
-   Index Active Full Partial Empty  Recent Ready    Written
-       0     no    0       0     0    full     0          0
-       1     no    0       0     0    full     0          0
-       2     no    0       0     0    full     0          0
-       3     no    0       0     0    full     0          0
-       4     no    0       0     0    full     0          0
-       5     no    0       0     0    full     0          0
-       6     no    0       0     0    full     0          0
-       7     no    0       0     0    full     0          0
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { LOW }
-   Stream volumes in dB: 0:-inf, 1:-inf, 2:-inf, 3:-inf, 4:-inf, 5:-inf, 6:-inf, 7:-inf, 8:-inf, 9:-inf, 10:-inf, 11:-inf, 12:-inf, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:49:58.269 - 
- Input thread 0x7387c82b18, name AudioIn_26, tid 10327, type 3 (RECORD):
-   I/O handle: 38
-   Standby: yes
-   Sample rate: 48000 Hz
-   HAL frame count: 960
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 3840 bytes
-   Channel count: 2
-   Channel mask: 0x0000000c (left, right)
-   Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   Processing frame size: 4 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   AudioStreamIn: 0x7160d64ce0 flags 0 (AUDIO_INPUT_FLAG_NONE)
-   Frames read: 0
-   No active record clients
-   Hal stream dump:
- Audio Stream Input::dump
- 	input Mutex: locked
- 	input devices: -2147483640
- 	input source: 1
- 	input flags: 0
- 	input sample rate: 48000
- 	input channel mask: 12
- 	input format: 1
- 	input audio usage: 1
- 	inut standby state: 0
-       Signal power history: (none)
-       Signal power history: (none)
-   Fast capture thread: no
-   Fast track available: no
-   FastCapture not initialized
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:51:23.586 - 
- Output thread 0x7387a65830, name AudioOut_4D, tid 10052, type 2 (DUPLICATING):
-   I/O handle: 77
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 8112 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d66540 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (balance 0 channelCount 2 volumes: 1 1)
-   No FastMixer
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { LOW }
-   2 OutputTracks: (61 : 0x738b6b7fe8, 13) (60 : 0x7387b10fe8, 69)
-   Stream volumes in dB: 0:-42, 1:-inf, 2:-inf, 3:-15, 4:-8, 5:-inf, 6:-42, 7:-27, 8:0, 9:-96, 10:-15, 11:-14, 12:0, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:51:23.604 - 
- Output thread 0x7387acc880, name AudioOut_45, tid 10035, type 0 (MIXER):
-   I/O handle: 69
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4056 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d66540 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   PipeSink frames written: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=10034  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
-             numTracks=0 writeErrors=0 underruns=0 overruns=0
-             sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
-             mixPeriod=nan ms latency=0.00 ms
-   FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   No FastMixer statistics available currently
-   Fast tracks: sMaxFastTracks=8 activeMask=0
-   Index Active Full Partial Empty  Recent Ready    Written
-       0     no    0       0     0    full     0          0
-       1     no    0       0     0    full     0          0
-       2     no    0       0     0    full     0          0
-       3     no    0       0     0    full     0          0
-       4     no    0       0     0    full     0          0
-       5     no    0       0     0    full     0          0
-       6     no    0       0     0    full     0          0
-       7     no    0       0     0    full     0          0
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { }
-   Stream volumes in dB: 0:-42, 1:-7.5e+02, 2:-7.5e+02, 3:-15, 4:-7.5e+02, 5:-inf, 6:-42, 7:-27, 8:0, 9:-96, 10:-15, 11:-14, 12:0, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:
-    08-19 14:49:54.780 CFG_EVENT_CREATE_AUDIO_PATCH: old device  (Empty device types) new device 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP)
-    08-19 14:51:23.587 removeTrack_l (0x72d0d48f80)          60     no   4876       0       0 T  0x000 00000005 00000003  44100 13   f  0  -inf     0     0     0            0 00000000   3072       0 I         0        0      false        false       new
-    08-19 14:51:23.600 CFG_EVENT_RELEASE_AUDIO_PATCH: old device 0x80 (AUDIO_DEVICE_OUT_BLUETOOTH_A2DP) new device  (Empty device types)

Historical Thread Log 08-19 14:51:37.543 - 
- Input thread 0x7387aceb18, name AudioIn_2E, tid 14028, type 3 (RECORD):
-   I/O handle: 46
-   Standby: yes
-   Sample rate: 48000 Hz
-   HAL frame count: 960
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 3840 bytes
-   Channel count: 2
-   Channel mask: 0x0000000c (left, right)
-   Processing format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   Processing frame size: 4 bytes
-   Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   AudioStreamIn: 0x7160d65780 flags 0 (AUDIO_INPUT_FLAG_NONE)
-   Frames read: 0
-   No active record clients
-   Hal stream dump:
- Audio Stream Input::dump
- 	input Mutex: locked
- 	input devices: -2147483640
- 	input source: 1
- 	input flags: 0
- 	input sample rate: 48000
- 	input channel mask: 12
- 	input format: 1
- 	input audio usage: 1
- 	inut standby state: 0
-       Signal power history: (none)
-       Signal power history: (none)
-   Fast capture thread: no
-   Fast track available: no
-   FastCapture not initialized
-   0 Tracks
-   0 Effect Chains
-   Local log:

Historical Thread Log 08-19 14:51:37.687 - 
- Output thread 0x7387acc880, name AudioOut_55, tid 14035, type 0 (MIXER):
-   I/O handle: 85
-   Standby: yes
-   Sample rate: 44100 Hz
-   HAL frame count: 1014
-   HAL format: 0x1 (AUDIO_FORMAT_PCM_16_BIT)
-   HAL buffer size: 4056 bytes
-   Channel count: 2
-   Channel mask: 0x00000003 (front-left, front-right)
-   Processing format: 0x5 (AUDIO_FORMAT_PCM_FLOAT)
-   Processing frame size: 8 bytes
  Pending config events: none
-   Output devices:  (Empty device types)
-   Input device: 0 (AUDIO_DEVICE_NONE)
-   Audio source: 0 (AUDIO_SOURCE_DEFAULT)
-   Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=1 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   Timestamp corrected: no
-   Master volume: 1.000000
-   Master mute: off
-   Mixer channel Mask: 0x3 (front-left, front-right)
-   Normal frame count: 1024
-   Total writes: 0
-   Delayed writes: 0
-   Blocked in write: no
-   Suspend count: 0
-   Fast track availMask=0xfe
-   Standby delay ns=3000000000
-   AudioStreamOut: 0x7160d67440 flags 0 (AUDIO_OUTPUT_FLAG_NONE)
-   Frames written: 0
-   Suspended frames: 0
-   PipeSink frames written: 0
-   Hal stream dump:
-       Signal power history: (none)
-       Signal power history: (none)
-   Thread throttle time (msecs): 0
-   AudioMixer tracks: 
-   Master mono: off
-   Master balance: 0.000000 (0.000000)
  FastMixer thread 0x73898137c0 tid=14034  FastMixer command=COLD_IDLE writeSequence=0 framesWritten=0
-             numTracks=0 writeErrors=0 underruns=0 overruns=0
-             sampleRate=0 frameCount=0 measuredWarmup=0 ms, warmupCycles=0
-             mixPeriod=nan ms latency=0.00 ms
-   FastMixer Timestamp stats: n=0 disc=0 cold=0 nRdy=0 err=0 jitterMs(unavail) localSR(nan, nan) correctedJitterMs(unavail)
-   No FastMixer statistics available currently
-   Fast tracks: sMaxFastTracks=8 activeMask=0
-   Index Active Full Partial Empty  Recent Ready    Written
-       0     no    0       0     0    full     0          0
-       1     no    0       0     0    full     0          0
-       2     no    0       0     0    full     0          0
-       3     no    0       0     0    full     0          0
-       4     no    0       0     0    full     0          0
-       5     no    0       0     0    full     0          0
-       6     no    0       0     0    full     0          0
-       7     no    0       0     0    full     0          0
- Bluetooth latency modes are not enabled
- HAL does not support Bluetooth latency modes
- Supported latency modes: { LOW }
-   Stream volumes in dB: 0:-inf, 1:-inf, 2:-inf, 3:-inf, 4:-inf, 5:-inf, 6:-inf, 7:-inf, 8:-inf, 9:-inf, 10:-inf, 11:-inf, 12:-inf, 13:0, 14:0
-   Normal mixer raw underrun counters: partial=0 empty=0
-   0 Tracks
-   0 Effect Chains
-   Local log:


IAudioFlinger binder call profile:
1 createTrack n=6 ave=203.223 std=286.518 min=12.0121 max=610.865
3 sampleRate n=1 ave=0.050575 min=0.050575 max=0.050575
5 frameCount n=1 ave=0.053883 min=0.053883 max=0.053883
11 setMasterBalance n=2 ave=0.110518 std=0.065843 min=0.06396 max=0.157076
17 setMicMute n=5 ave=1.37034 std=0.697978 min=0.753076 max=2.39707
18 getMicMute n=11 ave=0.436897 std=0.274858 min=0.190692 max=1.15381
20 setParameters n=21 ave=15.4167 std=43.9569 min=0.991191 max=201.911
22 registerClient n=25 ave=1.57686 std=3.39718 min=0.191383 max=13.2964
23 getInputBufferSize n=5 ave=3.23144 std=3.44123 min=0.530613 max=7.08338
34 newAudioUniqueId n=32 ave=0.0683553 std=0.0197511 min=0.026652 max=0.127922
35 acquireAudioSessionId n=32 ave=0.111218 std=0.178329 min=0.062114 max=1.08384
36 releaseAudioSessionId n=29 ave=0.102895 std=0.0950756 min=0.053537 max=0.548038
40 createEffect n=25 ave=14.5665 std=29.7705 min=3.33219 max=155.456
46 setLowRamDevice n=1 ave=0.137075 min=0.137075 max=0.137075
53 systemReady n=1 ave=1.8185 min=1.8185 max=1.8185
57 setAudioHalPids n=1 ave=0.27896 min=0.27896 max=0.27896
58 setVibratorInfos n=1 ave=0.10796 min=0.10796 max=0.10796
67 supportsBluetoothVariableLatency n=7 ave=0.177521 std=0.22247 min=0.059422 max=0.676498
69 isBluetoothVariableLatencyEnabled n=7 ave=0.0521526 std=0.0148048 min=0.031653 max=0.070384
70 getSoundDoseInterface n=1 ave=0.140499 min=0.140499 max=0.140499
1598311760 dump n=3 ave=48.7692 std=40.5586 min=21.8845 max=95.4216
1598968902 getInterfaceDescriptor n=6 ave=0.0767293 std=0.0387245 min=0.040807 max=0.13269

IEffect binder call profile:
1 enable n=4 ave=0.0890273 std=0.0149945 min=0.071267 max=0.107883
3 command n=116 ave=0.531797 std=0.904393 min=0.132575 max=8.06954
4 disconnect n=24 ave=1.09205 std=0.685991 min=0.549422 max=3.11631
5 getCblk n=25 ave=0.0774401 std=0.0352323 min=0.054151 max=0.215153

DeviceHalHidl binder call profile:
createAudioPatch n=3 ave=0.465345 std=0.073232 min=0.406345 max=0.547306
dump n=16 ave=2.40217 std=3.94795 min=0.230999 max=15.5773
getAudioPort n=6 ave=1.28067 std=1.58743 min=0.358268 max=4.48788
getInputBufferSize n=5 ave=2.96406 std=3.26232 min=0.387115 max=6.69977
getMasterMute n=1 ave=2.75185 min=2.75185 max=2.75185
getMasterVolume n=1 ave=0.545537 min=0.545537 max=0.545537
getMicMute n=11 ave=0.346646 std=0.261359 min=0.138653 max=1.02761
getParameters n=30 ave=0.583315 std=0.588064 min=0.142729 max=2.93623
initCheck n=4 ave=0.326316 std=0.190859 min=0.168306 max=0.604037
openInputStream n=5 ave=3.03598 std=2.59784 min=1.07896 max=7.06684
openOutputStream n=9 ave=2.66225 std=2.02173 min=1.25542 max=6.93427
releaseAudioPatch n=2 ave=2.86885 std=2.50887 min=1.09481 max=4.64288
setConnectedState n=84 ave=0.660235 std=2.19522 min=0.004229 max=20.1188
setMasterMute n=4 ave=0.106095 std=0.0181609 min=0.084537 max=0.128884
setMasterVolume n=4 ave=0.175566 std=0.0401304 min=0.121384 max=0.218345
setMicMute n=20 ave=0.306162 std=0.204003 min=0.083038 max=0.829191
setMode n=6 ave=37.3893 std=47.5716 min=0.30919 max=119.054
setParameters n=84 ave=3.50646 std=21.7167 min=0.095961 max=198.061
setVoiceVolume n=3 ave=3.85746 std=3.12393 min=0.276922 max=6.02684
supportsAudioPatches n=45 ave=0.350241 std=0.392409 min=0.086036 max=2.31127

EffectHalHidl binder call profile:
close n=48 ave=0.38725 std=0.467833 min=0.087728 max=2.32938
command n=279 ave=1.36066 std=6.66052 min=0.10873 max=97.5868
dump n=8 ave=1.88567 std=3.32631 min=0.497384 max=10.096
getDescriptor n=25 ave=0.593508 std=0.98578 min=0.14446 max=4.86484
setInBuffer n=102 ave=0.00325948 std=0.00115444 min=0.001345 max=0.006152
setOutBuffer n=114 ave=0.00199682 std=0.00156519 min=0.001421 max=0.018345

StreamInHalHidl binder call profile:
dump n=5 ave=1.00771 std=0.901396 min=0.464999 max=2.60427
getAudioProperties n=20 ave=0.333281 std=0.339095 min=0.097499 max=1.72727
getBufferSize n=10 ave=0.404733 std=0.675891 min=0.074576 max=2.31519
getFrameSize n=5 ave=0.179952 std=0.0464079 min=0.128306 max=0.236538
setParameters n=3 ave=1.07263 std=0.545565 min=0.46023 max=1.50677
standby n=10 ave=0.302241 std=0.126144 min=0.146536 max=0.517691

StreamOutHalHidl binder call profile:
dump n=25 ave=1.30705 std=1.36945 min=0.34546 max=6.53227
getAudioProperties n=42 ave=0.293245 std=0.177406 min=0.122382 max=1.02031
getBufferSize n=21 ave=0.176914 std=0.0716768 min=0.075575 max=0.325306
getFrameSize n=9 ave=0.233917 std=0.086726 min=0.143037 max=0.386113
getHalPid n=2 ave=0.514672 std=0.316649 min=0.290767 max=0.738576
getLatency n=157 ave=1.91888 std=5.02962 min=0.051538 max=38.1179
getParameters n=9 ave=0.514588 std=0.311458 min=0.231613 max=1.29511
legacyCreateAudioPatch n=28 ave=41.7914 std=72.5478 min=0.440805 max=289.103
setEventCallback n=12 ave=1.10579 std=1.63739 min=0.314537 max=6.16873
setParameters n=38 ave=31.1107 std=64.5345 min=0.335575 max=289.027
standby n=11 ave=13.9109 std=31.2701 min=0.109228 max=92.7608
updateSourceMetadata n=40 ave=0.602292 std=0.452198 min=0.192537 max=2.3115

TimeCheck:
now 14:52:03.274
secondChanceCount 0
analysis [  ]
timeout [  ]
pending [ { IAudioPolicyService::setPhoneState scheduled 14:52:03.215 deadline :06.215 tid 5721 } { IAudioFlinger::dump scheduled 14:52:03.251 deadline :06.251 tid 4876 } { IAudioFlinger::setParameters scheduled 14:52:03.274 deadline :06.274 tid 4919 } ]
retired [ { EffectHalHidl::setOutBuffer scheduled 14:52:03.247 deadline  tid 5721 } { EffectHalHidl::command scheduled 14:52:03.247 deadline  tid 5721 } { EffectHalHidl::setInBuffer scheduled 14:52:03.248 deadline  tid 5721 } { EffectHalHidl::setOutBuffer scheduled 14:52:03.248 deadline  tid 5721 } { EffectHalHidl::command scheduled 14:52:03.248 deadline  tid 5721 } { EffectHalHidl::command scheduled 14:52:03.254 deadline  tid 5721 } { StreamOutHalHidl::dump scheduled 14:52:03.259 deadline  tid 4876 } { EffectHalHidl::dump scheduled 14:52:03.260 deadline  tid 4876 } { StreamOutHalHidl::dump scheduled 14:52:03.261 deadline  tid 4876 } { StreamOutHalHidl::dump scheduled 14:52:03.263 deadline  tid 4876 } { StreamOutHalHidl::dump scheduled 14:52:03.267 deadline  tid 4876 } { StreamOutHalHidl::dump scheduled 14:52:03.268 deadline  tid 4876 } { DeviceHalHidl::dump scheduled 14:52:03.269 deadline  tid 4876 } { DeviceHalHidl::dump scheduled 14:52:03.272 deadline  tid 4876 } { DeviceHalHidl::dump scheduled 14:52:03.272 deadline  tid 4876 } { DeviceHalHidl::dump scheduled 14:52:03.272 deadline  tid 4876 } ]
mutex stats: priority inheritance enabled
Capability: AudioPolicyEffects_Mutex
locks: 4
uncontested: 4
waits: 0
unlocks: 4
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: EffectHandle_Mutex
locks: 168
uncontested: 168
waits: 0
unlocks: 168
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: EffectBase_PolicyMutex
locks: 53
uncontested: 53
waits: 0
unlocks: 53
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: AudioPolicyService_Mutex
locks: 4634
uncontested: 3848
waits: 786
unlocks: 4633
avg_wait_ms: 31.351310
std_wait_ms: 79.522624
Capability: CommandThread_Mutex
locks: 8657
uncontested: 8597
waits: 60
unlocks: 8657
avg_wait_ms: 0.397981
std_wait_ms: 0.921334
Capability: AudioCommand_Mutex
locks: 4676
uncontested: 4676
waits: 0
unlocks: 4676
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: UidPolicy_Mutex
locks: 11107
uncontested: 11107
waits: 0
unlocks: 11107
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: AudioFlinger_Mutex
locks: 774
uncontested: 763
waits: 11
unlocks: 774
avg_wait_ms: 11.410612
std_wait_ms: 21.048614
Capability: DeviceEffectManager_Mutex
locks: 62
uncontested: 58
waits: 4
unlocks: 62
avg_wait_ms: 0.004500
std_wait_ms: 0.003724
Capability: PatchCommandThread_Mutex
locks: 175
uncontested: 175
waits: 0
unlocks: 175
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: ThreadBase_Mutex
locks: 73621
uncontested: 73445
waits: 176
unlocks: 73621
avg_wait_ms: 0.922760
std_wait_ms: 3.735999
Capability: AudioFlinger_ClientMutex
locks: 276
uncontested: 248
waits: 28
unlocks: 276
avg_wait_ms: 0.817817
std_wait_ms: 1.241307
Capability: EffectChain_Mutex
locks: 7473
uncontested: 7468
waits: 5
unlocks: 7473
avg_wait_ms: 0.001684
std_wait_ms: 0.000308
Capability: EffectBase_Mutex
locks: 791
uncontested: 775
waits: 16
unlocks: 791
avg_wait_ms: 0.001075
std_wait_ms: 0.001066
Capability: AudioFlinger_HardwareMutex
locks: 118
uncontested: 114
waits: 4
unlocks: 118
avg_wait_ms: 0.001856
std_wait_ms: 0.000204
Capability: MelReporter_Mutex
locks: 4
uncontested: 4
waits: 0
unlocks: 4
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: ConfigEvent_Mutex
locks: 387
uncontested: 387
waits: 0
unlocks: 387
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: PatchCommandThread_ListenerMutex
locks: 60
uncontested: 60
waits: 0
unlocks: 60
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: PlaybackThread_AudioTrackCbMutex
locks: 14
uncontested: 14
waits: 0
unlocks: 14
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: AudioPolicyService_NotificationClientsMutex
locks: 1846
uncontested: 1846
waits: 0
unlocks: 1846
avg_wait_ms: 0.000000
std_wait_ms: 0.000000
Capability: MediaLogNotifier_Mutex
locks: 18440
uncontested: 18163
waits: 277
unlocks: 18440
avg_wait_ms: 0.015722
std_wait_ms: 0.015493
thread count: 23
tid: 4919
waiting: 493666761416
held: size: 0 true_size: 0 items: []
tid: 5721
waiting: 0
held: size: 1 true_size: 1 items: [{ 493398349320, 4 } ]
tids without current activity [ 4876 4918 4923 4986 4987 5056 5061 5063 5169 5906 6907 7856 7869 7870 7871 7872 7887 10054 13283 14038 14046 ]

============================================================
18 BLUETOOTH PROCESSES
============================================================
/system/bin/sh: audioflinger: inaccessible or not found
/system/bin/sh: btservices: inaccessible or not found
/system/bin/sh: audioserver: inaccessible or not found

============================================================
19 BLUETOOTH APEX PACKAGE
============================================================
Activity Resolver Table:
  Full MIME Types:
      x-mixmedia/*:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/x-hwp:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/pdf:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/zip:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/html:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/vnd.openxmlformats-officedocument.presentationml.presentation:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/vnd.ms-powerpoint:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/vnd.openxmlformats-officedocument.wordprocessingml.document:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/xml:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/calendar:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      audio/*:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/vnd.ms-excel:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/x-vcalendar:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      video/*:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/x-vcard:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      text/plain:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/msword:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      vnd.android.cursor.item/vnd.android.btopp:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 4036d2a
          Action: "android.btopp.intent.action.OPEN"
          Category: "android.intent.category.DEFAULT"
          StaticType: "vnd.android.cursor.item/vnd.android.btopp"
      image/*:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application/vnd.openxmlformats-officedocument.spreadsheetml.sheet:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

  Base MIME Types:
      vnd.android.cursor.item:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 4036d2a
          Action: "android.btopp.intent.action.OPEN"
          Category: "android.intent.category.DEFAULT"
          StaticType: "vnd.android.cursor.item/vnd.android.btopp"
      text:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      application:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

  Wild MIME Types:
      audio:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      image:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      video:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      x-mixmedia:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

  Non-Data Actions:
      android.intent.action.APPLICATION_PREFERENCES:
        d242d59 com.android.bluetooth/.BluetoothPrefs filter a0e9d1e
          Action: "android.intent.action.APPLICATION_PREFERENCES"
      com.android.bluetooth.action.TransferHistory:
        934771b com.android.bluetooth/.opp.BluetoothOppTransferHistory filter 18320b8
          Action: "com.android.bluetooth.action.TransferHistory"
          Category: "android.intent.category.DEFAULT"

  MIME Typed Actions:
      android.btopp.intent.action.OPEN:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 4036d2a
          Action: "android.btopp.intent.action.OPEN"
          Category: "android.intent.category.DEFAULT"
          StaticType: "vnd.android.cursor.item/vnd.android.btopp"
      android.intent.action.SEND:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 75a93cc
          Action: "android.intent.action.SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "audio"
          StaticType: "text/x-vcard"
          StaticType: "text/x-vcalendar"
          StaticType: "text/calendar"
          StaticType: "text/plain"
          StaticType: "text/html"
          StaticType: "text/xml"
          StaticType: "application/zip"
          StaticType: "application/vnd.ms-excel"
          StaticType: "application/msword"
          StaticType: "application/vnd.ms-powerpoint"
          StaticType: "application/pdf"
          StaticType: "application/vnd.openxmlformats-officedocument.spreadsheetml.sheet"
          StaticType: "application/vnd.openxmlformats-officedocument.wordprocessingml.document"
          StaticType: "application/vnd.openxmlformats-officedocument.presentationml.presentation"
          StaticType: "application/x-hwp"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      android.intent.action.SEND_MULTIPLE:
        f4c39ff com.android.bluetooth/.opp.BluetoothOppLauncherActivity filter 6614615
          Action: "android.intent.action.SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "image"
          StaticType: "video"
          StaticType: "x-mixmedia"
          StaticType: "text/x-vcard"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

Receiver Resolver Table:
  Full MIME Types:
      */*:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter e9969f7
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter 1a59064
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

  Wild MIME Types:
      *:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter e9969f7
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter 1a59064
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

  Non-Data Actions:
      androidx.profileinstaller.action.SAVE_PROFILE:
        6d522cd com.android.bluetooth/androidx.profileinstaller.ProfileInstallReceiver filter f5d4ed0
          Action: "androidx.profileinstaller.action.SAVE_PROFILE"
      androidx.profileinstaller.action.INSTALL_PROFILE:
        6d522cd com.android.bluetooth/androidx.profileinstaller.ProfileInstallReceiver filter e87782
          Action: "androidx.profileinstaller.action.INSTALL_PROFILE"
      androidx.profileinstaller.action.SKIP_FILE:
        6d522cd com.android.bluetooth/androidx.profileinstaller.ProfileInstallReceiver filter 7f0ae93
          Action: "androidx.profileinstaller.action.SKIP_FILE"
      androidx.profileinstaller.action.BENCHMARK_OPERATION:
        6d522cd com.android.bluetooth/androidx.profileinstaller.ProfileInstallReceiver filter d9e1ec9
          Action: "androidx.profileinstaller.action.BENCHMARK_OPERATION"
      android.btopp.intent.action.ACCEPTLIST_DEVICE:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter 8c331f6
          Action: "android.btopp.intent.action.ACCEPTLIST_DEVICE"
          Action: "android.btopp.intent.action.STOP_HANDOVER_TRANSFER"
      android.btopp.intent.action.STOP_HANDOVER_TRANSFER:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter 8c331f6
          Action: "android.btopp.intent.action.ACCEPTLIST_DEVICE"
          Action: "android.btopp.intent.action.STOP_HANDOVER_TRANSFER"

  MIME Typed Actions:
      android.nfc.handover.intent.action.HANDOVER_SEND_MULTIPLE:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter 1a59064
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND_MULTIPLE"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false
      android.nfc.handover.intent.action.HANDOVER_SEND:
        f1d2e91 com.android.bluetooth/.opp.BluetoothOppHandoverReceiver filter e9969f7
          Action: "android.nfc.handover.intent.action.HANDOVER_SEND"
          Category: "android.intent.category.DEFAULT"
          StaticType: "*"
          mPriority=0, mOrder=0, mHasStaticPartialTypes=true, mHasDynamicPartialTypes=false

Service Resolver Table:
  Non-Data Actions:
      android.telecom.InCallService:
        95c27e8 com.android.bluetooth/.telephony.BluetoothInCallService filter 5d5de01 permission android.permission.BIND_INCALL_SERVICE
          Action: "android.telecom.InCallService"
      android.bluetooth.notification.action.SEND_TOGGLE_NOTIFICATION:
        e9087fc com.android.bluetooth/.notification.NotificationHelperService filter 5e0de85 permission android.permission.BLUETOOTH_PRIVILEGED
          Action: "android.bluetooth.notification.action.SEND_TOGGLE_NOTIFICATION"
      android.bluetooth.IBluetooth:
        22a89ce com.android.bluetooth/.btservice.AdapterService filter 56da0ef permission android.permission.ACCESS_BLUETOOTH_SHARE
          Action: "android.bluetooth.IBluetooth"
      android.telecom.ConnectionService:
        b7a04a6 com.android.bluetooth/.hfpclient.HfpClientConnectionService filter ec2bee7 permission android.permission.BIND_CONNECTION_SERVICE
          Action: "android.telecom.ConnectionService"
      android.accounts.AccountAuthenticator:
        cbfda94 com.android.bluetooth/.pbapclient.AuthenticationService filter 4c1593d
          Action: "android.accounts.AccountAuthenticator"
      android.media.browse.MediaBrowserService:
        46974da com.android.bluetooth/.avrcpcontroller.BluetoothMediaBrowserService filter d1d5d0b
          Action: "android.media.browse.MediaBrowserService"

Domain verification status:

Permissions:
  Permission [com.android.permission.ALLOWLIST_BLUETOOTH_DEVICE] (df7eb71):
    sourcePackage=com.android.bluetooth
    uid=1002 gids=[] type=0 prot=signature|privileged
    perm=PermissionInfo{41a72ee com.android.permission.ALLOWLIST_BLUETOOTH_DEVICE}
    flags=0x0

Permissions:
  Permission [android.permission.ACCESS_BLUETOOTH_SHARE] (6b1dd56):
    sourcePackage=com.android.bluetooth
    uid=1002 gids=[] type=0 prot=signature|privileged
    perm=PermissionInfo{274661c android.permission.ACCESS_BLUETOOTH_SHARE}
    flags=0x0

Permissions:
  Permission [com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION] (1afa1d7):
    sourcePackage=com.android.bluetooth
    uid=1002 gids=[] type=0 prot=signature
    perm=PermissionInfo{becffa com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION}
    flags=0x0

Registered ContentProviders:
  com.android.bluetooth/androidx.startup.InitializationProvider:
    Provider{9f8e9ab com.android.bluetooth/androidx.startup.InitializationProvider}
  com.android.bluetooth/.opp.BluetoothOppProvider:
    Provider{b6fc808 com.android.bluetooth/.opp.BluetoothOppProvider}
  com.android.bluetooth/.map.MmsFileProvider:
    Provider{bbacba1 com.android.bluetooth/.map.MmsFileProvider}
  com.android.bluetooth/.avrcpcontroller.AvrcpCoverArtProvider:
    Provider{819f1c6 com.android.bluetooth/.avrcpcontroller.AvrcpCoverArtProvider}

ContentProvider Authorities:
  [com.android.bluetooth.map.MmsFileProvider]:
    Provider{bbacba1 com.android.bluetooth/.map.MmsFileProvider}
      applicationInfo=ApplicationInfo{e619ac4 com.android.bluetooth}
  [com.android.bluetooth.avrcpcontroller.AvrcpCoverArtProvider]:
    Provider{819f1c6 com.android.bluetooth/.avrcpcontroller.AvrcpCoverArtProvider}
      applicationInfo=ApplicationInfo{44ecdad com.android.bluetooth}
  [com.android.bluetooth.opp]:
    Provider{b6fc808 com.android.bluetooth/.opp.BluetoothOppProvider}
      applicationInfo=ApplicationInfo{90678e2 com.android.bluetooth}
  [com.android.bluetooth.androidx-startup]:
    Provider{9f8e9ab com.android.bluetooth/androidx.startup.InitializationProvider}
      applicationInfo=ApplicationInfo{1628473 com.android.bluetooth}

Key Set Manager:
  [com.android.bluetooth]
      Signing KeySets: 10

Packages:
  Package [com.android.bluetooth] (d9a170):
    appId=1002
    sharedUser=SharedUserSetting{75ee323 android.uid.bluetooth/1002}
    pkg=Package{cad9020 com.android.bluetooth}
    codePath=/apex/com.android.btservices/app/Bluetooth@AP4A.250205.002
    resourcePath=/apex/com.android.btservices/app/Bluetooth@AP4A.250205.002
    legacyNativeLibraryDir=/apex/com.android.btservices/app/Bluetooth@AP4A.250205.002/lib
    extractNativeLibs=false
    primaryCpuAbi=null
    secondaryCpuAbi=null
    cpuAbiOverride=null
    versionCode=35 minSdk=33 targetSdk=35
    minExtensionVersions=[]
    versionName=15
    hiddenApiEnforcementPolicy=0
    usesNonSdkApi=true
    splits=[base]
    apkSigningVersion=3
    flags=[ SYSTEM HAS_CODE ALLOW_CLEAR_USER_DATA ALLOW_BACKUP ]
    privateFlags=[ PRIVATE_FLAG_ACTIVITIES_RESIZE_MODE_RESIZEABLE_VIA_SDK_VERSION ALLOW_AUDIO_PLAYBACK_CAPTURE DEFAULT_TO_DEVICE_PROTECTED_STORAGE DIRECT_BOOT_AWARE PARTIALLY_DIRECT_BOOT_AWARE PRIVILEGED PRIVATE_FLAG_ALLOW_NATIVE_HEAP_POINTER_TAGGING ]
    forceQueryable=false
    scannedAsStoppedSystemApp=false
    supportsScreens=[small, medium, large, xlarge, resizeable, anyDensity]
    timeStamp=1970-01-01 03:30:00
    lastUpdateTime=2026-07-27 07:21:37
    installerPackageName=null
    installerPackageUid=-1
    initiatingPackageName=null
    originatingPackageName=null
    packageSource=0
    appMetadataFilePath=null
    appMetadataSource=0
    signatures=PackageSignatures{904dd9 version:3, signatures:[812e27f9], past signatures:[]}
    installPermissionsFixed=false
    pkgFlags=[ SYSTEM HAS_CODE ALLOW_CLEAR_USER_DATA ALLOW_BACKUP ]
    privatePkgFlags=[ PRIVATE_FLAG_ACTIVITIES_RESIZE_MODE_RESIZEABLE_VIA_SDK_VERSION ALLOW_AUDIO_PLAYBACK_CAPTURE DEFAULT_TO_DEVICE_PROTECTED_STORAGE DIRECT_BOOT_AWARE PARTIALLY_DIRECT_BOOT_AWARE PRIVILEGED PRIVATE_FLAG_ALLOW_NATIVE_HEAP_POINTER_TAGGING ]
    apexModuleName=com.android.btservices
    declared permissions:
      android.permission.ACCESS_BLUETOOTH_SHARE: prot=signature|privileged
      com.android.permission.ALLOWLIST_BLUETOOTH_DEVICE: prot=signature|privileged
      com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION: prot=signature
    requested permissions:
      android.permission.REAL_GET_TASKS
      android.permission.WRITE_SETTINGS
      android.permission.READ_SMS
      android.permission.POST_NOTIFICATIONS
      android.permission.READ_CALL_LOG
      android.permission.ACCESS_FINE_LOCATION
      android.permission.MODIFY_AUDIO_SETTINGS
      android.permission.MODIFY_AUDIO_ROUTING
      android.permission.QUERY_AUDIO_STATE
      android.permission.CALL_PRIVILEGED
      android.permission.CHANGE_NETWORK_STATE
      android.permission.RECEIVE_BOOT_COMPLETED
      android.permission.LISTEN_ALWAYS_REPORTED_SIGNAL_STRENGTH
      android.permission.DEVICE_POWER
      android.permission.RECEIVE_SMS
      android.permission.BLUETOOTH_CONNECT
      android.permission.READ_PROFILE
      android.permission.BLUETOOTH
      android.permission.INTERNET
      android.permission.BLUETOOTH_ADMIN
      android.permission.UPDATE_DEVICE_STATS
      android.permission.BLUETOOTH_STACK
      android.permission.BLUETOOTH_MAP
      android.permission.NET_ADMIN
      android.permission.READ_EXTERNAL_STORAGE
      android.permission.MANAGE_COMPANION_DEVICES
      android.permission.PACKAGE_USAGE_STATS
      android.permission.TETHER_PRIVILEGED
      android.permission.WRITE_SECURE_SETTINGS
      android.permission.ACCESS_COARSE_LOCATION
      android.permission.NFC_HANDOVER_STATUS
      android.permission.HIDE_OVERLAY_WINDOWS
      android.permission.LOG_COMPAT_CHANGE
      android.permission.READ_PRIVILEGED_PHONE_STATE
      android.permission.SEND_SMS
      android.permission.NETWORK_FACTORY
      android.permission.BLUETOOTH_PRIVILEGED
      android.permission.WRITE_SMS
      android.permission.WRITE_CONTACTS
      android.permission.WRITE_APN_SETTINGS
      android.permission.ACCESS_BLUETOOTH_SHARE
      android.permission.MANAGE_USERS
      android.permission.ACCESS_NETWORK_STATE
      android.permission.INTERACT_ACROSS_USERS
      android.permission.WRITE_CALL_LOG
      android.permission.BLUETOOTH_ADVERTISE
      android.permission.NET_TUNNELING
      android.permission.CONNECTIVITY_INTERNAL
      android.permission.GET_ACCOUNTS
      com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION
      android.permission.READ_COMPAT_CHANGE_CONFIG
      android.permission.WRITE_EXTERNAL_STORAGE
      android.permission.VIBRATE
      android.permission.START_FOREGROUND_SERVICES_FROM_BACKGROUND
      android.permission.WRITE_SECURITY_LOG
      android.permission.MANAGE_APP_OPS_MODES
      android.permission.CONTROL_INCALL_EXPERIENCE
      android.permission.MODIFY_PHONE_STATE
      android.permission.QUERY_ALL_PACKAGES
      android.permission.READ_DEVICE_CONFIG
      android.permission.WAKE_LOCK
      android.permission.READ_CONTACTS
      android.permission.UPDATE_APP_OPS_STATS
      android.permission.BLUETOOTH_SCAN
      android.permission.MEDIA_CONTENT_CONTROL
    install permissions:
      android.permission.REAL_GET_TASKS: granted=true
      android.permission.WRITE_SETTINGS: granted=true
      android.permission.MODIFY_AUDIO_SETTINGS: granted=true
      android.permission.MODIFY_AUDIO_ROUTING: granted=true
      android.permission.QUERY_AUDIO_STATE: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CALL_PRIVILEGED: granted=true
      android.permission.CHANGE_NETWORK_STATE: granted=true
      android.permission.RECEIVE_BOOT_COMPLETED: granted=true
      android.permission.LISTEN_ALWAYS_REPORTED_SIGNAL_STRENGTH: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.DEVICE_POWER: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.READ_PROFILE: granted=true
      android.permission.BLUETOOTH: granted=true
      android.permission.INTERNET: granted=true
      android.permission.BLUETOOTH_ADMIN: granted=true
      android.permission.UPDATE_DEVICE_STATS: granted=true
      android.permission.BLUETOOTH_STACK: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.BLUETOOTH_MAP: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.NET_ADMIN: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.MANAGE_COMPANION_DEVICES: granted=true
      android.permission.PACKAGE_USAGE_STATS: granted=true
      android.permission.TETHER_PRIVILEGED: granted=true
      android.permission.WRITE_SECURE_SETTINGS: granted=true
      android.permission.NFC_HANDOVER_STATUS: granted=true
      android.permission.HIDE_OVERLAY_WINDOWS: granted=true
      android.permission.LOG_COMPAT_CHANGE: granted=true
      android.permission.READ_PRIVILEGED_PHONE_STATE: granted=true
      android.permission.NETWORK_FACTORY: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.BLUETOOTH_PRIVILEGED: granted=true
      android.permission.WRITE_SMS: granted=true
      android.permission.WRITE_APN_SETTINGS: granted=true
      android.permission.ACCESS_BLUETOOTH_SHARE: granted=true
      android.permission.MANAGE_USERS: granted=true
      android.permission.ACCESS_NETWORK_STATE: granted=true
      android.permission.INTERACT_ACROSS_USERS: granted=true
      android.permission.NET_TUNNELING: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CONNECTIVITY_INTERNAL: granted=true
      com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION: granted=true
      android.permission.READ_COMPAT_CHANGE_CONFIG: granted=true
      android.permission.VIBRATE: granted=true
      android.permission.START_FOREGROUND_SERVICES_FROM_BACKGROUND: granted=true
      android.permission.WRITE_SECURITY_LOG: granted=true
      android.permission.MANAGE_APP_OPS_MODES: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CONTROL_INCALL_EXPERIENCE: granted=true
      android.permission.MODIFY_PHONE_STATE: granted=true
      android.permission.QUERY_ALL_PACKAGES: granted=true
      android.permission.READ_DEVICE_CONFIG: granted=true
      android.permission.WAKE_LOCK: granted=true
      android.permission.UPDATE_APP_OPS_STATS: granted=true
      android.permission.MEDIA_CONTENT_CONTROL: granted=true
    User 0: ceDataInode=3307 deDataInode=2049 installed=true hidden=false suspended=false distractionFlags=0 stopped=false notLaunched=false enabled=0 instant=false virtual=false quarantined=false
      installReason=0
      dataDir=/data/user_de/0/com.android.bluetooth
      firstInstallTime=2026-07-27 07:21:37
      uninstallReason=0
      overlay paths:
        /product/overlay/NavigationBarModeGestural/NavigationBarModeGesturalOverlay.apk
        /product/overlay/IconShapeSquircle/IconShapeSquircleOverlay.apk
        /data/resource-cache/com.android.systemui-accent-dJR5.frro
        /data/resource-cache/com.android.systemui-dynamic-77sB.frro
        /product/overlay/IconPackCircularAndroid/IconPackCircularAndroidOverlay.apk
        /data/resource-cache/com.android.systemui-neutral-KCsL.frro
      legacy overlay paths:
        /product/overlay/NavigationBarModeGestural/NavigationBarModeGesturalOverlay.apk
        /product/overlay/IconShapeSquircle/IconShapeSquircleOverlay.apk
        /product/overlay/IconPackCircularAndroid/IconPackCircularAndroidOverlay.apk
      enabledComponents:
        com.android.bluetooth.opp.BluetoothOppBtEnableActivity
        com.android.bluetooth.opp.BluetoothOppTransferHistory
        com.android.bluetooth.opp.BluetoothOppProvider
        com.android.bluetooth.opp.BluetoothOppBtEnablingActivity
        com.android.bluetooth.opp.BluetoothOppReceiver
        com.android.bluetooth.map.MmsFileProvider
        com.android.bluetooth.opp.BluetoothOppIncomingFileConfirmActivity
        com.android.bluetooth.opp.BluetoothOppHandoverReceiver
        com.android.bluetooth.opp.BluetoothOppTransferActivity
        com.android.bluetooth.pbap.BluetoothPbapActivity
        com.android.bluetooth.telephony.BluetoothInCallService
        com.android.bluetooth.opp.BluetoothOppLauncherActivity
        com.android.bluetooth.opp.BluetoothOppBtErrorActivity

Queries:
  system apps queryable: false
  queries via forceQueryable:
  queries via package name:
  queries via component:
    com.android.contacts:
      com.android.bluetooth
    com.miniclip.eightballpool:
      com.android.bluetooth
    ir.nasim:
      com.android.bluetooth
    com.azefsw.audioconnect:
      com.android.bluetooth
    com.whatsapp:
      com.android.bluetooth
    com.google.android.youtube:
      com.android.bluetooth
    com.openai.chatgpt:
      com.android.bluetooth
    ai.x.grok:
      com.android.bluetooth
    com.dv.adm:
      com.android.bluetooth
    com.instagram.barcelona:
      com.android.bluetooth
    com.ada.mbank.mehr:
      com.android.bluetooth
    com.google.android.contacts:
      com.android.bluetooth
    app.revanced.android.youtube:
      com.android.bluetooth
    com.rahand.qbank:
      com.android.bluetooth
    com.joytune.app:
      com.android.bluetooth
  queryable via interaction:
    User 0:
      [com.android.providers.settings,com.android.keychain,com.android.dynsystem,com.android.server.telecom,org.lineageos.dap,com.android.location.fused,org.lineageos.setupwizard,org.lineageos.lineagesettings,lineageos.platform,org.lineageos.lineageparts,com.android.settings,com.android.localtransport,com.android.DeviceAsWebcam,com.android.inputdevices,android,org.lineageos.settings.doze]:
        com.android.bluetooth
      com.android.bluetooth:
        [com.android.providers.settings,com.android.keychain,com.android.dynsystem,com.android.server.telecom,org.lineageos.dap,com.android.location.fused,org.lineageos.setupwizard,org.lineageos.lineagesettings,lineageos.platform,org.lineageos.lineageparts,com.android.settings,com.android.localtransport,com.android.DeviceAsWebcam,com.android.inputdevices,android,org.lineageos.settings.doze]
      [com.android.providers.userdictionary,com.android.providers.contactkeys,com.android.providers.blockednumber,com.android.providers.contacts,com.android.calllogbackup]:
        com.android.bluetooth
      org.lineageos.twelve:
        com.android.bluetooth
      ir.nasim:
        com.android.bluetooth
      com.google.android.googlequicksearchbox:
        com.android.bluetooth
      com.google.android.youtube:
        com.android.bluetooth
      app.rbmain.a:
        com.android.bluetooth
      org.telegram.messenger.web:
        com.android.bluetooth
      app.revanced.android.youtube:
        com.android.bluetooth
      com.joytune.app:
        com.android.bluetooth
  queryable via uses-library:

Shared users:
  SharedUser [android.uid.bluetooth] (75ee323):
    appId=1002
    Packages
      PackageSetting{d9a170 com.android.bluetooth/1002}
    install permissions:
      android.permission.REAL_GET_TASKS: granted=true
      android.permission.WRITE_SETTINGS: granted=true
      android.permission.MODIFY_AUDIO_SETTINGS: granted=true
      android.permission.MODIFY_AUDIO_ROUTING: granted=true
      android.permission.QUERY_AUDIO_STATE: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CALL_PRIVILEGED: granted=true
      android.permission.CHANGE_NETWORK_STATE: granted=true
      android.permission.RECEIVE_BOOT_COMPLETED: granted=true
      android.permission.LISTEN_ALWAYS_REPORTED_SIGNAL_STRENGTH: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.DEVICE_POWER: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.READ_PROFILE: granted=true
      android.permission.BLUETOOTH: granted=true
      android.permission.INTERNET: granted=true
      android.permission.BLUETOOTH_ADMIN: granted=true
      android.permission.UPDATE_DEVICE_STATS: granted=true
      android.permission.BLUETOOTH_STACK: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.BLUETOOTH_MAP: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.NET_ADMIN: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.MANAGE_COMPANION_DEVICES: granted=true
      android.permission.PACKAGE_USAGE_STATS: granted=true
      android.permission.TETHER_PRIVILEGED: granted=true
      android.permission.WRITE_SECURE_SETTINGS: granted=true
      android.permission.NFC_HANDOVER_STATUS: granted=true
      android.permission.HIDE_OVERLAY_WINDOWS: granted=true
      android.permission.LOG_COMPAT_CHANGE: granted=true
      android.permission.READ_PRIVILEGED_PHONE_STATE: granted=true
      android.permission.NETWORK_FACTORY: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.BLUETOOTH_PRIVILEGED: granted=true
      android.permission.WRITE_SMS: granted=true
      android.permission.WRITE_APN_SETTINGS: granted=true
      android.permission.ACCESS_BLUETOOTH_SHARE: granted=true
      android.permission.MANAGE_USERS: granted=true
      android.permission.ACCESS_NETWORK_STATE: granted=true
      android.permission.INTERACT_ACROSS_USERS: granted=true
      android.permission.NET_TUNNELING: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CONNECTIVITY_INTERNAL: granted=true
      com.android.bluetooth.DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION: granted=true
      android.permission.READ_COMPAT_CHANGE_CONFIG: granted=true
      android.permission.VIBRATE: granted=true
      android.permission.START_FOREGROUND_SERVICES_FROM_BACKGROUND: granted=true
      android.permission.WRITE_SECURITY_LOG: granted=true
      android.permission.MANAGE_APP_OPS_MODES: granted=true, flags=[ GRANTED_BY_ROLE]
      android.permission.CONTROL_INCALL_EXPERIENCE: granted=true
      android.permission.MODIFY_PHONE_STATE: granted=true
      android.permission.QUERY_ALL_PACKAGES: granted=true
      android.permission.READ_DEVICE_CONFIG: granted=true
      android.permission.WAKE_LOCK: granted=true
      android.permission.UPDATE_APP_OPS_STATS: granted=true
      android.permission.MEDIA_CONTENT_CONTROL: granted=true
    User 0: 
      gids=[3002, 3003, 3001, 3007, 1002, 3010, 3011, 3005, 1016, 1091]
      runtime permissions:
        android.permission.READ_SMS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.POST_NOTIFICATIONS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.READ_CALL_LOG: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.ACCESS_FINE_LOCATION: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT]
        android.permission.RECEIVE_SMS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.BLUETOOTH_CONNECT: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.READ_EXTERNAL_STORAGE: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.ACCESS_COARSE_LOCATION: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT]
        android.permission.SEND_SMS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.WRITE_CONTACTS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.WRITE_CALL_LOG: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.BLUETOOTH_ADVERTISE: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.GET_ACCOUNTS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.WRITE_EXTERNAL_STORAGE: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_SYSTEM_EXEMPT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.READ_CONTACTS: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]
        android.permission.BLUETOOTH_SCAN: granted=true, flags=[ SYSTEM_FIXED|GRANTED_BY_DEFAULT|RESTRICTION_UPGRADE_EXEMPT]

Dexopt state:
  [com.android.bluetooth]
    path: /apex/com.android.btservices/app/Bluetooth@AP4A.250205.002/Bluetooth.apk
      arm64: [status=speed-profile] [reason=bg-dexopt] [primary-abi]
        [location is /data/dalvik-cache/arm64/apex@com.android.btservices@app@Bluetooth@AP4A.250205.002@Bluetooth.apk@classes.dex]

Compiler stats:
  [com.android.bluetooth]
     Bluetooth.apk - 1145

============================================================
20 BT SERVICES
============================================================
/system/bin/sh: BluetoothManager: inaccessible or not found
/system/bin/sh: BluetoothHeadset: inaccessible or not found

============================================================
21 LIVE BLUETOOTH
============================================================
Bluetooth Status
  enabled: false
  state: BLE_TURNING_ON
  address: XX:XX:XX:XX:82:10
  name: Galaxy A21s
  time since enabled: 00:03:04.800

Enable log:
  08-19 14:49:00.341 	Package [android] requested to [Enable]. 	Reason is SYSTEM_BOOT
  08-19 14:49:29.148 	Package [BluetoothSystemServer] requested to [Disable]. 	Reason is CRASH
  08-19 14:49:29.552 	Package [BluetoothSystemServer] requested to [Enable]. 	Reason is RESTARTED
  08-19 14:51:22.308 	Package [BluetoothSystemServer] requested to [Disable]. 	Reason is CRASH
  08-19 14:51:22.710 	Package [BluetoothSystemServer] requested to [Enable]. 	Reason is RESTARTED
  08-19 14:52:04.516 	Package [BluetoothSystemServer] requested to [Disable]. 	Reason is CRASH
  08-19 14:52:04.931 	Package [BluetoothSystemServer] requested to [Enable]. 	Reason is RESTARTED

Bluetooth crashed 3 times
  08-19 14:49:29.106
  08-19 14:51:22.308
  08-19 14:52:04.516

Number of Ble app registered: 0

BluetoothManagerService:
  mEnable:true
  mQuietEnable:false
  mEnableExternal:true
  mQuietEnableExternal:false

🚩Flag dump:
	[■]: a2dp_aidl_encoding_interval
	[■]: a2dp_async_allow_low_latency
	[ ]: a2dp_broadcast_connection_state_when_turned_off
	[■]: a2dp_check_lea_iso_channel
	[■]: a2dp_fix_codec_type_in_java
	[ ]: a2dp_ignore_started_when_responder
	[■]: a2dp_service_looper
	[ ]: a2dp_variable_aac_capability
	[ ]: abs_volume_sdp_conflict
	[■]: adm_always_fallback_to_available_device
	[■]: adm_fallback_when_wired_audio_disconnected
	[■]: allow_switching_hid_and_hogp
	[■]: android_headtracker_service
	[■]: android_os_identifier
	[■]: api_get_connection_state_using_identity_address
	[■]: asha_encrypted_l2c_coc
	[■]: asymmetric_phy_for_unidirectional_cis
	[■]: audio_port_binder_inherit_rt
	[ ]: audio_routing_centralization
	[ ]: auto_connect_on_multiple_hfp_when_no_a2dp_device
	[ ]: av_stream_reconfigure_fix
	[■]: avdt_discover_seps_as_acceptor
	[ ]: avdt_prioritize_mandatory_codec
	[■]: avdtp_error_codes
	[■]: avoid_static_loading_of_native
	[■]: avrcp_connect_a2dp_with_delay
	[■]: avrcp_sdp_records
	[■]: ble_check_data_length_on_legacy_advertising
	[■]: ble_context_map_remove_fix
	[■]: ble_gatt_server_use_address_type_in_connection
	[■]: ble_scan_adv_metrics_redesign
	[ ]: bluetooth_power_telemetry
	[■]: bond_transport_after_bond_cancel_fix
	[■]: break_uhid_polling_early
	[ ]: browsing_refactor
	[ ]: bt_socket_api_l2cap_cid
	[■]: bt_system_context_report
	[ ]: bta_ag_cmd_brsf_allow_uint32
	[ ]: bta_av_setconfig_rej_type_confusion
	[ ]: bta_av_use_peer_codec
	[ ]: bta_dm_defer_device_discovery_state_change_until_rnr_complete
	[■]: bta_dm_discover_both
	[■]: btsec_check_valid_discovery_database
	[■]: cancel_open_discovery_client
	[■]: cancel_pairing_only_on_disconnected_transport
	[■]: channel_sounding
	[ ]: channel_sounding_in_stack
	[■]: choose_wrong_hfp_codec_in_specific_config
	[■]: cleanup_le_only_device_type
	[ ]: clear_auth_collision_state_on_pairing_complete
	[ ]: clear_pairing_state_when_no_devrec
	[ ]: close_hid_if_uhid_ready_too_slow
	[■]: close_hid_only_if_connected
	[■]: device_iot_config_logging
	[ ]: donot_push_error_code_to_app_when_connected
	[ ]: donot_queue_dup_rnr
	[ ]: donot_validate_bond_state_from_profiles
	[ ]: enable_hap_by_default
	[ ]: encrypted_advertising_data
	[ ]: encryption_change_v2
	[ ]: enforce_resolve_system_service_behavior
	[■]: enumerate_gatt_errors
	[■]: fast_bind_to_app
	[ ]: fix_avdt_rconfig_not_setting_l2cap
	[ ]: fix_hfp_qual19
	[■]: fix_le_evt_cancelling_sdp_discovery
	[■]: fix_nonconnectable_scannable_advertisement
	[ ]: fix_sco_command_status_handling
	[ ]: floss_separate_host_privacy_and_llprivacy
	[ ]: gatt_callback_on_failure
	[■]: gatt_cleanup_restricted_handles
	[ ]: gatt_client_dynamic_allocation
	[ ]: gatt_disconnect_fix
	[■]: gatt_fix_device_busy
	[■]: gatt_fix_multiple_direct_connect
	[■]: gatt_rediscover_on_canceled
	[ ]: gatt_server_requests_fix
	[ ]: get_all_element_attributes_empty
	[ ]: get_name_and_address_as_callback
	[ ]: get_state_from_system_server
	[ ]: guest_mode_bond
	[ ]: handle_delivery_sending_failure_events
	[■]: headset_client_am_hf_volume_symmetric
	[■]: headtracker_codec_capability
	[■]: headtracker_sdu_size
	[ ]: hfp_allow_volume_change_without_sco
	[ ]: hfp_client_disconnecting_state
	[ ]: hfp_software_datapath
	[■]: hid_report_queuing
	[■]: identity_address_null_if_not_known
	[ ]: ignore_notify_when_already_connected
	[ ]: improve_create_connection_for_already_connecting_device
	[■]: initiate_multiple_hid_connections
	[ ]: is_sco_managed_by_audio
	[ ]: key_missing_as_ordered_broadcast
	[■]: key_missing_broadcast
	[ ]: key_missing_classic_device
	[ ]: kill_instead_of_exit
	[ ]: l2cap_le_do_not_adjust_min_interval
	[■]: l2cap_p_ccb_check_rewrite
	[ ]: l2cap_tx_complete_cb_info
	[■]: l2cap_update_existing_conn_interval_with_base_interval
	[■]: le_ase_read_multiple_variable
	[■]: le_audio_base_ecosystem_interval
	[ ]: le_audio_support_unidirectional_voice_assistant
	[ ]: le_enc_on_reconnection
	[■]: le_inquiry_duration
	[■]: le_scan_fix_remote_exception
	[ ]: le_scan_msft_support
	[■]: le_scan_use_address_type
	[■]: le_scan_use_uid_for_importance
	[ ]: leaudio_add_aics_support
	[ ]: leaudio_allow_leaudio_only_devices
	[■]: leaudio_allowed_context_mask
	[ ]: leaudio_big_depends_on_audio_state
	[■]: leaudio_broadcast_assistant_peripheral_entrustment
	[■]: leaudio_broadcast_audio_handover_policies
	[■]: leaudio_broadcast_destroy_after_timeout
	[■]: leaudio_broadcast_extract_periodic_scanner_from_state_machine
	[■]: leaudio_broadcast_feature_support
	[■]: leaudio_broadcast_monitor_source_sync_status
	[ ]: leaudio_broadcast_resync_helper
	[■]: leaudio_broadcast_update_metadata_callback
	[■]: leaudio_broadcast_volume_control_for_connected_devices
	[■]: leaudio_broadcast_volume_control_primary_group_only
	[■]: leaudio_broadcast_volume_control_with_set_volume
	[■]: leaudio_call_start_scan_directly
	[■]: leaudio_codec_config_callback_order_fix
	[■]: leaudio_dynamic_spatial_audio
	[■]: leaudio_getting_active_state_support
	[ ]: leaudio_gmap_client
	[■]: leaudio_hal_client_asrc
	[ ]: leaudio_mono_location_errata
	[■]: leaudio_multicodec_aidl_support
	[■]: leaudio_multiple_vocs_instances_api
	[■]: leaudio_no_context_validate_streaming_request
	[ ]: leaudio_set_codec_config_preference
	[■]: leaudio_speed_up_reconfiguration_between_call
	[■]: leaudio_start_request_state_mutex_check
	[■]: leaudio_synchronize_start
	[ ]: leaudio_unicast_no_available_contexts
	[■]: leaudio_use_audio_mode_listener
	[ ]: maintain_call_index_after_conference
	[■]: map_limit_notification
	[■]: mcp_allow_play_without_active_player
	[■]: metadata_api_inactive_audio_device_upon_connection
	[ ]: msft_addr_tracking_quirk
	[■]: name_discovery_for_le_pairing
	[ ]: non_wake_alarm_for_rpa_rotation
	[ ]: nrpa_non_connectable_adv
	[■]: opp_fix_multiple_notifications_issues
	[■]: opp_ignore_content_observer_after_service_stop
	[■]: opp_start_activity_directly_from_notification
	[■]: override_context_to_specify_device_id
	[■]: pairing_name_discovery_addresss_mismatch
	[■]: pairing_on_unknown_transport
	[■]: pan_use_identity_address
	[ ]: phy_to_native
	[ ]: prevent_duplicate_uuid_intent
	[■]: prevent_hogp_reconnect_when_connected
	[■]: progress_acl_scheduler_upon_incoming_connection
	[ ]: queue_dis_requests
	[■]: randomize_device_level_media_ids
	[ ]: read_le_appearance
	[ ]: refactor_saving_messages_and_metadata
	[■]: remove_address_map_on_unbond
	[ ]: remove_dup_pairing_response_in_oob_pairing
	[■]: remove_input_device_on_vup
	[ ]: remove_one_time_get_name_and_address
	[■]: reset_after_collision
	[■]: reset_ag_state_on_collision
	[■]: respect_ble_scan_setting
	[ ]: retry_esco_with_zero_retransmission_effort
	[ ]: rfcomm_always_disc_initiator_in_disc_wait_ua
	[■]: rfcomm_always_use_mitm
	[■]: rfcomm_prevent_unnecessary_collisions
	[ ]: rnr_directly_call_gap_over_le
	[ ]: rnr_store_device_type
	[ ]: rnr_validate_page_scan_repetition_mode
	[ ]: run_ble_audio_ticks_in_worker_thread
	[ ]: run_clock_recovery_in_worker_thread
	[■]: save_initial_hid_connection_policy
	[ ]: save_peer_csrk_after_ltk_gen
	[ ]: scan_manager_refactor
	[■]: scan_record_manufacturer_data_merge
	[ ]: sec_dont_clear_keys_on_encryption_err
	[ ]: serialize_hogp_and_dis
	[ ]: set_addressed_player
	[■]: settings_can_control_hap_preset
	[ ]: signal_connecting_on_focus_gain
	[■]: sink_audio_policy_handover
	[ ]: skip_unknown_robust_caching
	[ ]: stack_sdp_detect_nil_property_type
	[■]: stop_on_offload_fail
	[ ]: support_bluetooth_quality_report_v6
	[■]: support_exclusive_manager
	[ ]: support_metadata_device_types_apis
	[■]: suppress_hid_rejection_broadcast
	[ ]: system_server_messenger
	[■]: temporary_pairing_device_properties
	[■]: transmit_smp_packets_before_release
	[■]: unbonded_profile_forbid_fix
	[ ]: uncache_player_when_browsed_player_changes
	[ ]: unified_connection_manager
	[■]: unix_file_socket_creation_failure
	[ ]: update_active_device_in_band_ringtone
	[■]: update_sco_state_correctly_on_rfcomm_disconnect_during_codec_nego
	[ ]: use_encrypt_req_for_av
	[ ]: use_entire_message_handle
	[ ]: use_le_shim_connection_map_guard
	[■]: use_local_oob_extended_command
	[ ]: vcp_mute_unmute
	[■]: wait_for_disconnect_before_unbond


AdapterProperties
  Name: null
  Address: null
  ConnectionState: STATE_DISCONNECTED
  State: OFF
  MaxConnectedAudioDevices: 1
  A2dpOffloadEnabled: false
  Discovering: false
  DiscoveryEndMs: 0
  Bonded devices:

ScanMode: Unknown Scan Mode 0
Scan Mode Changes:

sSnoopLogSettingAtEnable = EMPTY
sDefaultSnoopLogSettingAtEnable = empty

Enabled Profile Services:
  GATT
  A2DP
  AVRCP
  BATTERY
  HEADSET
  HEARING_AID
  HID_DEVICE
  HID_HOST
  MAP
  OPP
  PAN
  PBAP
  SAP

AdapterState:
 total records=0
curState=OffState

SilenceDeviceManager:
  Address            | Is silenced?

BluetoothDatabase:
  Metadata Changes:

Metadata:

Impossible to dump native stack. state=OFF


============================================================
22 LIVE HFP SCO
============================================================
/system/bin/sh: HEADSET: inaccessible or not found
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: eSCO: inaccessible or not found
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: connected: inaccessible or not found
/system/bin/sh: disconnect: inaccessible or not found
/system/bin/sh: active: inaccessible or not found
/system/bin/sh: inactive: inaccessible or not found
/system/bin/sh: audio: inaccessible or not found
/system/bin/sh: state: inaccessible or not found

============================================================
23 LIVE AUDIO
============================================================
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: HFP: inaccessible or not found
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: communication: inaccessible or not found
/system/bin/sh: route: inaccessible or not found
/system/bin/sh: device: inaccessible or not found
/system/bin/sh: speaker: inaccessible or not found
/system/bin/sh: earpiece: inaccessible or not found
/system/bin/sh: HAL: inaccessible or not found
/system/bin/sh: mode: inaccessible or not found

============================================================
24 LIVE AUDIO POLICY
============================================================
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: HFP: inaccessible or not found
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: route: inaccessible or not found
/system/bin/sh: error: inaccessible or not found
/system/bin/sh: fail: inaccessible or not found
/system/bin/sh: HAL: inaccessible or not found
/system/bin/sh: device: inaccessible or not found

============================================================
25 LIVE AUDIO FLINGER
============================================================
/system/bin/sh: A2DP: inaccessible or not found
/system/bin/sh: fail: inaccessible or not found
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: Record: inaccessible or not found
/system/bin/sh: error: inaccessible or not found
/system/bin/sh: Playback: inaccessible or not found
/system/bin/sh: HFP: inaccessible or not found
/system/bin/sh: Output: inaccessible or not found
/system/bin/sh: Input: inaccessible or not found

============================================================
26 LOGCAT HFP SCO
============================================================
/system/bin/sh: Headset: inaccessible or not found
/system/bin/sh: SCO: inaccessible or not found
/system/bin/sh: eSCO: inaccessible or not found
/system/bin/sh: HAL.*audio: inaccessible or not found
/system/bin/sh: AudioFlinger: inaccessible or not found
/system/bin/sh: BluetoothAudio: inaccessible or not found
/system/bin/sh: BluetoothAudioHal: inaccessible or not found
/system/bin/sh: bt_stack: inaccessible or not found
/system/bin/sh: btif: inaccessible or not found
/system/bin/sh: AudioPolicy: inaccessible or not found
/system/bin/sh: audio.*HAL: inaccessible or not found

============================================================
27 LOGCAT ERRORS
============================================================
/system/bin/sh: failed: inaccessible or not found
/system/bin/sh: error: inaccessible or not found
/system/bin/sh: failure: inaccessible or not found
/system/bin/sh: invalid: inaccessible or not found
/system/bin/sh: FATAL: inaccessible or not found
/system/bin/sh: Error: inaccessible or not found
/system/bin/sh: fatal: inaccessible or not found
/system/bin/sh: crash: inaccessible or not found
/system/bin/sh: Crash: inaccessible or not found
/system/bin/sh: unable: inaccessible or not found
/system/bin/sh: cannot: inaccessible or not found

============================================================
28 BLUETOOTH AUDIO HAL ERRORS ONLY
============================================================
/system/bin/sh: BluetoothAudioHal: inaccessible or not found
/system/bin/sh: HFP.*HAL: inaccessible or not found
/system/bin/sh: A2DP.*HAL: inaccessible or not found
/system/bin/sh: sink.*audio: inaccessible or not found
/system/bin/sh: audio.*sink: inaccessible or not found
/system/bin/sh: audio.*HAL.*setup: inaccessible or not found
/system/bin/sh: SCO.*HAL: inaccessible or not found
/system/bin/sh: setup.*audio.*HAL: inaccessible or not found
/system/bin/sh: SCO.*open: inaccessible or not found
/system/bin/sh: SCO.*socket: inaccessible or not found
/system/bin/sh: HF.*audio: inaccessible or not found

============================================================
29 FINAL BUILD
============================================================
lineage_a21s-userdebug 15 AP4A.250205.002 61e53241d0
22.1-20250401-NIGHTLY-a21s
 
============================================================ 
END 
============================================================ 
