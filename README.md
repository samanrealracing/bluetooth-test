--------- beginning of radio
08-19 22:46:07.131 E/RILClient( 5919): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:07.792 E/boot    ( 6000): cbd: (ERR! No such file or directory) get_cmdline_str: find str androidboot.debug_level=0x4f4c form /proc/cmdline
08-19 22:46:07.792 D/boot    ( 6000): cbd: check_debug_level: androidboot.debug_level=0x4f4c, 0
08-19 22:46:07.793 D/boot    ( 6000): cbd: get_cmdline_str: find str androidboot.force_upload=0x0 form /proc/cmdline
08-19 22:46:07.793 D/boot    ( 6000): cbd: check_debug_level: force_upload = 0x0
08-19 22:46:07.793 D/boot    ( 6000): cbd: check_debug_level: debug level=0, cp_debug=0
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Start CP Boot Daemon (CBD) CBD-20220120R1
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Daemon Mode
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: SS310 modem
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: boot SHMEM link
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: main SHMEM link
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: partition number : by-name/radio
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: partition path : /dev/block/by-name/radio
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Call boot start
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Modem type = 12
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Boot link = 9
08-19 22:46:07.793 D/boot    ( 6000): cbd: main: Main link = 9
08-19 22:46:07.793 E/boot    ( 6000): cbd: (ERR! No such file or directory) check_board_revision: /proc/device-tree/model_info-system_rev open fail (No such file or directory)
08-19 22:46:07.793 D/boot    ( 6000): cbd: start_shannon310_boot: CP boot device = /dev/umts_boot0
08-19 22:46:07.793 D/boot    ( 6000): cbd: start_shannon310_boot: CP binary file = /dev/block/by-name/radio
08-19 22:46:07.793 D/boot    ( 6000): cbd: start_shannon310_boot: CP NV file = /mnt/vendor/efs/nv_data.bin
08-19 22:46:07.793 D/boot    ( 6000): cbd: start_shannon310_boot: BOOT link SHMEM
08-19 22:46:07.793 D/boot    ( 6000): cbd: start_shannon310_boot: MAIN link SHMEM
08-19 22:46:08.140 D/RILD    ( 6018): **RIL Daemon Started**
08-19 22:46:08.140 D/RILD    ( 6018): **RILd param count=1**
08-19 22:46:08.143 D/RILD    ( 6018): rilLibPath = libsec-ril.so
08-19 22:46:08.292 D/RILD    ( 6018): RIL_Init argc = 3 simSlotCount = 2
08-19 22:46:08.292 D/RILD    ( 6018): RIL_Init argc = 5 clientId = 0
08-19 22:46:08.292 E/RILC    ( 6018): rilc_configure_thread_pool
08-19 22:46:08.296 D/RILD    ( 6018): RIL_Init: SimCount: 2
08-19 22:46:08.296 D/RILD    ( 6018): RIL_Init:  Initialize XML Parser once
08-19 22:46:08.301 D/RILD    ( 6018): RIL_Init[0]: phy intf: rmnet_mhi0, gsm net prefix: rmnet
08-19 22:46:08.301 D/RILD    ( 6018): RIL_Init[1]: phy intf: rmnet_mhi0, gsm net prefix: rmnet
08-19 22:46:08.302 E/RILD    ( 6018): create Thread[IPM]
08-19 22:46:08.302 E/RILD2   ( 6018): create Thread[IPM2]
08-19 22:46:08.341 E/RILD2   ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.341 E/RILD    ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.343 E/RILD2   ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.343 E/RILD2   ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.343 E/RILD2   ( 6018): create Thread[MTC2]
08-19 22:46:08.353 E/RILD2   ( 6018): NET-MGR - ModelType: 0 -> 2
08-19 22:46:08.355 E/RILD2   ( 6018): create Thread[ODEAR2]
08-19 22:46:08.365 E/RILD    ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.365 E/RILD    ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.365 E/RILD    ( 6018): Debug channel is not opened for ship build.
08-19 22:46:08.366 E/RILD    ( 6018): create Thread[MTC]
08-19 22:46:08.370 E/RILD    ( 6018): NET-MGR - ModelType: 0 -> 2
08-19 22:46:08.371 E/RILD    ( 6018): create Thread[ODEAR]
08-19 22:46:08.390 E/RILD2   ( 6018): CALL-MGR - ModelType: 0 -> 2
08-19 22:46:08.390 E/RILD2   ( 6018): CALL-MGR - Make new CallManager (ModelType: 2)
08-19 22:46:08.392 E/RILD    ( 6018): create Thread[SDBHAR]
08-19 22:46:08.395 D/boot    ( 6000): cbd: start_shannon310_boot: NV validation done
08-19 22:46:08.395 D/boot    ( 6000): cbd: boot_wake_lock: /sys/power/wake_lock/ss310
08-19 22:46:08.395 D/boot    ( 6000): cbd: start_shannon310_boot: Prepare arguments
08-19 22:46:08.395 D/boot    ( 6000): cbd: std_boot_prepare_args: DEV(/dev/umts_boot0) opened (fd 6)
08-19 22:46:08.395 D/boot    ( 6000): cbd: prepare_boot_args: BIN(/dev/block/by-name/radio) opened (fd 7)
08-19 22:46:08.396 E/RILD    ( 6018): CALL-MGR - ModelType: 0 -> 2
08-19 22:46:08.396 D/boot    ( 6000): cbd: prepare_boot_args: toc[0].name = TOC, b_off=0x00000000, m_off=0x40008000, size=0x00000410
08-19 22:46:08.396 E/RILD    ( 6018): CALL-MGR - Make new CallManager (ModelType: 2)
08-19 22:46:08.396 D/boot    ( 6000): cbd: prepare_boot_args: toc[1].name = BOOT, b_off=0x00000420, m_off=0x40000000, size=0x00001ca8
08-19 22:46:08.396 D/boot    ( 6000): cbd: prepare_boot_args: toc[2].name = MAIN, b_off=0x000020e0, m_off=0x40010000, size=0x0251b4d4
08-19 22:46:08.396 D/boot    ( 6000): cbd: prepare_boot_args: toc[3].name = VSS, b_off=0x0251d5c0, m_off=0x46900000, size=0x00550514
08-19 22:46:08.396 D/boot    ( 6000): cbd: prepare_boot_args: toc[4].name = NV, b_off=0x00000000, m_off=0x46300000, size=0x00100000
08-19 22:46:08.398 D/boot    ( 6000): cbd: prepare_boot_args: NV(/mnt/vendor/efs/nv_data.bin) opened (fd 8)
08-19 22:46:08.398 D/boot    ( 6000): cbd: build_std_dload_control: stage=0, name:TOC b_off=0x00000000, m_offset=0x00008000 b_size=0x00000410
08-19 22:46:08.398 D/boot    ( 6000): cbd: build_std_dload_control: stage=1, name:BOOT b_off=0x00000420, m_offset=0x00000000 b_size=0x00001ca8
08-19 22:46:08.398 D/boot    ( 6000): cbd: build_std_dload_control: stage=2, name:MAIN b_off=0x000020e0, m_offset=0x00010000 b_size=0x0251b4d4
08-19 22:46:08.398 D/boot    ( 6000): cbd: build_std_dload_control: stage=3, name:VSS b_off=0x0251d5c0, m_offset=0x06900000 b_size=0x00550514
08-19 22:46:08.398 D/boot    ( 6000): cbd: build_std_dload_control: stage=4, name:NV b_off=0x00000000, m_offset=0x06300000 b_size=0x00100000
08-19 22:46:08.398 D/boot    ( 6000): cbd: check_srinfo_last: check_srinfo_last: full_path: /data/vendor/log/cbd/err/last_sr_info_umts
08-19 22:46:08.398 E/boot    ( 6000): cbd: (ERR! No such file or directory) alloc_srinfo: Crash info string was invalid(0/5245564a)
08-19 22:46:08.398 D/boot    ( 6000): cbd: store_srinfo_type1: alloc srinfo fail
08-19 22:46:08.404 D/boot    ( 6000): cbd: get_modem_state: modem_status: 0
08-19 22:46:08.404 D/boot    ( 6000): cbd: start_shannon310_boot: Power on CP
08-19 22:46:08.406 D/boot    ( 6000): cbd: start_shannon310_boot: Request security : non-secure mode
08-19 22:46:08.406 D/boot    ( 6000): cbd: std_security_req: security_req: 2:0:0:0
08-19 22:46:08.406 D/boot    ( 6000): cbd: std_security_req: orig cpu_set[0]=0x000000ff
08-19 22:46:08.407 D/boot    ( 6000): cbd: std_security_req: new cpu_set[0]=0x000000fe
08-19 22:46:08.407 D/boot    ( 6000): cbd: std_security_req: ERR! IOCTL_CHECK_SECURITY fail (11,Success)
08-19 22:46:08.407 D/boot    ( 6000): cbd: std_security_req: restore cpu_set[0]=0x000000ff
08-19 22:46:08.407 D/boot    ( 6000): cbd: start_shannon310_boot: Send CP image
08-19 22:46:08.407 D/boot    ( 6000): cbd: load_cp_image_by_stage: stage=0(0), b_off=0x00000000, m_off=0x00008000, b_size=0x00000410, mode=0x00000000
08-19 22:46:08.408 D/boot    ( 6000): cbd: load_cp_image_by_stage: 0 stage complelte
08-19 22:46:08.408 D/boot    ( 6000): cbd: load_cp_image_by_stage: stage=1(1), b_off=0x00000420, m_off=0x00000000, b_size=0x00001ca8, mode=0x00000000
08-19 22:46:08.409 D/boot    ( 6000): cbd: load_cp_image_by_stage: 1 stage complelte
08-19 22:46:08.409 D/boot    ( 6000): cbd: load_cp_image_by_stage: stage=2(2), b_off=0x000020e0, m_off=0x00010000, b_size=0x0251b4d4, mode=0x00000000
08-19 22:46:08.410 E/RILD2   ( 6018): NetworkManager init start
08-19 22:46:08.410 E/RILD    ( 6018): NetworkManager init start
08-19 22:46:08.411 E/RILD    ( 6018): NetworkManager init end
08-19 22:46:08.411 E/RILD2   ( 6018): NetworkManager init end
08-19 22:46:08.413 E/RILD2   ( 6018): SelectE911RatDeterminer - Type: DEFAULT (Reason: CS domain)
08-19 22:46:08.413 E/RILD    ( 6018): SelectE911RatDeterminer - Type: DEFAULT (Reason: CS domain)
08-19 22:46:08.415 E/RILD2   ( 6018): Start, NetlinkUtils thread Started
08-19 22:46:08.415 E/RILD    ( 6018): Start, NetlinkUtils thread Started
08-19 22:46:08.416 E/RILD    ( 6018): create Thread[NU]
08-19 22:46:08.416 E/RILD2   ( 6018): create Thread[NU2]
08-19 22:46:08.416 E/RILD2   ( 6018): Run(): NetlinkUtilsRunnable
08-19 22:46:08.416 E/RILD    ( 6018): Run(): NetlinkUtilsRunnable
08-19 22:46:08.440 E/RILD    ( 6018): [C] Initialize(): Is initialized: 0
08-19 22:46:08.440 E/RILD2   ( 6018): [C] Initialize(): Is initialized: 0
08-19 22:46:08.441 E/RILD    ( 6018): create Thread[ESAR]
08-19 22:46:08.441 E/RILD2   ( 6018): create Thread[ESAR2]
08-19 22:46:08.441 E/RILD    ( 6018): DoEvent - data call is nullptr
08-19 22:46:08.442 E/RILD2   ( 6018): DoEvent - data call is nullptr
08-19 22:46:08.442 E/RILD2   ( 6018): create Thread[RDAR2]
08-19 22:46:08.442 E/RILD    ( 6018): create Thread[RDAR]
08-19 22:46:08.443 E/RILD2   ( 6018): create Thread[MBM2]
08-19 22:46:08.443 E/RILD    ( 6018): create Thread[MBM]
08-19 22:46:08.449 D/RILD    ( 6018): RIL_Init rilInit completed
08-19 22:46:08.449 I/RILC    ( 6018): SIM_COUNT: 2
08-19 22:46:08.449 E/RILC    ( 6018): RIL_register: RIL version 15
08-19 22:46:08.449 I/RILC    ( 6018): s_registerCalled flag set, 1
08-19 22:46:08.453 D/RILC    ( 6018): register IRadioConfig AIDL service success
08-19 22:46:08.454 D/RILC    ( 6018): register IRadioData AIDL service success : slot1
08-19 22:46:08.455 D/RILC    ( 6018): register IRadioData AIDL service success : slot2
08-19 22:46:08.457 D/RILC    ( 6018): register IRadioMessaging AIDL service success : slot1
08-19 22:46:08.458 D/RILC    ( 6018): register IRadioMessaging AIDL service success : slot2
08-19 22:46:08.459 D/RILC    ( 6018): register IRadioModem AIDL service success : slot1
08-19 22:46:08.460 D/RILC    ( 6018): register IRadioModem AIDL service success : slot2
08-19 22:46:08.462 D/RILC    ( 6018): register IRadioNetwork AIDL service success : slot1
08-19 22:46:08.463 D/RILC    ( 6018): register IRadioNetwork AIDL service success : slot2
08-19 22:46:08.464 D/RILC    ( 6018): register IRadioSim AIDL service success : slot1
08-19 22:46:08.465 D/RILC    ( 6018): register IRadioSim AIDL service success : slot2
08-19 22:46:08.466 D/RILC    ( 6018): register IRadioVoice AIDL service success : slot1
08-19 22:46:08.468 D/RILC    ( 6018): register IRadioVoice AIDL service success : slot2
08-19 22:46:08.469 D/RILC    ( 6018): register ISehRadioNetwork AIDL service success : slot1
08-19 22:46:08.471 D/RILC    ( 6018): register ISehRadioNetwork AIDL service success : slot2
08-19 22:46:08.472 D/RILC    ( 6018): register ISehRadioData AIDL service success : slot1
08-19 22:46:08.474 D/RILC    ( 6018): register ISehRadioData AIDL service success : slot2
08-19 22:46:08.475 D/RILC    ( 6018): register ISehRadioSim AIDL service success : slot1
08-19 22:46:08.477 D/RILC    ( 6018): register ISehRadioSim AIDL service success : slot2
08-19 22:46:08.478 D/RILC    ( 6018): register IRadioMessaging AIDL service success : slot1
08-19 22:46:08.480 D/RILC    ( 6018): register IRadioMessaging AIDL service success : slot2
08-19 22:46:08.480 I/RILC    ( 6018): RILHIDL called registerService
08-19 22:46:08.480 D/RILD    ( 6018): RIL_Init RIL_register completed
08-19 22:46:08.480 D/RILD    ( 6018): RIL_register_socket started
08-19 22:46:08.480 D/RIL_UIM_SOCKET( 6018): Adding socket with id: 0
08-19 22:46:08.480 D/RIL_UIM_SOCKET( 6018): Adding socket with id: 1
08-19 22:46:08.480 I/RILC    ( 6018): RIL_register_socket: calling registerService
08-19 22:46:08.480 D/RIL_SAP ( 6018): registerService: starting ISap slot1 for slotId 0
08-19 22:46:08.484 D/RIL_SAP ( 6018): registerService: started ISap slot1 status 0
08-19 22:46:08.484 D/RIL_SAP ( 6018): registerService: starting ISap slot2 for slotId 1
08-19 22:46:08.486 D/RIL_SAP ( 6018): registerService: started ISap slot2 status 0
08-19 22:46:08.487 D/RILD    ( 6018): RIL_register_socket completed
08-19 22:46:08.487 E/RILC    ( 6018): rilc_thread_pool
08-19 22:46:08.604 E/RILClient( 5870): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:08.605 E/RILClient( 5870): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:08.605 E/RILClient( 5870): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:08.605 E/RILClient( 5870): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:08.605 E/RILClient( 5870): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:08.671 D/boot    ( 6000): cbd: load_cp_image_by_stage: 2 stage complelte
08-19 22:46:08.671 D/boot    ( 6000): cbd: load_cp_image_by_stage: stage=3(3), b_off=0x0251d5c0, m_off=0x06900000, b_size=0x00550514, mode=0x00000000
08-19 22:46:08.712 D/boot    ( 6000): cbd: load_cp_image_by_stage: 3 stage complelte
08-19 22:46:08.712 D/boot    ( 6000): cbd: load_cp_image_by_stage: stage=4(4), b_off=0x00000000, m_off=0x06300000, b_size=0x00100000, mode=0x00000000
08-19 22:46:08.714 D/boot    ( 6000): cbd: load_cp_image_by_stage: 4 stage complelte
08-19 22:46:08.715 D/boot    ( 6000): cbd: start_shannon310_boot: Request Security : secure mode
08-19 22:46:08.715 D/boot    ( 6000): cbd: std_security_req: security_req: 7:8000:410:0
08-19 22:46:08.715 D/boot    ( 6000): cbd: std_security_req: orig cpu_set[0]=0x000000ff
08-19 22:46:08.715 D/boot    ( 6000): cbd: std_security_req: new cpu_set[0]=0x000000fe
08-19 22:46:08.722 D/boot    ( 6000): cbd: std_security_req: restore cpu_set[0]=0x000000ff
08-19 22:46:08.722 D/boot    ( 6000): cbd: std_security_req: security_req: 7:6900000:550514:0
08-19 22:46:08.722 D/boot    ( 6000): cbd: std_security_req: orig cpu_set[0]=0x000000ff
08-19 22:46:08.722 D/boot    ( 6000): cbd: std_security_req: new cpu_set[0]=0x000000fe
08-19 22:46:08.742 D/boot    ( 6000): cbd: std_security_req: restore cpu_set[0]=0x000000ff
08-19 22:46:08.742 D/boot    ( 6000): cbd: start_shannon310_boot: Request security : secure mode
08-19 22:46:08.742 D/boot    ( 6000): cbd: std_security_req: security_req: 0:1ca8:251b4d4:0
08-19 22:46:08.742 D/boot    ( 6000): cbd: std_security_req: orig cpu_set[0]=0x000000ff
08-19 22:46:08.742 D/boot    ( 6000): cbd: std_security_req: new cpu_set[0]=0x000000fe
08-19 22:46:08.852 D/boot    ( 6000): cbd: std_security_req: restore cpu_set[0]=0x000000ff
08-19 22:46:08.852 E/boot    ( 6000): cbd: (ERR! No such file or directory) get_factory_prop: /efs/factory.prop open fail(not support)
08-19 22:46:08.852 D/boot    ( 6000): cbd: set_sim_configuration: sim count: -22 (echo to ds_detect file)
08-19 22:46:08.852 D/boot    ( 6000): cbd: start_shannon310_boot: Start CP bootloader
08-19 22:46:08.872 D/boot    ( 6000): cbd: start_shannon310_boot: Handshake
08-19 22:46:08.872 D/boot    ( 6000): cbd: std_udl_req_resp: request:0x0000900D
08-19 22:46:08.875 D/boot    ( 6000): cbd: std_udl_req_resp: request:0x00009F00
08-19 22:46:08.875 D/boot    ( 6000): cbd: start_shannon310_boot: Complete normal bootup
08-19 22:46:09.460 D/boot    ( 6000): cbd: open_srinfo_last: open last_sr_info file - /data/vendor/log/cbd/err/last_sr_info_umts
08-19 22:46:09.461 E/boot    ( 6000): cbd: (ERR! No such file or directory) open_srinfo_last: last_sr_info open fail(No such file or directory)
08-19 22:46:09.461 D/boot    ( 6000): cbd: restore_srinfo: sr_info_last open fail(-1)
08-19 22:46:09.471 D/boot    ( 6000): cbd: boot_wake_lock: /sys/power/wake_unlock/ss310
08-19 22:46:09.471 D/boot    ( 6000): cbd: main: Boot up process done!!!
08-19 22:46:09.471 D/boot    ( 6000): cbd: status_loop: CP status_loop start (modem = 12)
08-19 22:46:09.473 D/boot    ( 6000): cbd: status_loop: Wait event from modem 12
08-19 22:46:09.547 E/RILClient( 5843): Connect_RILD_Internal: Connecting failed. Connection refused(111)
08-19 22:46:09.646 E/RILD    ( 6018): create Thread[SINR]
08-19 22:46:09.646 E/RILD2   ( 6018): create Thread[ICR2]
08-19 22:46:09.647 E/RILD    ( 6018): create Thread[ICR]
08-19 22:46:09.648 E/RILD    ( 6018): create Thread[ICR]
08-19 22:46:09.650 D/SemNativeCarrierFeature( 6018): register vendor.samsung.hardware.radio.channel.ISehRadioChannel/imsd service success
08-19 22:46:09.650 E/RILD    ( 6018): create Thread[HAR]
08-19 22:46:09.650 D/SemNativeCarrierFeature( 6018): register vendor.samsung.hardware.radio.channel.ISehRadioChannel/imsd2 service success
08-19 22:46:09.650 E/RILD    ( 6018): create Thread[ICR]
08-19 22:46:09.650 E/RILD2   ( 6018): create Thread[HAR2]
08-19 22:46:09.651 E/RILD2   ( 6018): create Thread[ICR2]
08-19 22:46:09.651 D/SemNativeCarrierFeature( 6018): register vendor.samsung.hardware.radio.channel.ISehRadioChannel/epdgd service success
08-19 22:46:09.652 E/RILD    ( 6018): create Thread[HAR]
08-19 22:46:09.652 E/RILD    ( 6018): create Thread[ICR]
08-19 22:46:09.653 E/RILD    ( 6018): create Thread[OCR]
08-19 22:46:09.653 D/SemNativeCarrierFeature( 6018): register vendor.samsung.hardware.radio.channel.ISehRadioChannel/epdgd2 service success
08-19 22:46:09.653 E/RILD2   ( 6018): create Thread[HAR2]
08-19 22:46:09.654 E/RILD2   ( 6018): create Thread[ICR2]
08-19 22:46:09.654 E/RILD2   ( 6018): create Thread[OCR2]
08-19 22:46:09.655 D/RILC    ( 6018): register ISehRadioBridge AIDL service success slot1
08-19 22:46:09.657 D/RILC    ( 6018): register ISehRadioBridge AIDL service success slot2
08-19 22:46:10.505 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:10.510 E/RILD    ( 6018): OnRadioStateChanged: RADIO_OFF : mIsDeviceReadyNotiNeed = NOT_CONNECTED
08-19 22:46:10.510 E/RILC    ( 6018): sendIndication: sehRadioBridgeService || mSehRadioBridgeIndication == NULL
08-19 22:46:10.547 D/RILClient( 5843): Connect_RILD_Internal: socket allocated 8
08-19 22:46:10.548 D/RILClient( 5843): Connect_RILD_Internal: Success to connect
08-19 22:46:10.549 E/RILD    ( 6018): OemClient::ProcessBuffer() from[9], token[1], datalen[24]
08-19 22:46:10.549 D/RILClient( 5843): RxReaderFunc(): close(8)
08-19 22:46:10.662 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:10.662 E/RILD2   ( 6018): Failed to get Imei manager
08-19 22:46:10.663 E/RILD2   ( 6018): OnRadioStateChanged: RADIO_OFF : mIsDeviceReadyNotiNeed = NOT_CONNECTED
08-19 22:46:10.664 E/RILC    ( 6018): sendIndication: sehRadioBridgeService || mSehRadioBridgeIndication == NULL
08-19 22:46:10.667 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:10.672 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:10.672 E/RILD    ( 6018): Oem OnRequestComplete:(9)
08-19 22:46:10.673 E/RILD2   ( 6018): OnRadioCapabilityUpdateNoti - Make RadioCapability
08-19 22:46:10.682 E/RILD    ( 6018): OnRadioCapabilityUpdateNoti - Make RadioCapability
08-19 22:46:11.226 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.227 E/RILC    ( 6018): simStatusChangedInd: mRadioSimIndication == NULL
08-19 22:46:11.227 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:11.228 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.229 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.229 E/RILC    ( 6018): simStatusChangedInd: mRadioSimIndication == NULL
08-19 22:46:11.278 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.278 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.285 E/RILC    ( 6018): radioStateChangedInd: mRadioModemIndication == NULL
08-19 22:46:11.336 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.336 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.338 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.338 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:11.339 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:12.238 E/RILC    ( 6018): networkStateChangedInd: mRadioNetworkIndication == NULL
08-19 22:46:12.239 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:12.239 E/RILD    ( 6018): IO channel write error.
08-19 22:46:12.239 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:17.972 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:18.101 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:18.734 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:19.779 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:19.780 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:19.943 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:19.995 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:19.995 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.252 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.253 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.254 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.255 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.528 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:20.638 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:20.640 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 25
08-19 22:46:20.687 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.687 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:20.718 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 26
08-19 22:46:20.719 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 27
08-19 22:46:20.719 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:20.791 W/CarrierConfigManager( 6138): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:20.832 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 28
08-19 22:46:20.832 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:20.857 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 29
08-19 22:46:20.857 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:20.886 W/CarrierConfigManager( 6375): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:20.896 W/CarrierConfigManager( 6375): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:20.945 D/TelephonyRegistry( 6138): systemRunning register for intents
08-19 22:46:21.187 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:21.300 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 30
08-19 22:46:21.300 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:21.318 W/CarrierConfigManager( 6524): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:21.701 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:21.712 W/CarrierConfigManager( 6375): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:21.732 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:21.751 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 31
08-19 22:46:21.981 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.041 D/TelephonyComponentFactory( 6608): validated paths: null
08-19 22:46:22.041 D/TelephonyComponentFactory( 6608): Total components injected: 0
08-19 22:46:22.043 D/TelephonyRegistry( 6138): notifyCellLocationForSubscriber: subId=2147483647 cellIdentity=null
08-19 22:46:22.045 D/TelephonyRegistry( 6138): notifyCellLocationForSubscriber: subId=2147483647 cellIdentity=null
08-19 22:46:22.046 D/TDC     ( 6608): updateOrInsert: inserting: Modem { uuid=modem, state=0, rilModel=0, rat={}, maxActiveVoiceCall=1, maxActiveDataCall=1, maxStandby=1 }
08-19 22:46:22.046 D/TDC     ( 6608): updateOrInsert: inserting: Sim { uuid=sim, modemUuid=modem, state=0 }
08-19 22:46:22.076 D/MetricsCollector( 6608): registered
08-19 22:46:22.082 D/CdmaSSM ( 6608): subscriptionSource from settings: 0
08-19 22:46:22.082 I/PhoneFactory( 6608): Cdma Subscription set to 0
08-19 22:46:22.082 I/PhoneFactory( 6608): Network Mode set to 9
08-19 22:46:22.084 D/RILJ    ( 6608): RIL: init allowedNetworkTypes=316295 cdmaSubscription=0) [PHONEnull]
08-19 22:46:22.129 D/RadioModemProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.129 D/RILJ    ( 6608): Linked to death for service MODEM [PHONE0]
08-19 22:46:22.130 D/RILC    ( 6018): SemRadioModem::setResponseFunctions
08-19 22:46:22.134 D/RILJ    ( 6608): [0000]> GET_HARDWARE_CONFIG [PHONE0]
08-19 22:46:22.136 D/RILJ    ( 6608): [0000]< GET_HARDWARE_CONFIG error 6 [PHONE0]
08-19 22:46:22.137 D/RilRequest( 6608): [0000]< GET_HARDWARE_CONFIG error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret=  result=null
08-19 22:46:22.139 E/RILJ    ( 6608): Feature android.hardware.telephony.ims is declared, but service IMS is missing [PHONE0]
08-19 22:46:22.144 D/RILJ    ( 6608): HAL version of RADIO: 2.0 [PHONE0]
08-19 22:46:22.147 D/RadioDataProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.147 D/RILJ    ( 6608): Linked to death for service DATA [PHONE0]
08-19 22:46:22.148 D/RILJ    ( 6608): HAL version of DATA: 2.0 [PHONE0]
08-19 22:46:22.148 D/RILC    ( 6018): SemRadioData::setResponseFunctions
08-19 22:46:22.151 D/RadioMessagingProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.152 D/RILJ    ( 6608): Linked to death for service MESSAGING [PHONE0]
08-19 22:46:22.152 D/RILJ    ( 6608): HAL version of MESSAGING: 2.0 [PHONE0]
08-19 22:46:22.153 D/RILC    ( 6018): setResponseFunctions
08-19 22:46:22.154 D/RILJ    ( 6608): HAL version of MODEM: 2.0 [PHONE0]
08-19 22:46:22.159 D/RadioNetworkProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.159 D/RILJ    ( 6608): Linked to death for service NETWORK [PHONE0]
08-19 22:46:22.159 D/RILJ    ( 6608): HAL version of NETWORK: 2.0 [PHONE0]
08-19 22:46:22.160 D/RILC    ( 6018): SemRadioNetwork::setResponseFunctions
08-19 22:46:22.160 D/RILC    ( 6018): The version of IRadioNetwork AIDL service: 3
08-19 22:46:22.165 D/RadioSimProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.167 D/RILJ    ( 6608): Linked to death for service SIM [PHONE0]
08-19 22:46:22.167 D/RILJ    ( 6608): HAL version of SIM: 2.0 [PHONE0]
08-19 22:46:22.168 D/RILC    ( 6018): SemRadioSim::setResponseFunctions
08-19 22:46:22.171 D/RadioVoiceProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.171 D/RILJ    ( 6608): Linked to death for service VOICE [PHONE0]
08-19 22:46:22.172 D/RILJ    ( 6608): HAL version of VOICE: 2.0 [PHONE0]
08-19 22:46:22.172 D/RILC    ( 6018): SemRadioVoice::setResponseFunctions
08-19 22:46:22.173 D/RILC    ( 6018): rilConnectedInd
08-19 22:46:22.173 D/RILC    ( 6018): radioStateChangedInd: radioState 10
08-19 22:46:22.173 I/RILC    ( 6018): RIL Daemon version: Samsung RIL v5.0
08-19 22:46:22.173 D/RILJ    ( 6608): Not initializing IMS (not supported) [PHONE0]
08-19 22:46:22.173 I/PhoneFactory( 6608): Network Mode set to 9
08-19 22:46:22.173 D/RILJ    ( 6608): RIL: init allowedNetworkTypes=316295 cdmaSubscription=0) [PHONEnull]
08-19 22:46:22.176 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:22.176 D/RILJ    ( 6608): [UNSL]< UNSOL_RIL_CONNECTED [PHONE0]
08-19 22:46:22.179 D/RILJ    ( 6608): [0002]> RADIO_POWER on = false forEmergencyCall= false preferredForEmergencyCall=false [PHONE0]
08-19 22:46:22.180 D/RILC    ( 6018): setRadioPower: serial 2, powerOn 0, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:22.181 D/RILJ    ( 6608): [0003]> CDMA_SET_SUBSCRIPTION_SOURCE cdmaSubscription = 0 [PHONE0]
08-19 22:46:22.182 D/RILJ    ( 6608): [0003]< CDMA_SET_SUBSCRIPTION_SOURCE error 12 [PHONE0]
08-19 22:46:22.182 D/RilRequest( 6608): [0003]< CDMA_SET_SUBSCRIPTION_SOURCE error: com.android.internal.telephony.CommandException: SUBSCRIPTION_NOT_AVAILABLE ret= result=null
08-19 22:46:22.183 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:22.183 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 1 [PHONE0]
08-19 22:46:22.189 D/RadioModemProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.189 D/RILJ    ( 6608): Linked to death for service MODEM [PHONE1]
08-19 22:46:22.190 D/RILC    ( 6018): SemRadioModem::setResponseFunctions
08-19 22:46:22.192 D/RILJ    ( 6608): [0005]> GET_HARDWARE_CONFIG [PHONE1]
08-19 22:46:22.194 D/RILJ    ( 6608): [0005]< GET_HARDWARE_CONFIG error 6 [PHONE1]
08-19 22:46:22.194 D/RilRequest( 6608): [0005]< GET_HARDWARE_CONFIG error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret=  result=null
08-19 22:46:22.196 E/RILJ    ( 6608): Feature android.hardware.telephony.ims is declared, but service IMS is missing [PHONE1]
08-19 22:46:22.200 D/RILJ    ( 6608): HAL version of RADIO: 2.0 [PHONE1]
08-19 22:46:22.205 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:22.205 E/RILD    ( 6018): IO channel write error.
08-19 22:46:22.205 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:22.205 D/RadioDataProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.205 D/RILJ    ( 6608): Linked to death for service DATA [PHONE1]
08-19 22:46:22.205 D/RILJ    ( 6608): HAL version of DATA: 2.0 [PHONE1]
08-19 22:46:22.206 D/RILC    ( 6018): SemRadioData::setResponseFunctions
08-19 22:46:22.206 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:22.206 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_NETWORK_STATE_CHANGED [PHONE0]
08-19 22:46:22.215 D/RadioMessagingProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.215 D/RILJ    ( 6608): Linked to death for service MESSAGING [PHONE1]
08-19 22:46:22.216 D/RILC    ( 6018): setResponseFunctions
08-19 22:46:22.216 D/RILJ    ( 6608): HAL version of MESSAGING: 2.0 [PHONE1]
08-19 22:46:22.217 D/RILJ    ( 6608): HAL version of MODEM: 2.0 [PHONE1]
08-19 22:46:22.220 D/RadioNetworkProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.220 D/RILJ    ( 6608): Linked to death for service NETWORK [PHONE1]
08-19 22:46:22.221 D/RILJ    ( 6608): HAL version of NETWORK: 2.0 [PHONE1]
08-19 22:46:22.221 D/RILC    ( 6018): SemRadioNetwork::setResponseFunctions
08-19 22:46:22.221 D/RILC    ( 6018): The version of IRadioNetwork AIDL service: 3
08-19 22:46:22.223 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:22.223 E/RILD    ( 6018): IO channel write error.
08-19 22:46:22.223 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:22.223 D/RILC    ( 6018): setRadioPowerResponse: serial 2
08-19 22:46:22.223 D/RILJ    ( 6608): [0002]< RADIO_POWER  [PHONE0]
08-19 22:46:22.224 D/RILC    ( 6018): radioStateChangedInd: radioState 0
08-19 22:46:22.225 E/RILD    ( 6018): OnRadioStateChanged: RADIO_OFF : mIsDeviceReadyNotiNeed = NOT_CONNECTED
08-19 22:46:22.225 D/RadioSimProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.225 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:22.225 D/RILJ    ( 6608): Linked to death for service SIM [PHONE1]
08-19 22:46:22.225 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 0 [PHONE0]
08-19 22:46:22.226 D/RILJ    ( 6608): HAL version of SIM: 2.0 [PHONE1]
08-19 22:46:22.226 D/RILC    ( 6018): SemRadioSim::setResponseFunctions
08-19 22:46:22.229 D/RadioVoiceProxy( 6608): AIDL initialized mHalVersion=2.0
08-19 22:46:22.229 D/RILJ    ( 6608): Linked to death for service VOICE [PHONE1]
08-19 22:46:22.229 D/RILJ    ( 6608): HAL version of VOICE: 2.0 [PHONE1]
08-19 22:46:22.229 D/RILC    ( 6018): SemRadioVoice::setResponseFunctions
08-19 22:46:22.230 D/RILC    ( 6018): rilConnectedInd
08-19 22:46:22.230 D/RILC    ( 6018): radioStateChangedInd: radioState 10
08-19 22:46:22.230 I/RILC    ( 6018): RIL Daemon version: Samsung RIL v5.0
08-19 22:46:22.230 D/RILJ    ( 6608): Not initializing IMS (not supported) [PHONE1]
08-19 22:46:22.231 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE1]
08-19 22:46:22.231 D/RILJ    ( 6608): [UNSL]< UNSOL_RIL_CONNECTED [PHONE1]
08-19 22:46:22.232 D/UiccController( 6608): Creating UiccController
08-19 22:46:22.232 D/UiccController( 6608): config_num_physical_slots = 1
08-19 22:46:22.234 D/RILJ    ( 6608): [0009]> RADIO_POWER on = false forEmergencyCall= false preferredForEmergencyCall=false [PHONE1]
08-19 22:46:22.234 D/RILC    ( 6018): setRadioPower: serial 9, powerOn 0, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:22.238 D/RILJ    ( 6608): [0010]> CDMA_SET_SUBSCRIPTION_SOURCE cdmaSubscription = 0 [PHONE1]
08-19 22:46:22.239 D/RILJ    ( 6608): [0010]< CDMA_SET_SUBSCRIPTION_SOURCE error 12 [PHONE1]
08-19 22:46:22.239 D/RilRequest( 6608): [0010]< CDMA_SET_SUBSCRIPTION_SOURCE error: com.android.internal.telephony.CommandException: SUBSCRIPTION_NOT_AVAILABLE ret= result=null
08-19 22:46:22.240 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE1]
08-19 22:46:22.240 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 1 [PHONE1]
08-19 22:46:22.242 D/RILC    ( 6018): setRadioPowerResponse: serial 9
08-19 22:46:22.243 D/RILJ    ( 6608): [0009]< RADIO_POWER  [PHONE1]
08-19 22:46:22.244 D/RILC    ( 6018): radioStateChangedInd: radioState 0
08-19 22:46:22.245 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE1]
08-19 22:46:22.245 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 0 [PHONE1]
08-19 22:46:22.246 E/RILD2   ( 6018): OnRadioStateChanged: RADIO_OFF : mIsDeviceReadyNotiNeed = NOT_CONNECTED
08-19 22:46:22.256 D/RadioConfigProxy( 6608): setAidl: setting HAL version to version = 2.0
08-19 22:46:22.257 D/RadioConfig( 6608): [0013]> GET_HAL_DEVICE_CAPABILITIES
08-19 22:46:22.258 D/RILC    ( 6018): SemRadioConfig::setResponseFunctions
08-19 22:46:22.258 E/RILC    ( 6018): getHalDeviceCapabilitiesResponse: Invalid response
08-19 22:46:22.258 D/RILUtils( 6608): Radio Hal Version = 2.0
08-19 22:46:22.259 D/RILUtils( 6608): CAPABILITY_USES_ALLOWED_NETWORK_TYPES_BITMASK
08-19 22:46:22.259 D/RILUtils( 6608): CAPABILITY_SIM_PHONEBOOK_IN_MODEM
08-19 22:46:22.259 D/RilRequest( 6608): [0013]< GET_HAL_DEVICE_CAPABILITIES error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret=[CAPABILITY_USES_ALLOWED_NETWORK_TYPES_BITMASK, CAPABILITY_SIM_PHONEBOOK_IN_MODEM] result={ when=-32s190ms what=100 target=com.android.internal.telephony.RadioInterfaceCapabilityController }
08-19 22:46:22.259 E/RadioConfigResponseAidl( 6608): [0013]< GET_HAL_DEVICE_CAPABILITIES error 1
08-19 22:46:22.259 E/RadioInterfaceCapabilityController( 6608): setupRadioInterfaceCapabilities: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE
08-19 22:46:22.259 D/RadioInterfaceCapabilityController( 6608): setupRadioInterfaceCapabilities: mRadioInterfaceCapabilities now setup
08-19 22:46:22.269 D/PinStorage( 6608): KeyStore: alias PinStorage_longTerm_always_key exists
08-19 22:46:22.269 D/PinStorage( 6608): Device is locked - Postponing initialization
08-19 22:46:22.269 I/PhoneFactory( 6608): Creating SubscriptionManagerService
08-19 22:46:22.271 D/SMSVC   ( 6608): Created SubscriptionManagerService
08-19 22:46:22.286 D/SDMGR   ( 6608): Created SubscriptionDatabaseManager.
08-19 22:46:22.287 D/SDMGR   ( 6608): loadDatabaseInternal
08-19 22:46:22.292 W/CarrierConfigManager( 6375): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.293 D/SMSVC   ( 6608): broadcastSubId action: android.intent.action.ACTION_DEFAULT_DATA_SUBSCRIPTION_CHANGED subId= -1
08-19 22:46:22.296 D/SMSVC   ( 6608): broadcastSubId action: android.intent.action.ACTION_DEFAULT_VOICE_SUBSCRIPTION_CHANGED subId= -1
08-19 22:46:22.298 W/CarrierConfigManager( 6138): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.300 D/SMSVC   ( 6608): broadcastSubId action: android.telephony.action.DEFAULT_SMS_SUBSCRIPTION_CHANGED subId= -1
08-19 22:46:22.310 D/SMSVC   ( 6608): Registered iSub service
08-19 22:46:22.314 D/SDMGR   ( 6608): Loaded 2 records from the subscription database.
08-19 22:46:22.315 D/SDMGR   ( 6608):   [SubscriptionInfoInternal: id=1 iccId=89984320002722354824 simSlotIndex=-1 portIndex=-1 isEmbedded=0 isRemovableEmbedded=0 carrierId=1967 displayName=Irancell carrierName=Irancell isOpportunistic=0 groupUuid= groupOwner= displayNameSource=SIM_SPN iconTint=-4716942 number=+989337852278 dataRoaming=1 mcc=432 mnc=35 ehplmns= hplmns=43235 cardString=89984320002722354824 cardId=0 nativeAccessRules= carrierConfigAccessRules= countryIso=ir profileClass=-1 type=LOCAL_SIM areUiccApplicationsEnabled=1 usageSetting=DEFAULT isEnhanced4GModeEnabled=-1 isVideoTelephonyEnabled=-1 isWifiCallingEnabled=-1 isWifiCallingEnabledForRoaming=-1 wifiCallingMode=UNKNOWN wifiCallingModeForRoaming=UNKNOWN enabledMobileDataPolicies= imsi=432350499141789 rcsUceEnabled=0 crossSimCallingEnabled=0 rcsConfig= allowedNetworkTypesForReasons=user=316295 deviceToDeviceStatusSharingPreference=0 isVoImsOptInEnabled=0 deviceToDeviceStatusSharingContacts= numberFromCarrier= numberFromIms= userId=-10000 isSatelliteEnabled=0 satellite_attach_enabled_for_carrier=1 getOnlyNonTerrestrialNetwork=0 isGroupDisabled=false serviceCapabilities=7 transferStatus=0 satelliteEntitlementStatus=0 satelliteEntitlementPlmns= isSatelliteESOSSupported=0 isSatelliteProvisionedForNonIpDatagram=0]
08-19 22:46:22.315 D/SDMGR   ( 6608):   [SubscriptionInfoInternal: id=2 iccId=89981139000610214099 simSlotIndex=-1 portIndex=-1 isEmbedded=0 isRemovableEmbedded=0 carrierId=1562 displayName=IR-MCI carrierName=IR-MCI isOpportunistic=0 groupUuid= groupOwner= displayNameSource=SIM_SPN iconTint=-16749196 number=+989165045444 dataRoaming=1 mcc=432 mnc=11 ehplmns=43211 hplmns= cardString=89981139000610214099 cardId=1 nativeAccessRules= carrierConfigAccessRules= countryIso=ir profileClass=-1 type=LOCAL_SIM areUiccApplicationsEnabled=1 usageSetting=DEFAULT isEnhanced4GModeEnabled=-1 isVideoTelephonyEnabled=-1 isWifiCallingEnabled=-1 isWifiCallingEnabledForRoaming=-1 wifiCallingMode=UNKNOWN wifiCallingModeForRoaming=UNKNOWN enabledMobileDataPolicies=3 imsi=432113961021409 rcsUceEnabled=0 crossSimCallingEnabled=0 rcsConfig= allowedNetworkTypesForReasons=user=316295 deviceToDeviceStatusSharingPreference=0 isVoImsOptInEnabled=0 deviceToDeviceStatusSharingContacts= numberFromCarrier= numberFromIms= userId=-10000 isSatelliteEnabled=0 satellite_attach_enabled_for_carrier=1 getOnlyNonTerrestrialNetwork=0 isGroupDisabled=false serviceCapabilities=7 transferStatus=0 satelliteEntitlementStatus=0 satelliteEntitlementPlmns= isSatelliteESOSSupported=0 isSatelliteProvisionedForNonIpDatagram=0]
08-19 22:46:22.317 I/PhoneFactory( 6608): Creating Phone with type = 1 phoneId = 0
08-19 22:46:22.318 D/Phone-0 ( 6608): mDoesRilSendMultipleCallRing=true
08-19 22:46:22.319 D/Phone-0 ( 6608): mCallRingDelay=3000
08-19 22:46:22.319 D/TelephonyAdminReceiver( 6608): No user manager. Attempting to resolve one.
08-19 22:46:22.321 D/TelephonyTester-0( 6608): register for intent action=com.android.internal.telephony.action_detached
08-19 22:46:22.321 D/TelephonyTester-0( 6608): register for intent action=com.android.internal.telephony.action_attached
08-19 22:46:22.322 D/TelephonyTester-0( 6608): register for intent action=com.android.internal.telephony.TestServiceState
08-19 22:46:22.322 D/TelephonyTester-0( 6608): register for intent action=com.android.internal.telephony.TestChangeNumber
08-19 22:46:22.349 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.349 D/TelephonyAnalytics( 6608): stopped listener
08-19 22:46:22.353 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.353 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.356 E/SatelliteController( 6608): SatelliteController was not yet initialized.
08-19 22:46:22.359 D/SmsDispatchersController( 6608): SmsDispatchersController created
08-19 22:46:22.363 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=unknown mSmsSendDisabled=false
08-19 22:46:22.365 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=3gpp2 mSmsSendDisabled=false
08-19 22:46:22.365 D/CdmaSMSDispatcher( 6608): CdmaSMSDispatcher created
08-19 22:46:22.379 D/GsmInboundSmsHandler( 6608): created InboundSmsHandler
08-19 22:46:22.397 D/CdmaInboundSmsHandler( 6608): created InboundSmsHandler
08-19 22:46:22.407 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=3gpp mSmsSendDisabled=false
08-19 22:46:22.407 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher created
08-19 22:46:22.413 D/CdmaSSM ( 6608): subscriptionSource from settings: 0
08-19 22:46:22.413 D/CdmaSSM ( 6608): cdmaSSM constructor: 0
08-19 22:46:22.422 I/GsmCdmaPhone( 6608): [0] enable_identifier_disclosure_transparency_unsol_events is on. Registering for cellular identifier disclosures from phone 0
08-19 22:46:22.424 I/GsmCdmaPhone( 6608): [0] enable_modem_cipher_transparency_unsol_events is on. Registering for security algorithm updates from phone 0
08-19 22:46:22.424 D/GsmCdmaPhone( 6608): [0] initializeCarrierApps
08-19 22:46:22.429 D/GsmCdmaPhone( 6608): [0] Precise phone type 1
08-19 22:46:22.429 D/RILJ    ( 6608): setPhoneType=1 old value=0 [PHONE0]
08-19 22:46:22.432 D/CarrierActionAgent( 6608): [0]Creating CarrierActionAgent
08-19 22:46:22.433 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.433 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.440 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.448 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.448 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.449 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.450 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.453 D/NRM-C-0 ( 6608): registerForNetworkRegistrationInfoChanged
08-19 22:46:22.454 D/NRM-I-0 ( 6608): registerForNetworkRegistrationInfoChanged
08-19 22:46:22.465 D/RILJ    ( 6608): [0014]> SIGNAL_STRENGTH [PHONE0]
08-19 22:46:22.465 E/RILC    ( 6018): getSignalStrengthResponse: Invalid response
08-19 22:46:22.466 D/SST     ( 6608): [0] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=0
08-19 22:46:22.468 D/RILJ    ( 6608): [0014]< SIGNAL_STRENGTH error 1 [PHONE0]
08-19 22:46:22.468 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.469 D/RilRequest( 6608): [0014]< SIGNAL_STRENGTH error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret=SignalStrength:{mCdma=CellSignalStrengthCdma: cdmaDbm=0 cdmaEcio=0 evdoDbm=0 evdoEcio=0 evdoSnr=0 level=4,mGsm=CellSignalStrengthGsm: rssi=-113 ber=0 mTa=0 mLevel=0,mWcdma=CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-120 ecno=-24 level=0,mTdscdma=CellSignalStrengthTdscdma: rssi=-113 ber=0 rscp=-120 level=0,mLte=CellSignalStrengthLte: rssi=-113 rsrp=2147483647 rsrq=0 rssnr=0 cqiTableIndex=2147483647 cqi=0 ta=0 level=1 parametersUseForLevel=1,mNr=CellSignalStrengthNr:{ csiRsrp = 2147483647 csiRsrq = 2147483647 csiCqiTableIndex = 2147483647 csiCqiReport = [] ssRsrp = 2147483647 ssRsrq = 0 ssSinr = 0 level = 0 parametersUseForLevel = 1 timingAdvance = 2147483647 },primary=CellSignalStrengthLte} result={ when=-32s401ms what=6 target=com.android.internal.telephony.SignalStrengthController }
08-19 22:46:22.469 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:22.472 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.472 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.487 D/EmergencyNumberTracker( 6608): [0] asset emergency database is loaded. Ver: 2 Phone Id: 0 countryIso: 
08-19 22:46:22.488 E/EmergencyNumberTracker( 6608): [0]Cache ota emergency database IOException: java.io.FileNotFoundException: /data/misc/emergencynumberdb/emergency_number_db: open failed: ENOENT (No such file or directory)
08-19 22:46:22.488 D/EmergencyNumberTracker( 6608): [0]Using Asset Emergency database. Version: 2
08-19 22:46:22.516 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.519 D/DNC-0   ( 6608): DataNetworkController created.
08-19 22:46:22.523 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.524 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.527 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.527 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.528 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.529 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.538 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.538 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.555 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.556 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.558 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.558 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.560 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.560 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.561 E/DSM-I-0 ( 6608): Can't find the binding package
08-19 22:46:22.562 D/DCM-0   ( 6608): DataConfigManager created.
08-19 22:46:22.569 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.583 D/DCM-0   ( 6608): Carrier config updated. Config is not carrier specific.
08-19 22:46:22.592 D/DSMGR-0 ( 6608): DataSettingsManager created.
08-19 22:46:22.611 D/DSRM-0  ( 6608): DataStallRecoveryManager created.
08-19 22:46:22.614 D/DSRM-0  ( 6608): Enabled actions is null
08-19 22:46:22.619 D/DSRM-0  ( 6608): Duration millis is null
08-19 22:46:22.630 D/CarrierResolver( 6608): Creating CarrierResolver[0]
08-19 22:46:22.653 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 25
08-19 22:46:22.657 D/SST     ( 6608): [0] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=0
08-19 22:46:22.665 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 26
08-19 22:46:22.670 I/GsmCdmaPhone( 6608): [0] updateTtyMode ttyMode=0
08-19 22:46:22.672 D/RILJ    ( 6608): [0015]> SET_TTY_MODE ttyMode = 0 [PHONE0]
08-19 22:46:22.674 I/GsmCdmaPhone( 6608): [0] updateUiTtyMode ttyMode=0
08-19 22:46:22.674 D/CallManager( 6608): registerPhone(GSM Handler (com.android.internal.telephony.GsmCdmaPhone) {1048021})
08-19 22:46:22.675 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 27
08-19 22:46:22.675 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.676 D/GsmCdmaPhone( 6608): [0] GsmCdmaPhone: constructor: sub = 0
08-19 22:46:22.676 I/PhoneFactory( 6608): Creating Phone with type = 1 phoneId = 1
08-19 22:46:22.677 D/Phone-1 ( 6608): mDoesRilSendMultipleCallRing=true
08-19 22:46:22.677 D/RILJ    ( 6608): [0015]< SET_TTY_MODE  [PHONE0]
08-19 22:46:22.677 D/Phone-1 ( 6608): mCallRingDelay=3000
08-19 22:46:22.677 D/TelephonyAdminReceiver( 6608): No user manager. Attempting to resolve one.
08-19 22:46:22.679 D/TelephonyTester-1( 6608): register for intent action=com.android.internal.telephony.action_detached
08-19 22:46:22.679 D/TelephonyTester-1( 6608): register for intent action=com.android.internal.telephony.action_attached
08-19 22:46:22.679 D/TelephonyTester-1( 6608): register for intent action=com.android.internal.telephony.TestServiceState
08-19 22:46:22.679 D/TelephonyTester-1( 6608): register for intent action=com.android.internal.telephony.TestChangeNumber
08-19 22:46:22.698 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 28
08-19 22:46:22.699 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 29
08-19 22:46:22.699 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.700 D/TelephonyAnalytics( 6608): stopped listener
08-19 22:46:22.704 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 30
08-19 22:46:22.704 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.704 E/SatelliteController( 6608): SatelliteController was not yet initialized.
08-19 22:46:22.707 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 31
08-19 22:46:22.707 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.707 D/SmsDispatchersController( 6608): SmsDispatchersController created
08-19 22:46:22.710 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=unknown mSmsSendDisabled=false
08-19 22:46:22.717 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=3gpp2 mSmsSendDisabled=false
08-19 22:46:22.717 D/CdmaSMSDispatcher( 6608): CdmaSMSDispatcher created
08-19 22:46:22.726 D/GsmInboundSmsHandler( 6608): created InboundSmsHandler
08-19 22:46:22.748 D/CdmaInboundSmsHandler( 6608): created InboundSmsHandler
08-19 22:46:22.754 D/SMSDispatcher( 6608): SMSDispatcher: ctor mSmsCapable=true format=3gpp mSmsSendDisabled=false
08-19 22:46:22.754 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher created
08-19 22:46:22.760 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 32
08-19 22:46:22.761 I/GsmCdmaPhone( 6608): [1] enable_identifier_disclosure_transparency_unsol_events is on. Registering for cellular identifier disclosures from phone 1
08-19 22:46:22.761 I/GsmCdmaPhone( 6608): [1] enable_modem_cipher_transparency_unsol_events is on. Registering for security algorithm updates from phone 1
08-19 22:46:22.761 D/GsmCdmaPhone( 6608): [1] Precise phone type 1
08-19 22:46:22.761 D/RILJ    ( 6608): setPhoneType=1 old value=0 [PHONE1]
08-19 22:46:22.764 D/CarrierActionAgent( 6608): [1]Creating CarrierActionAgent
08-19 22:46:22.765 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.765 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.766 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 33
08-19 22:46:22.768 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 34
08-19 22:46:22.769 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.770 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 35
08-19 22:46:22.771 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 36
08-19 22:46:22.773 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.773 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.776 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 37
08-19 22:46:22.776 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.777 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.778 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 38
08-19 22:46:22.779 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 39
08-19 22:46:22.779 D/NRM-C-1 ( 6608): registerForNetworkRegistrationInfoChanged
08-19 22:46:22.780 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 40
08-19 22:46:22.781 D/NRM-I-1 ( 6608): registerForNetworkRegistrationInfoChanged
08-19 22:46:22.787 D/RILJ    ( 6608): [0016]> SIGNAL_STRENGTH [PHONE1]
08-19 22:46:22.787 E/RILC    ( 6018): getSignalStrengthResponse: Invalid response
08-19 22:46:22.788 D/SST     ( 6608): [1] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=0
08-19 22:46:22.788 D/RILJ    ( 6608): [0016]< SIGNAL_STRENGTH error 1 [PHONE1]
08-19 22:46:22.789 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 41
08-19 22:46:22.789 D/RilRequest( 6608): [0016]< SIGNAL_STRENGTH error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret=SignalStrength:{mCdma=CellSignalStrengthCdma: cdmaDbm=0 cdmaEcio=0 evdoDbm=0 evdoEcio=0 evdoSnr=0 level=4,mGsm=CellSignalStrengthGsm: rssi=-113 ber=0 mTa=0 mLevel=0,mWcdma=CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-120 ecno=-24 level=0,mTdscdma=CellSignalStrengthTdscdma: rssi=-113 ber=0 rscp=-120 level=0,mLte=CellSignalStrengthLte: rssi=-113 rsrp=2147483647 rsrq=0 rssnr=0 cqiTableIndex=2147483647 cqi=0 ta=0 level=1 parametersUseForLevel=1,mNr=CellSignalStrengthNr:{ csiRsrp = 2147483647 csiRsrq = 2147483647 csiCqiTableIndex = 2147483647 csiCqiReport = [] ssRsrp = 2147483647 ssRsrq = 0 ssSinr = 0 level = 0 parametersUseForLevel = 1 timingAdvance = 2147483647 },primary=CellSignalStrengthLte} result={ when=-32s720ms what=6 target=com.android.internal.telephony.SignalStrengthController }
08-19 22:46:22.790 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 42
08-19 22:46:22.790 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.791 D/Phone-1 ( 6608): [1] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:22.793 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.793 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.794 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 43
08-19 22:46:22.804 D/EmergencyNumberTracker( 6608): [1] asset emergency database is loaded. Ver: 2 Phone Id: 1 countryIso: 
08-19 22:46:22.805 E/EmergencyNumberTracker( 6608): [1]Cache ota emergency database IOException: java.io.FileNotFoundException: /data/misc/emergencynumberdb/emergency_number_db: open failed: ENOENT (No such file or directory)
08-19 22:46:22.805 D/EmergencyNumberTracker( 6608): [1]Using Asset Emergency database. Version: 2
08-19 22:46:22.814 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.815 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 44
08-19 22:46:22.815 D/DNC-1   ( 6608): DataNetworkController created.
08-19 22:46:22.816 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 45
08-19 22:46:22.818 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.818 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.820 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.820 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.821 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.821 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.822 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.823 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.830 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 46
08-19 22:46:22.831 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.831 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.833 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.833 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.834 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.834 W/CarrierConfigManager( 6608): CarrierConfigLoader is not available.
08-19 22:46:22.834 E/DSM-I-1 ( 6608): Can't find the binding package
08-19 22:46:22.835 D/DCM-1   ( 6608): DataConfigManager created.
08-19 22:46:22.835 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 47
08-19 22:46:22.837 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.842 D/DCM-1   ( 6608): Carrier config updated. Config is not carrier specific.
08-19 22:46:22.843 D/DSMGR-1 ( 6608): DataSettingsManager created.
08-19 22:46:22.846 D/DSRM-1  ( 6608): DataStallRecoveryManager created.
08-19 22:46:22.846 D/DSRM-1  ( 6608): Enabled actions is null
08-19 22:46:22.846 D/DSRM-1  ( 6608): Duration millis is null
08-19 22:46:22.857 D/CarrierResolver( 6608): Creating CarrierResolver[1]
08-19 22:46:22.863 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 48
08-19 22:46:22.866 D/SST     ( 6608): [1] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=0
08-19 22:46:22.870 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 49
08-19 22:46:22.872 I/GsmCdmaPhone( 6608): [1] updateTtyMode ttyMode=0
08-19 22:46:22.877 D/RILJ    ( 6608): [0017]> SET_TTY_MODE ttyMode = 0 [PHONE1]
08-19 22:46:22.879 I/GsmCdmaPhone( 6608): [1] updateUiTtyMode ttyMode=0
08-19 22:46:22.879 D/CallManager( 6608): registerPhone(GSM Handler (com.android.internal.telephony.GsmCdmaPhone) {bc6f7a7})
08-19 22:46:22.880 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 50
08-19 22:46:22.880 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.881 D/GsmCdmaPhone( 6608): [1] GsmCdmaPhone: constructor: sub = 1
08-19 22:46:22.881 D/RILJ    ( 6608): [0017]< SET_TTY_MODE  [PHONE1]
08-19 22:46:22.910 I/PhoneFactory( 6608): defaultSmsApplication: com.android.messaging
08-19 22:46:22.918 D/Phone-2147483647( 6608): mDoesRilSendMultipleCallRing=true
08-19 22:46:22.918 D/Phone-2147483647( 6608): mCallRingDelay=3000
08-19 22:46:22.918 D/TelephonyAdminReceiver( 6608): No user manager. Attempting to resolve one.
08-19 22:46:22.922 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 51
08-19 22:46:22.926 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 52
08-19 22:46:22.927 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.927 E/ImsPhoneCallTracker( 6608): [0] getCarrierConfigBundle: carrier config is null, skipping.
08-19 22:46:22.928 E/ImsPhoneCallTracker( 6608): [0] updateCarrierConfiguration: carrier config is null, skipping.
08-19 22:46:22.932 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:22.932 D/CallManager( 6608): registerPhone(ImsPhone Handler (com.android.internal.telephony.imsphone.ImsPhone) {e6e5e3e})
08-19 22:46:22.933 D/Phone-2147483647( 6608): mDoesRilSendMultipleCallRing=true
08-19 22:46:22.933 D/Phone-2147483647( 6608): mCallRingDelay=3000
08-19 22:46:22.933 D/TelephonyAdminReceiver( 6608): No user manager. Attempting to resolve one.
08-19 22:46:22.937 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 53
08-19 22:46:22.939 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 54
08-19 22:46:22.940 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.940 E/ImsPhoneCallTracker( 6608): [1] getCarrierConfigBundle: carrier config is null, skipping.
08-19 22:46:22.940 E/ImsPhoneCallTracker( 6608): [1] updateCarrierConfiguration: carrier config is null, skipping.
08-19 22:46:22.943 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:22.943 D/CallManager( 6608): registerPhone(ImsPhone Handler (com.android.internal.telephony.imsphone.ImsPhone) {4c7d8d8})
08-19 22:46:22.944 D/PhoneCfgMgr( 6608): getStaticPhoneCapability: isDefault=true, caps=mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=1 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:22.946 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 55
08-19 22:46:22.947 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.947 D/PhoneCfgMgr( 6608): getStaticPhoneCapability: isDefault=true, caps=mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=1 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:22.950 D/PhoneSwitcher( 6608): register handler to receive IMS registration : 0
08-19 22:46:22.950 D/PhoneSwitcher( 6608): register handler to receive IMS registration : 1
08-19 22:46:22.951 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 56
08-19 22:46:22.951 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.958 D/PhoneSwitcher( 6608): PhoneSwitcher started
08-19 22:46:22.958 D/ProxyController( 6608): Constructor - Enter
08-19 22:46:22.963 D/ProxyController( 6608): clearTransaction
08-19 22:46:22.963 D/ProxyController( 6608): clearTransaction: phoneId=0 status=IDLE
08-19 22:46:22.963 D/ProxyController( 6608): clearTransaction: phoneId=1 status=IDLE
08-19 22:46:22.963 D/ProxyController( 6608): Constructor - Exit
08-19 22:46:22.977 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 57
08-19 22:46:22.977 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.978 D/TelephonyNetworkFactory[0]( 6608): Registering NetworkFactory
08-19 22:46:22.980 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 58
08-19 22:46:22.980 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.980 D/TelephonyNetworkFactory[1]( 6608): Registering NetworkFactory
08-19 22:46:22.984 D/RcsProvisioningMonitor( 6608): RcsProvisioningMonitor created.
08-19 22:46:22.987 D/RcsStats( 6608): RcsStats created.
08-19 22:46:22.989 D/RcsProvisioningMonitor( 6608): init.
08-19 22:46:22.992 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 59
08-19 22:46:22.992 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:22.997 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:22.998 W/CarrierConfigManager( 6608): Error getting config for subId -1 ICarrierConfigLoader is null
08-19 22:46:23.000 D/SatelliteModemInterface( 6608): Created SatelliteModemInterface. Attempting to bind to SatelliteService.
08-19 22:46:23.000 E/SatelliteModemInterface( 6608): Unable to bind to the satellite service because the package is undefined.
08-19 22:46:23.005 D/TelephonyCountryDetector( 6608): getCurrentNetworkCountryIso: invalid countryIso= for phoneId=0, subId=-1
08-19 22:46:23.005 D/TelephonyCountryDetector( 6608): getCurrentNetworkCountryIso: invalid countryIso= for phoneId=1, subId=-1
08-19 22:46:23.006 D/TelephonyCountryDetector( 6608): Location update was not requested yet
08-19 22:46:23.006 D/TelephonyCountryDetector( 6608): registerForWifiConnectivityStateChanged
08-19 22:46:23.009 D/SatelliteStats( 6608): SatelliteStats created.
08-19 22:46:23.012 D/SatelliteController( 6608): EVENT_RADIO_STATE_CHANGED: radioState=0
08-19 22:46:23.013 D/SatelliteController( 6608): Radios To be checked when satellite is on: 
08-19 22:46:23.013 D/SatelliteController( 6608): initializeSatelliteModeRadios: unregisterReceiver, e=java.lang.IllegalArgumentException: Receiver not registered: com.android.internal.telephony.satellite.SatelliteController$BTWifiNFCStateReceiver@d24739b
08-19 22:46:23.015 D/SatelliteController( 6608): mDisableBTOnSatelliteEnabled: false mDisableNFCOnSatelliteEnabled: false mDisableWifiOnSatelliteEnabled: false mDisableUWBOnSatelliteEnabled: false
08-19 22:46:23.015 D/SatelliteController( 6608): mBTStateEnabled: false mNfcStateEnabled: false mWifiStateEnabled: false mUwbStateEnabled: false
08-19 22:46:23.018 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 60
08-19 22:46:23.020 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 61
08-19 22:46:23.020 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.020 D/SatelliteController( 6608): registerDefaultSmsSubscriptionChangedBroadcastReceiver: Flag CarrierRoamingNbIotNtn is disabled
08-19 22:46:23.024 D/SatelliteAccessController( 6608): setIsSatelliteAllowedRegionPossiblyChanged : false
08-19 22:46:23.025 D/SatelliteAccessController( 6608): getSatelliteCountryCodesFromOverlayConfig: Read config_oem_enabled_satellite_country_codes from device config
08-19 22:46:23.025 D/SatelliteAccessController( 6608): getSatelliteS2CellFileFromOverlayConfig: Read config_oem_enabled_satellite_s2cell_file from device config
08-19 22:46:23.026 D/SatelliteAccessController( 6608): s2CellFile=null
08-19 22:46:23.026 E/SatelliteAccessController( 6608): config updater country codes are either null or empty
08-19 22:46:23.027 D/SatelliteController( 6608): evaluateOemSatelliteRequestAllowed: satellite service is not supported
08-19 22:46:23.031 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 62
08-19 22:46:23.038 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 63
08-19 22:46:23.039 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 64
08-19 22:46:23.042 D/ImsStateCallbackController( 6608): ImsStateCallbackController created
08-19 22:46:23.043 D/ImsStateCallbackController( 6608): updateFeatures: oldSlots=0, newNumSlots=2
08-19 22:46:23.050 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 65
08-19 22:46:23.050 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.052 D/RcsStats( 6608): created Callback
08-19 22:46:23.052 D/RcsStats( 6608): UceStatsWriterCallback created.
08-19 22:46:23.053 D/ImsStateCallbackController( 6608): onExternalRcsStateChanged slotId=0, state=UNAVAILABLE, reason=NO_IMS_SERVICE_CONFIGURED
08-19 22:46:23.053 D/ImsStateCallbackController( 6608): onExternalRcsStateChanged slotId=1, state=UNAVAILABLE, reason=NO_IMS_SERVICE_CONFIGURED
08-19 22:46:23.055 I/ImsProvisioningController( 6608): ImsProvisioningController created
08-19 22:46:23.055 D/ImsProvisioningController( 6608): ImsProvisioningController
08-19 22:46:23.056 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 66
08-19 22:46:23.056 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.057 D/ImsProvisioningController( 6608): MmTelFeatureListener[0] created
08-19 22:46:23.058 D/ImsProvisioningController( 6608): RcsFeatureListener[0] created
08-19 22:46:23.060 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[0] ProvisioningCallbackManager create
08-19 22:46:23.060 D/ImsProvisioningController( 6608): MmTelFeatureListener[1] created
08-19 22:46:23.061 D/ImsProvisioningController( 6608): RcsFeatureListener[1] created
08-19 22:46:23.062 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[1] ProvisioningCallbackManager create
08-19 22:46:23.069 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 67
08-19 22:46:23.069 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.069 D/CallManager( 6608): registerForMmiComplete
08-19 22:46:23.077 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 68
08-19 22:46:23.078 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 69
08-19 22:46:23.082 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.090 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 70
08-19 22:46:23.090 D/TelephonyRegistry( 6138): listen oscl: mHasNotifySubscriptionInfoChangedOccurred==false no callback
08-19 22:46:23.092 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 71
08-19 22:46:23.105 D/CdmaInboundSmsHandler( 6608): StartupState.enter: entering StartupState
08-19 22:46:23.105 D/GsmInboundSmsHandler( 6608): StartupState.enter: entering StartupState
08-19 22:46:23.105 D/CdmaInboundSmsHandler( 6608): StartupState.enter: entering StartupState
08-19 22:46:23.105 D/GsmInboundSmsHandler( 6608): StartupState.enter: entering StartupState
08-19 22:46:23.107 D/UiccController( 6608): handleMessage: Received RADIO_AVAILABLE for phoneId 0
08-19 22:46:23.107 D/UiccController( 6608): Received EVENT_RADIO_AVAILABLE/EVENT_RADIO_ON, calling getIccCardStatus
08-19 22:46:23.107 D/UiccController( 6608): Received EVENT_RADIO_AVAILABLE/EVENT_RADIO_ON for phoneId 0, calling getSimSlotsStatus
08-19 22:46:23.107 D/RadioConfig( 6608): [0018]> GET_SLOT_STATUS
08-19 22:46:23.108 D/RILC    ( 6018): convertRilSlotStatusToHal
08-19 22:46:23.109 D/RadioConfigResponseAidl( 6608): [0018]< GET_SLOT_STATUS []
08-19 22:46:23.110 D/RILJ    ( 6608): [0019]> GET_SIM_STATUS [PHONE0]
08-19 22:46:23.110 D/UiccController( 6608): handleMessage: Received RADIO_UNAVAILABLE for phoneId 1
08-19 22:46:23.110 D/UiccController( 6608): EVENT_RADIO_UNAVAILABLE, dispose card
08-19 22:46:23.111 D/UiccController( 6608): handleMessage: Received RADIO_AVAILABLE for phoneId 1
08-19 22:46:23.111 D/UiccController( 6608): Received EVENT_RADIO_AVAILABLE/EVENT_RADIO_ON, calling getIccCardStatus
08-19 22:46:23.112 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.113 D/RILJ    ( 6608): [0020]> GET_SIM_STATUS [PHONE1]
08-19 22:46:23.115 D/RILJ    ( 6608): responseIccCardStatus: from AIDL: IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=0, portIndex=0}} [PHONE0]
08-19 22:46:23.115 D/RILJ    ( 6608): [0019]< GET_SIM_STATUS IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=0, portIndex=0}} [PHONE0]
08-19 22:46:23.115 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.116 D/RILJ    ( 6608): responseIccCardStatus: from AIDL: IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=1, portIndex=0}} [PHONE1]
08-19 22:46:23.116 D/RILJ    ( 6608): [0020]< GET_SIM_STATUS IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=1, portIndex=0}} [PHONE1]
08-19 22:46:23.116 D/SMSVC   ( 6608): updateUserIdToAvailableSubs: {}
08-19 22:46:23.117 D/TelephonyRegistry( 6138): notifySubscriptionInfoChanged: first invocation mRecords.size=111
08-19 22:46:23.123 D/SMSVC   ( 6608): updateUserIdToAvailableSubs: {}
08-19 22:46:23.128 D/ImsProvisioningController( 6608): MmTelFeatureListener[0] subId is not changed
08-19 22:46:23.128 D/ImsProvisioningController( 6608): MmTelFeatureListener[1] subId is not changed
08-19 22:46:23.128 D/ImsProvisioningController( 6608): RcsFeatureListener[0] subId is not changed
08-19 22:46:23.128 D/ImsProvisioningController( 6608): RcsFeatureListener[1] subId is not changed
08-19 22:46:23.128 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[0] subId is not changed 
08-19 22:46:23.128 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[1] subId is not changed 
08-19 22:46:23.198 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 32
08-19 22:46:23.202 E/TelephonyAnalyticsSubId( 6608): Null Pointer Exception Caught
08-19 22:46:23.202 E/TelephonyAnalyticsSubId( 6608): Null Pointer Exception Caught
08-19 22:46:23.204 D/SMSVC   ( 6608): Subscription database has been initialized.
08-19 22:46:23.204 D/SMSVC   ( 6608): markSubscriptionsInactive: slot 0
08-19 22:46:23.204 D/ImsProvisioningController( 6608): MmTelFeatureListener[0] subId is not changed
08-19 22:46:23.205 E/TelephonyAnalyticsSubId( 6608): Null Pointer Exception Caught
08-19 22:46:23.205 E/TelephonyAnalyticsSubId( 6608): Null Pointer Exception Caught
08-19 22:46:23.205 D/ImsProvisioningController( 6608): MmTelFeatureListener[1] subId is not changed
08-19 22:46:23.205 D/ImsProvisioningController( 6608): RcsFeatureListener[0] subId is not changed
08-19 22:46:23.205 D/ImsProvisioningController( 6608): RcsFeatureListener[1] subId is not changed
08-19 22:46:23.205 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[0] subId is not changed 
08-19 22:46:23.205 D/ImsProvisioningController( 6608): ProvisioningCallbackManager[1] subId is not changed 
08-19 22:46:23.207 D/SMSVC   ( 6608): markSubscriptionsInactive: current mapping []
08-19 22:46:23.207 D/SMSVC   ( 6608): markSubscriptionsInactive: slot 1
08-19 22:46:23.208 W/TelephonyRegistry( 6138): Pid 6138 has exceeded half the number of permissible registered listeners. Now at 33
08-19 22:46:23.208 D/SMSVC   ( 6608): markSubscriptionsInactive: current mapping []
08-19 22:46:23.209 E/GsmCdmaPhone( 6608): [0] reapplyUiccAppsEnablementIfNeeded: slot state=null
08-19 22:46:23.212 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 0
08-19 22:46:23.214 D/GsmInboundSmsHandler( 6608): StartupState.processMessage: processing EVENT_START_ACCEPTING_SMS
08-19 22:46:23.214 D/GsmInboundSmsHandler( 6608): IdleState.enter: entering IdleState
08-19 22:46:23.214 D/CdmaInboundSmsHandler( 6608): StartupState.processMessage: processing EVENT_START_ACCEPTING_SMS
08-19 22:46:23.214 D/CdmaInboundSmsHandler( 6608): IdleState.enter: entering IdleState
08-19 22:46:23.221 D/RILJ    ( 6608): [0021]> BASEBAND_VERSION [PHONE0]
08-19 22:46:23.222 E/RILJ    ( 6608): getImei not supported on service MODEM < 2.1. [PHONE0]
08-19 22:46:23.227 E/RILD    ( 6018): isEsimSlotSwitchModel(): no need to update prop
08-19 22:46:23.230 D/RILJ    ( 6608): [0022]> DEVICE_IDENTITY [PHONE0]
08-19 22:46:23.232 E/RILD    ( 6018): Not support read boot param (ro.vendor.boot.sn.param.offset)
08-19 22:46:23.232 D/RILJ    ( 6608): [0023]> GET_RADIO_CAPABILITY [PHONE0]
08-19 22:46:23.234 D/RILJ    ( 6608): [0021]< BASEBAND_VERSION A217FXXSCDXE1 [PHONE0]
08-19 22:46:23.237 D/RILJ    ( 6608): [0024]> GET_UICC_APPLICATIONS_ENABLEMENT [PHONE0]
08-19 22:46:23.238 E/RILC    ( 6018): areUiccApplicationsEnabledResponse: Invalid response
08-19 22:46:23.238 D/RILJ    ( 6608): convertHalRadioCapability: session=0, phase=4, rat=130047, logicModemUuid=, status=1, rcRil.raf=262142 [PHONE0]
08-19 22:46:23.239 D/RILJ    ( 6608): [0024]< GET_UICC_APPLICATIONS_ENABLEMENT error 11 [PHONE0]
08-19 22:46:23.239 D/RILJ    ( 6608): [0023]< GET_RADIO_CAPABILITY {mPhoneId = 0 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1} [PHONE0]
08-19 22:46:23.239 D/RilRequest( 6608): [0024]< GET_UICC_APPLICATIONS_ENABLEMENT error: com.android.internal.telephony.CommandException: SIM_ABSENT ret=false result={ when=-33s171ms what=55 target=com.android.internal.telephony.GsmCdmaPhone }
08-19 22:46:23.240 E/RILJ    ( 6608): setNullCipherAndIntegrityEnabled not supported on service NETWORK < 2.1. [PHONE0]
08-19 22:46:23.241 D/CellularIdentifierDisclosureNotifier( 6608): disabled
08-19 22:46:23.242 E/RILD    ( 6018): Not support read boot param (ro.vendor.boot.im.param.offset)
08-19 22:46:23.242 D/CellularIdentifierDisclosureNotifier( 6608): On disable notifier
08-19 22:46:23.242 E/RILJ    ( 6608): setCellularIdentifierTransparencyEnabled not supported on service NETWORK < 2.2. [PHONE0]
08-19 22:46:23.242 D/NullCipherNotifier( 6608): disabled
08-19 22:46:23.243 E/RILJ    ( 6608): setSecurityAlgorithmsUpdatedEnabled not supported on service NETWORK < 2.2. [PHONE0]
08-19 22:46:23.243 D/RILJ    ( 6608): [0022]< DEVICE_IDENTITY {[R7unnwhKBh8_x9XazDkXvA9JIHE], 01, , } [PHONE0]
08-19 22:46:23.244 D/GsmCdmaPhone( 6608): [0] Event EVENT_RADIO_OFF_OR_NOT_AVAILABLE Received
08-19 22:46:23.244 D/GsmCdmaPhone( 6608): [0] EVENT EVENT_RADIO_STATE_CHANGED
08-19 22:46:23.245 D/GsmCdmaPhone( 6608): handleRadioPowerStateChange, state= 0
08-19 22:46:23.245 E/RILD    ( 6018): update prop from cp sim count
08-19 22:46:23.249 I/NullCipherNotifier( 6608): On enable notifier. Enable value: false
08-19 22:46:23.251 D/RILClient( 6011): Connect_RILD_Internal: socket allocated 13
08-19 22:46:23.252 D/RILClient( 6011): Connect_RILD_Internal: Success to connect
08-19 22:46:23.252 D/RILClient( 6011): Connect_RILD_Internal: socket allocated 16
08-19 22:46:23.252 D/RILClient( 6011): Connect_RILD_Internal: Success to connect
08-19 22:46:23.255 E/ANM-0   ( 6608): Can't find the binding package
08-19 22:46:23.257 D/SSCtr   ( 6608): No matching configuration
08-19 22:46:23.263 D/RILJ    ( 6608): [0025]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.265 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=4 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:23.265 D/RILJ    ( 6608): [0025]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error 1 [PHONE0]
08-19 22:46:23.265 D/RilRequest( 6608): [0025]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret= result=null
08-19 22:46:23.266 D/SSCtr   ( 6608): No matching configuration
08-19 22:46:23.271 D/RILJ    ( 6608): [0026]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.271 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=4 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:23.271 D/RILJ    ( 6608): [0026]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error 1 [PHONE0]
08-19 22:46:23.272 D/RilRequest( 6608): [0026]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret= result=null
08-19 22:46:23.273 D/SST     ( 6608): [0] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:23.273 D/SST     ( 6608): [0] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:23.273 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:23.277 D/SST     ( 6608): [0] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:23.277 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:23.277 D/SST     ( 6608): [0] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='No service', showSpn='false', spn='', dataSpn='', subId='-1'
08-19 22:46:23.281 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:23.288 D/NRM-C-0 ( 6608): Trying to bind com.android.phone for transport WWAN
08-19 22:46:23.300 E/NRM-I-0 ( 6608): Can't find the binding package
08-19 22:46:23.301 D/SST     ( 6608): [0] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=0, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:23.304 D/RILJ    ( 6608): [0027]> RADIO_POWER on = true forEmergencyCall= false preferredForEmergencyCall=false [PHONE0]
08-19 22:46:23.304 D/SST     ( 6608): [0] pollState: modemTriggered=true, radioState=0
08-19 22:46:23.304 D/RILC    ( 6018): setRadioPower: serial 27, powerOn 1, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:23.306 D/RILJ    ( 6608): [0028]> OPERATOR [PHONE0]
08-19 22:46:23.307 E/NRM-C-0 ( 6608): service not connected. Domain = PS
08-19 22:46:23.307 E/NRM-C-0 ( 6608): service not connected. Domain = CS
08-19 22:46:23.308 E/NRM-I-0 ( 6608): service not connected. Domain = PS
08-19 22:46:23.309 D/RILC    ( 6018): setRadioPowerResponse: serial 27
08-19 22:46:23.309 D/RILJ    ( 6608): [0027]< RADIO_POWER  [PHONE0]
08-19 22:46:23.310 D/RILC    ( 6018): radioStateChangedInd: radioState 10
08-19 22:46:23.310 D/RILJ    ( 6608): [0029]> QUERY_NETWORK_SELECTION_MODE [PHONE0]
08-19 22:46:23.312 D/SST     ( 6608): [0] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=0, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:23.315 D/RILJ    ( 6608): [0031]> RADIO_POWER on = true forEmergencyCall= false preferredForEmergencyCall=false [PHONE0]
08-19 22:46:23.315 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:23.315 D/SST     ( 6608): [0] pollState: modemTriggered=true, radioState=0
08-19 22:46:23.315 D/RILC    ( 6018): setRadioPower: serial 31, powerOn 1, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:23.316 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 1 [PHONE0]
08-19 22:46:23.316 D/SatelliteController( 6608): EVENT_RADIO_STATE_CHANGED: radioState=1
08-19 22:46:23.316 D/RILC    ( 6018): setRadioPowerResponse: serial 31
08-19 22:46:23.317 D/RILJ    ( 6608): [0032]> OPERATOR [PHONE0]
08-19 22:46:23.317 D/RILJ    ( 6608): [0031]< RADIO_POWER  [PHONE0]
08-19 22:46:23.318 E/NRM-C-0 ( 6608): service not connected. Domain = PS
08-19 22:46:23.319 E/NRM-C-0 ( 6608): service not connected. Domain = CS
08-19 22:46:23.319 E/NRM-I-0 ( 6608): service not connected. Domain = PS
08-19 22:46:23.321 D/RILJ    ( 6608): [0033]> QUERY_NETWORK_SELECTION_MODE [PHONE0]
08-19 22:46:23.321 E/SSCtr   ( 6608): onSignalStrengthResult() Exception from RIL : com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE
08-19 22:46:23.326 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.326 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 0 networkType = 316295
08-19 22:46:23.334 D/Phone-0 ( 6608): [0] Allowed network types for 'carrier' reason is changed by carrier config = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.334 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.335 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:23.335 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,false,false,-1,false,true
08-19 22:46:23.335 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:23.336 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.336 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:23.336 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.336 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:23.337 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:23.337 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.337 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 0 networkType = 316295
08-19 22:46:23.340 D/Phone-0 ( 6608): [0] Allowed network types for 'carrier' reason is changed by carrier config = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.342 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.343 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:23.343 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,false,false,-1,false,true
08-19 22:46:23.343 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:23.343 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.344 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:23.344 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.344 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:23.344 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:23.345 D/EmergencyNumberTracker( 6608): [0]updateRadioEmergencyNumberListAndNotify(): receiving []
08-19 22:46:23.349 D/RILJ    ( 6608): [0034]> SEND_DEVICE_STATE 1:true [PHONE0]
08-19 22:46:23.350 D/RILJ    ( 6608): [0034]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.351 D/RILJ    ( 6608): [0035]> SEND_DEVICE_STATE 2:false [PHONE0]
08-19 22:46:23.352 D/RILJ    ( 6608): [0035]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.353 D/RILJ    ( 6608): [0036]> SEND_DEVICE_STATE 0:false [PHONE0]
08-19 22:46:23.354 D/RILJ    ( 6608): [0036]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.355 D/RILJ    ( 6608): [0037]> SET_UNSOLICITED_RESPONSE_FILTER -1 [PHONE0]
08-19 22:46:23.356 D/RILJ    ( 6608): [0037]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE0]
08-19 22:46:23.357 D/RILJ    ( 6608): [0038]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.357 E/RILC    ( 6018): in_accessNetwork 1 not supported
08-19 22:46:23.357 D/RILJ    ( 6608): [0038]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.358 D/RilRequest( 6608): [0038]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.359 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.359 D/RILJ    ( 6608): [0039]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.359 E/RILD    ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.360 D/RILJ    ( 6608): [0039]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.360 D/RilRequest( 6608): [0039]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.360 D/RILJ    ( 6608): [0040]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.361 D/RILJ    ( 6608): [0040]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.361 D/RilRequest( 6608): [0040]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.364 D/RILJ    ( 6608): [0041]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.364 E/RILC    ( 6018): in_accessNetwork 4 not supported
08-19 22:46:23.365 D/RILJ    ( 6608): [0041]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.365 D/RilRequest( 6608): [0041]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.365 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:23.365 E/RILD    ( 6018): IO channel write error.
08-19 22:46:23.365 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:23.365 D/RILJ    ( 6608): [0042]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.365 E/RILC    ( 6018): in_accessNetwork 6 not supported
08-19 22:46:23.366 D/RILJ    ( 6608): [0028]< OPERATOR {, , } [PHONE0]
08-19 22:46:23.367 D/RILJ    ( 6608): [0043]> SEND_DEVICE_STATE 1:true [PHONE0]
08-19 22:46:23.367 D/RILJ    ( 6608): [0042]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.368 D/RILJ    ( 6608): [0043]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.370 D/RILJ    ( 6608): [0044]> SEND_DEVICE_STATE 2:false [PHONE0]
08-19 22:46:23.370 D/RilRequest( 6608): [0042]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.370 D/RILJ    ( 6608): [0044]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.370 D/RILJ    ( 6608): [0029]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE0]
08-19 22:46:23.371 D/RILJ    ( 6608): [0045]> SEND_DEVICE_STATE 0:false [PHONE0]
08-19 22:46:23.372 D/RILJ    ( 6608): [0045]< SEND_DEVICE_STATE  [PHONE0]
08-19 22:46:23.373 D/RILJ    ( 6608): [0046]> SET_UNSOLICITED_RESPONSE_FILTER -1 [PHONE0]
08-19 22:46:23.374 D/RILJ    ( 6608): [0047]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.374 E/RILC    ( 6018): in_accessNetwork 1 not supported
08-19 22:46:23.375 D/RILJ    ( 6608): [0048]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.376 D/RILJ    ( 6608): [0047]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.376 D/RilRequest( 6608): [0047]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.376 D/RILJ    ( 6608): [0049]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.377 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:23.377 E/RILD    ( 6018): IO channel write error.
08-19 22:46:23.377 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:23.378 D/RILJ    ( 6608): [0050]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.378 E/RILC    ( 6018): in_accessNetwork 4 not supported
08-19 22:46:23.378 D/RILJ    ( 6608): [0046]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE0]
08-19 22:46:23.379 D/RILJ    ( 6608): [0051]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE0]
08-19 22:46:23.379 E/RILC    ( 6018): in_accessNetwork 6 not supported
08-19 22:46:23.379 D/RILJ    ( 6608): [0048]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.379 D/RilRequest( 6608): [0048]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.379 D/NetworkTypeController( 6608): [0] DefaultState: process EVENT_INITIALIZE
08-19 22:46:23.380 D/RILJ    ( 6608): [0049]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.380 D/RilRequest( 6608): [0049]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.380 D/RILJ    ( 6608): [0032]< OPERATOR {, , } [PHONE0]
08-19 22:46:23.381 D/RILJ    ( 6608): [0050]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.381 D/RilRequest( 6608): [0050]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.382 D/RILJ    ( 6608): [0051]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE0]
08-19 22:46:23.382 D/RilRequest( 6608): [0051]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.382 D/RILJ    ( 6608): [0033]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE0]
08-19 22:46:23.383 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 72
08-19 22:46:23.386 D/NetworkTypeController( 6608): [0] mOverrideTimerRules: {connected={mState=connected, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_con={mState=not_restricted_rrc_con, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, legacy={mState=legacy, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_idle={mState=not_restricted_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, restricted={mState=restricted, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, connected_mmwave={mState=connected_mmwave, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, connected_rrc_idle={mState=connected_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}}
08-19 22:46:23.386 D/NetworkTypeController( 6608): [0] Physical channel configs updated: anchorNrCell=-1, nrBandwidths=0, nrBands=[], configs=null
08-19 22:46:23.386 D/NetworkTypeController( 6608): [0] DefaultState: process EVENT_UPDATE
08-19 22:46:23.387 D/NetworkTypeController( 6608): [0] Entering LegacyState
08-19 22:46:23.387 D/NetworkTypeController( 6608): [0] Reset timers since NR is not allowed.
08-19 22:46:23.393 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 73
08-19 22:46:23.398 D/DSMGR-0 ( 6608): mIsDataEnabled=false, prevDataEnabled=false
08-19 22:46:23.398 D/DSMGR-0 ( 6608): notifyDataEnabledChanged: enabled=false, reason=UNKNOWN, callingPackage=com.android.phone
08-19 22:46:23.406 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 74
08-19 22:46:23.407 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:23.769 D/GsmCdmaPhone( 6608): [0] onVoiceRegStateOrRatChanged
08-19 22:46:23.769 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, current vrs=1, vrat=0
08-19 22:46:23.769 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, result calcVrat=0
08-19 22:46:23.770 E/GsmCdmaPhone( 6608): [1] reapplyUiccAppsEnablementIfNeeded: slot state=null
08-19 22:46:23.772 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 1
08-19 22:46:23.772 D/GsmInboundSmsHandler( 6608): StartupState.processMessage: processing EVENT_START_ACCEPTING_SMS
08-19 22:46:23.772 D/GsmInboundSmsHandler( 6608): IdleState.enter: entering IdleState
08-19 22:46:23.772 D/CdmaInboundSmsHandler( 6608): StartupState.processMessage: processing EVENT_START_ACCEPTING_SMS
08-19 22:46:23.772 D/CdmaInboundSmsHandler( 6608): IdleState.enter: entering IdleState
08-19 22:46:23.773 E/RILD    ( 6018): OemClient::ProcessBuffer() from[2], token[1], datalen[14]
08-19 22:46:23.774 E/RILD    ( 6018): Oem OnRequestComplete:(2)
08-19 22:46:23.774 D/RILJ    ( 6608): [0052]> BASEBAND_VERSION [PHONE1]
08-19 22:46:23.774 E/RILJ    ( 6608): getImei not supported on service MODEM < 2.1. [PHONE1]
08-19 22:46:23.775 D/RILJ    ( 6608): [0053]> DEVICE_IDENTITY [PHONE1]
08-19 22:46:23.777 D/RILJ    ( 6608): [0054]> GET_RADIO_CAPABILITY [PHONE1]
08-19 22:46:23.778 D/RILJ    ( 6608): convertHalRadioCapability: session=0, phase=4, rat=130047, logicModemUuid=, status=1, rcRil.raf=262142 [PHONE1]
08-19 22:46:23.778 D/RILJ    ( 6608): [0055]> GET_UICC_APPLICATIONS_ENABLEMENT [PHONE1]
08-19 22:46:23.778 D/RILJ    ( 6608): [0054]< GET_RADIO_CAPABILITY {mPhoneId = 1 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1} [PHONE1]
08-19 22:46:23.779 E/RILJ    ( 6608): setNullCipherAndIntegrityEnabled not supported on service NETWORK < 2.1. [PHONE1]
08-19 22:46:23.779 D/CellularIdentifierDisclosureNotifier( 6608): disabled
08-19 22:46:23.779 E/RILJ    ( 6608): setCellularIdentifierTransparencyEnabled not supported on service NETWORK < 2.2. [PHONE1]
08-19 22:46:23.779 D/CellularIdentifierDisclosureNotifier( 6608): On disable notifier
08-19 22:46:23.780 D/NullCipherNotifier( 6608): disabled
08-19 22:46:23.780 D/RILClient( 6011): processUnsolicited(): resp_id (11009), len(12)
08-19 22:46:23.780 I/NullCipherNotifier( 6608): On enable notifier. Enable value: false
08-19 22:46:23.781 D/RILClient( 6011): processUnsolicited(): unsol_func resp_id (11009), len(12)
08-19 22:46:23.781 E/RILJ    ( 6608): setSecurityAlgorithmsUpdatedEnabled not supported on service NETWORK < 2.2. [PHONE1]
08-19 22:46:23.781 D/GsmCdmaPhone( 6608): [1] Event EVENT_RADIO_OFF_OR_NOT_AVAILABLE Received
08-19 22:46:23.782 D/GsmCdmaPhone( 6608): [1] EVENT EVENT_RADIO_STATE_CHANGED
08-19 22:46:23.782 D/GsmCdmaPhone( 6608): handleRadioPowerStateChange, state= 0
08-19 22:46:23.782 E/RILD2   ( 6018): Not support read boot param (ro.vendor.boot.sn.param.offset)
08-19 22:46:23.783 E/RILC    ( 6018): areUiccApplicationsEnabledResponse: Invalid response
08-19 22:46:23.784 D/RILJ    ( 6608): [0052]< BASEBAND_VERSION A217FXXSCDXE1 [PHONE1]
08-19 22:46:23.784 D/RILJ    ( 6608): [0055]< GET_UICC_APPLICATIONS_ENABLEMENT error 11 [PHONE1]
08-19 22:46:23.784 D/RilRequest( 6608): [0055]< GET_UICC_APPLICATIONS_ENABLEMENT error: com.android.internal.telephony.CommandException: SIM_ABSENT ret=false result={ when=-33s716ms what=55 target=com.android.internal.telephony.GsmCdmaPhone }
08-19 22:46:23.784 E/ANM-1   ( 6608): Can't find the binding package
08-19 22:46:23.785 D/SSCtr   ( 6608): No matching configuration
08-19 22:46:23.786 D/RILJ    ( 6608): [0056]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.787 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=4 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:23.787 D/RILJ    ( 6608): [0056]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error 1 [PHONE1]
08-19 22:46:23.787 D/RilRequest( 6608): [0056]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret= result=null
08-19 22:46:23.787 D/SSCtr   ( 6608): No matching configuration
08-19 22:46:23.788 D/RILJ    ( 6608): [0053]< DEVICE_IDENTITY {[ZJJPUfuukyxDZ969yi_G-v1JpYc], 01, , } [PHONE1]
08-19 22:46:23.789 D/RILJ    ( 6608): [0057]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.789 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=4 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:23.789 D/RILJ    ( 6608): [0057]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error 1 [PHONE1]
08-19 22:46:23.789 D/SST     ( 6608): [1] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:23.789 D/SST     ( 6608): [1] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:23.789 D/RilRequest( 6608): [0057]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE ret= result=null
08-19 22:46:23.790 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:23.790 E/RILD2   ( 6018): update prop from cp sim count
08-19 22:46:23.790 D/SST     ( 6608): [1] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:23.791 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:23.791 D/SST     ( 6608): [1] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='No service', showSpn='false', spn='', dataSpn='', subId='-1'
08-19 22:46:23.793 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:23.795 D/NRM-C-1 ( 6608): Trying to bind com.android.phone for transport WWAN
08-19 22:46:23.798 E/NRM-I-1 ( 6608): Can't find the binding package
08-19 22:46:23.798 D/SST     ( 6608): [1] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=0, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:23.800 D/RILJ    ( 6608): [0058]> RADIO_POWER on = true forEmergencyCall= false preferredForEmergencyCall=false [PHONE1]
08-19 22:46:23.800 D/RILC    ( 6018): setRadioPower: serial 58, powerOn 1, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:23.800 D/SST     ( 6608): [1] pollState: modemTriggered=true, radioState=0
08-19 22:46:23.802 D/RILJ    ( 6608): [0059]> OPERATOR [PHONE1]
08-19 22:46:23.802 E/NRM-C-1 ( 6608): service not connected. Domain = PS
08-19 22:46:23.802 E/NRM-C-1 ( 6608): service not connected. Domain = CS
08-19 22:46:23.803 E/NRM-I-1 ( 6608): service not connected. Domain = PS
08-19 22:46:23.803 D/RILC    ( 6018): setRadioPowerResponse: serial 58
08-19 22:46:23.803 D/RILJ    ( 6608): [0058]< RADIO_POWER  [PHONE1]
08-19 22:46:23.804 D/RILC    ( 6018): radioStateChangedInd: radioState 10
08-19 22:46:23.804 D/RILJ    ( 6608): [0060]> QUERY_NETWORK_SELECTION_MODE [PHONE1]
08-19 22:46:23.805 D/SST     ( 6608): [1] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=0, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:23.806 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE1]
08-19 22:46:23.806 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_RADIO_STATE_CHANGED radioStateChanged: 1 [PHONE1]
08-19 22:46:23.806 D/RILJ    ( 6608): [0062]> RADIO_POWER on = true forEmergencyCall= false preferredForEmergencyCall=false [PHONE1]
08-19 22:46:23.806 D/RILC    ( 6018): setRadioPower: serial 62, powerOn 1, forEmergencyCall 0, preferredForEmergencyCall 0
08-19 22:46:23.806 D/SST     ( 6608): [1] pollState: modemTriggered=true, radioState=1
08-19 22:46:23.807 D/RILC    ( 6018): setRadioPowerResponse: serial 62
08-19 22:46:23.807 D/RILJ    ( 6608): [0063]> OPERATOR [PHONE1]
08-19 22:46:23.808 E/NRM-C-1 ( 6608): service not connected. Domain = PS
08-19 22:46:23.808 E/NRM-C-1 ( 6608): service not connected. Domain = CS
08-19 22:46:23.808 E/NRM-I-1 ( 6608): service not connected. Domain = PS
08-19 22:46:23.808 D/RILJ    ( 6608): [0062]< RADIO_POWER  [PHONE1]
08-19 22:46:23.809 D/RILJ    ( 6608): [0064]> QUERY_NETWORK_SELECTION_MODE [PHONE1]
08-19 22:46:23.809 E/SSCtr   ( 6608): onSignalStrengthResult() Exception from RIL : com.android.internal.telephony.CommandException: RADIO_NOT_AVAILABLE
08-19 22:46:23.811 D/Phone-1 ( 6608): [1] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.811 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 1 networkType = 316295
08-19 22:46:23.813 D/Phone-0 ( 6608): [0] Allowed network types for 'carrier' reason is changed by carrier config = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.813 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.813 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:23.813 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,false,false,-1,false,true
08-19 22:46:23.813 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:23.814 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.814 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:23.814 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.814 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:23.814 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:23.814 D/Phone-1 ( 6608): [1] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.814 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 1 networkType = 316295
08-19 22:46:23.815 D/Phone-0 ( 6608): [0] Allowed network types for 'carrier' reason is changed by carrier config = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.815 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:23.816 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:23.816 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,false,false,-1,false,true
08-19 22:46:23.816 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:23.816 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.816 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:23.816 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:23.816 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:23.817 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:23.817 D/EmergencyNumberTracker( 6608): [1]updateRadioEmergencyNumberListAndNotify(): receiving []
08-19 22:46:23.818 D/RILJ    ( 6608): [0065]> SEND_DEVICE_STATE 1:true [PHONE1]
08-19 22:46:23.819 D/RILJ    ( 6608): [0065]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.819 D/RILJ    ( 6608): [0066]> SEND_DEVICE_STATE 2:false [PHONE1]
08-19 22:46:23.820 D/RILJ    ( 6608): [0066]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.821 D/RILJ    ( 6608): [0067]> SEND_DEVICE_STATE 0:false [PHONE1]
08-19 22:46:23.821 D/RILJ    ( 6608): [0067]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.822 D/RILJ    ( 6608): [0068]> SET_UNSOLICITED_RESPONSE_FILTER -1 [PHONE1]
08-19 22:46:23.822 D/RILJ    ( 6608): [0068]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE1]
08-19 22:46:23.823 D/RILJ    ( 6608): [0069]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.823 E/RILC    ( 6018): in_accessNetwork 1 not supported
08-19 22:46:23.823 D/RILJ    ( 6608): [0069]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.824 D/RilRequest( 6608): [0069]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.824 D/RILJ    ( 6608): [0070]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.825 D/RILJ    ( 6608): [0070]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.825 D/RilRequest( 6608): [0070]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.825 D/RILJ    ( 6608): [0071]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.826 D/RILJ    ( 6608): [0071]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.826 D/RilRequest( 6608): [0071]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.826 D/RILJ    ( 6608): [0072]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.827 E/RILC    ( 6018): in_accessNetwork 4 not supported
08-19 22:46:23.827 D/RILJ    ( 6608): [0072]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.827 D/RilRequest( 6608): [0072]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.827 D/RILJ    ( 6608): [0073]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.828 E/RILC    ( 6018): in_accessNetwork 6 not supported
08-19 22:46:23.828 D/RILJ    ( 6608): [0073]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.828 D/RilRequest( 6608): [0073]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.829 D/RILJ    ( 6608): [0074]> SEND_DEVICE_STATE 1:true [PHONE1]
08-19 22:46:23.830 D/RILJ    ( 6608): [0074]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.830 D/RILJ    ( 6608): [0075]> SEND_DEVICE_STATE 2:false [PHONE1]
08-19 22:46:23.831 D/RILJ    ( 6608): [0075]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.831 D/RILJ    ( 6608): [0076]> SEND_DEVICE_STATE 0:false [PHONE1]
08-19 22:46:23.832 D/RILJ    ( 6608): [0076]< SEND_DEVICE_STATE  [PHONE1]
08-19 22:46:23.832 D/RILJ    ( 6608): [0077]> SET_UNSOLICITED_RESPONSE_FILTER -1 [PHONE1]
08-19 22:46:23.833 D/RILJ    ( 6608): [0077]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE1]
08-19 22:46:23.834 D/RILJ    ( 6608): [0078]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.834 E/RILC    ( 6018): in_accessNetwork 1 not supported
08-19 22:46:23.835 D/RILJ    ( 6608): [0078]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.835 D/RILJ    ( 6608): [0079]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.835 D/RilRequest( 6608): [0078]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.836 D/RILJ    ( 6608): [0079]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.836 D/RilRequest( 6608): [0079]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.836 D/RILJ    ( 6608): [0080]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.837 D/RILJ    ( 6608): [0080]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.837 D/RilRequest( 6608): [0080]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.838 D/RILJ    ( 6608): [0081]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.838 E/RILC    ( 6018): in_accessNetwork 4 not supported
08-19 22:46:23.838 D/RILJ    ( 6608): [0081]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.838 D/RilRequest( 6608): [0081]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.839 D/RILJ    ( 6608): [0082]> SET_LINK_CAPACITY_REPORTING_CRITERIA [PHONE1]
08-19 22:46:23.839 E/RILC    ( 6018): in_accessNetwork 6 not supported
08-19 22:46:23.839 D/NetworkTypeController( 6608): [1] DefaultState: process EVENT_INITIALIZE
08-19 22:46:23.839 D/RILJ    ( 6608): [0082]< SET_LINK_CAPACITY_REPORTING_CRITERIA error 6 [PHONE1]
08-19 22:46:23.840 D/RilRequest( 6608): [0082]< SET_LINK_CAPACITY_REPORTING_CRITERIA error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result=null
08-19 22:46:23.842 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 75
08-19 22:46:23.843 D/NetworkTypeController( 6608): [1] mOverrideTimerRules: {connected={mState=connected, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_con={mState=not_restricted_rrc_con, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, legacy={mState=legacy, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_idle={mState=not_restricted_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, restricted={mState=restricted, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, connected_mmwave={mState=connected_mmwave, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, connected_rrc_idle={mState=connected_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}}
08-19 22:46:23.843 D/NetworkTypeController( 6608): [1] Physical channel configs updated: anchorNrCell=-1, nrBandwidths=0, nrBands=[], configs=null
08-19 22:46:23.843 D/NetworkTypeController( 6608): [1] DefaultState: process EVENT_UPDATE
08-19 22:46:23.843 D/NetworkTypeController( 6608): [1] Entering LegacyState
08-19 22:46:23.843 D/NetworkTypeController( 6608): [1] Reset timers since NR is not allowed.
08-19 22:46:23.846 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 76
08-19 22:46:23.847 D/DSMGR-1 ( 6608): mIsDataEnabled=false, prevDataEnabled=false
08-19 22:46:23.847 D/DSMGR-1 ( 6608): notifyDataEnabledChanged: enabled=false, reason=UNKNOWN, callingPackage=com.android.phone
08-19 22:46:23.850 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 77
08-19 22:46:23.851 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:23.853 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.854 E/RILD2   ( 6018): Invalid appState for updateRetryCounts.
08-19 22:46:23.855 E/RILD2   ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd2]
08-19 22:46:23.855 E/RILD2   ( 6018): IO channel write error.
08-19 22:46:23.855 E/RILD2   ( 6018): Can't send SSAC info to IMS
08-19 22:46:23.855 D/RILJ    ( 6608): [0059]< OPERATOR {, , } [PHONE1]
08-19 22:46:23.858 D/RILJ    ( 6608): [0060]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE1]
08-19 22:46:23.859 E/RILD2   ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd2]
08-19 22:46:23.860 E/RILD2   ( 6018): IO channel write error.
08-19 22:46:23.860 E/RILD2   ( 6018): Can't send SSAC info to IMS
08-19 22:46:23.860 D/RILJ    ( 6608): [0063]< OPERATOR {, , } [PHONE1]
08-19 22:46:23.862 D/RILJ    ( 6608): [0064]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE1]
08-19 22:46:24.391 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:24.391 E/RILD    ( 6018): IO channel write error.
08-19 22:46:24.391 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:24.394 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:24.394 D/RILJ    ( 6608): [UNSL]< UNSOL_RESPONSE_NETWORK_STATE_CHANGED [PHONE0]
08-19 22:46:24.419 D/GsmCdmaPhone( 6608): [1] onVoiceRegStateOrRatChanged
08-19 22:46:24.419 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, current vrs=1, vrat=0
08-19 22:46:24.419 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, result calcVrat=0
08-19 22:46:24.421 D/ImsPhone( 6608): [0] handleMessage what=82
08-19 22:46:24.422 D/ImsPhone( 6608): [0] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:24.422 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.422 D/ImsPhone( 6608): [0] handleMessage what=82
08-19 22:46:24.422 D/ImsPhone( 6608): [0] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:24.423 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.424 D/ImsPhone( 6608): [1] handleMessage what=82
08-19 22:46:24.425 D/ImsPhone( 6608): [1] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:24.425 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.425 D/ImsPhone( 6608): [1] handleMessage what=82
08-19 22:46:24.425 D/ImsPhone( 6608): [1] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:24.425 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.426 D/PhoneCfgMgr( 6608): Received EVENT_RADIO_AVAILABLE/EVENT_RADIO_ON
08-19 22:46:24.429 D/RILJ    ( 6608): [0084]> GET_MODEM_STATUS [PHONE0]
08-19 22:46:24.430 D/PhoneCfgMgr( 6608): updateRadioCapability: sending the request for getting PhoneCapability
08-19 22:46:24.431 D/RadioConfig( 6608): [0085]> GET_PHONE_CAPABILITY
08-19 22:46:24.431 E/RILD    ( 6018): IpcTxGetModemStatus()
08-19 22:46:24.431 D/PhoneCfgMgr( 6608): Received EVENT_RADIO_AVAILABLE/EVENT_RADIO_ON
08-19 22:46:24.433 D/RadioConfigResponseAidl( 6608): [0085]< GET_PHONE_CAPABILITY mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.433 E/RILD    ( 6018): IpcRxGetModemStatus()
08-19 22:46:24.433 D/RILJ    ( 6608): [0086]> GET_MODEM_STATUS [PHONE1]
08-19 22:46:24.434 D/PhoneCfgMgr( 6608): updateRadioCapability: sending the request for getting PhoneCapability
08-19 22:46:24.434 D/RILJ    ( 6608): [0084]< GET_MODEM_STATUS true [PHONE0]
08-19 22:46:24.434 D/RadioConfig( 6608): [0087]> GET_PHONE_CAPABILITY
08-19 22:46:24.434 E/RILD2   ( 6018): IpcTxGetModemStatus()
08-19 22:46:24.435 D/RadioConfigResponseAidl( 6608): [0087]< GET_PHONE_CAPABILITY mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.436 E/RILD2   ( 6018): IpcRxGetModemStatus()
08-19 22:46:24.439 D/TelephonyNetworkFactory[0]( 6608): onActivePhoneSwitch
08-19 22:46:24.441 D/RILJ    ( 6608): [0086]< GET_MODEM_STATUS true [PHONE1]
08-19 22:46:24.444 D/TelephonyNetworkFactory[1]( 6608): onActivePhoneSwitch
08-19 22:46:24.456 D/DataService( 6608): Data service created
08-19 22:46:24.459 D/DebugService( 6608): DebugService DebugService:
08-19 22:46:24.467 D/UiccController( 6608): handleMessage: Received GET_SLOT_STATUS_DONE for phoneId 0
08-19 22:46:24.467 D/UiccController( 6608): Received EVENT_SLOT_STATUS_CHANGED or EVENT_GET_SLOT_STATUS_DONE
08-19 22:46:24.468 D/UiccController( 6608): onGetSlotStatusDone: []
08-19 22:46:24.468 D/UiccController( 6608): onGetSlotStatusDone: mDefaultEuiccCardId=UNINITIALIZED
08-19 22:46:24.468 E/UiccController( 6608): Number of active ports 0 does not match the number of Phones2
08-19 22:46:24.479 E/GsmCdmaPhone( 6608): [0] reapplyUiccAppsEnablementIfNeeded: slot state=null
08-19 22:46:24.480 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 0
08-19 22:46:24.480 D/SST     ( 6608): [0] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.480 D/SST     ( 6608): [0] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.480 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:24.480 D/SST     ( 6608): [0] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.481 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:24.481 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:24.481 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.481 E/GsmCdmaPhone( 6608): [1] reapplyUiccAppsEnablementIfNeeded: slot state=null
08-19 22:46:24.481 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 1
08-19 22:46:24.481 D/SST     ( 6608): [1] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.481 D/SST     ( 6608): [1] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.481 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:24.482 D/SST     ( 6608): [1] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.482 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:24.482 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:24.482 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.486 D/UiccController( 6608): handleMessage: Received GET_ICC_STATUS_DONE for phoneId 0
08-19 22:46:24.486 D/UiccController( 6608): Received EVENT_GET_ICC_STATUS_DONE
08-19 22:46:24.486 D/UiccController( 6608): onGetIccCardStatusDone: phoneId-0 IccCardStatus: IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=0, portIndex=0}}
08-19 22:46:24.486 D/UiccSlot( 6608): Creating
08-19 22:46:24.487 E/AnswerToReset( 6608): Valid ATR string must at least contains TS and T0.
08-19 22:46:24.487 D/UiccSlot( 6608): update: radioState=1 mLastRadioState={}
08-19 22:46:24.487 D/UiccController( 6608): mUiccSlots[0] has no card. Notifying IccChangedRegistrants
08-19 22:46:24.487 D/UiccController( 6608): handleMessage: Received GET_ICC_STATUS_DONE for phoneId 1
08-19 22:46:24.487 D/UiccController( 6608): Received EVENT_GET_ICC_STATUS_DONE
08-19 22:46:24.487 D/UiccController( 6608): onGetIccCardStatusDone: phoneId-1 IccCardStatus: IccCardState {CARDSTATE_ABSENT,PINSTATE_UNKNOWN,num_apps=0,gsm_id=-1,cdma_id=-1,ims_id=-1,atr=,iccid=,eid=,SupportedMepMode=NONE,SlotPortMapping={physicalSlotIndex=1, portIndex=0}}
08-19 22:46:24.488 D/UiccSlot( 6608): Creating
08-19 22:46:24.488 E/AnswerToReset( 6608): Valid ATR string must at least contains TS and T0.
08-19 22:46:24.488 D/UiccSlot( 6608): update: radioState=1 mLastRadioState={}
08-19 22:46:24.488 D/UiccController( 6608): mUiccSlots[1] has no card. Notifying IccChangedRegistrants
08-19 22:46:24.489 D/SST     ( 6608): [0] SubscriptionListener.onSubscriptionInfoChanged
08-19 22:46:24.489 D/SST     ( 6608): [1] SubscriptionListener.onSubscriptionInfoChanged
08-19 22:46:24.494 D/Phone-0 ( 6608): isImsRegistered =false
08-19 22:46:24.494 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:24.552 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:24.589 D/SST     ( 6608): [1] SubscriptionListener.onSubscriptionInfoChanged
08-19 22:46:24.589 D/SST     ( 6608): [0] SubscriptionListener.onSubscriptionInfoChanged
08-19 22:46:24.594 D/Phone-0 ( 6608): isImsRegistered =false
08-19 22:46:24.595 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:24.647 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:24.665 D/GsmInboundSmsHandler( 6608): IdleState.processMessage: processing EVENT_RELEASE_WAKELOCK
08-19 22:46:24.668 D/GsmInboundSmsHandler( 6608): IdleState.processMessage: EVENT_RELEASE_WAKELOCK: mWakeLock released
08-19 22:46:24.669 D/CdmaInboundSmsHandler( 6608): IdleState.processMessage: processing EVENT_RELEASE_WAKELOCK
08-19 22:46:24.670 D/CdmaInboundSmsHandler( 6608): IdleState.processMessage: EVENT_RELEASE_WAKELOCK: mWakeLock released
08-19 22:46:24.671 D/SSCtr   ( 6608): clearSignalStrengthUpdateRequest subId=-1 callingUid=1002 request=SignalStrengthUpdateRequest{mSignalThresholdInfos=[] mIsReportingRequestedWhileIdle=false mIsSystemThresholdReportingRequestedWhileIdle=true mLiveTokenandroid.os.BinderProxy@7a5891e}
08-19 22:46:24.671 E/GsmCdmaPhone( 6608): [0] parseImeiInfo :: Exception received : com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED
08-19 22:46:24.671 D/GsmCdmaPhone( 6608): [0] Baseband version: A217FXXSCDXE1
08-19 22:46:24.673 D/GsmCdmaPhone( 6608): EVENT_GET_RADIO_CAPABILITY: phone rc: {mPhoneId = 0 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1}
08-19 22:46:24.673 D/GsmCdmaPhone( 6608): [0] Received exception on event55 : com.android.internal.telephony.CommandException: SIM_ABSENT
08-19 22:46:24.673 D/GsmCdmaPhone( 6608): [0] EVENT_SET_NULL_CIPHER_AND_INTEGRITY_DONE
08-19 22:46:24.673 D/GsmCdmaPhone( 6608): [0] EVENT_SET_IDENTIFIER_DISCLOSURE_ENABLED_DONE
08-19 22:46:24.673 D/GsmCdmaPhone( 6608): [0] EVENT_SET_SECURITY_ALGORITHMS_UPDATED_ENABLED_DONE
08-19 22:46:24.677 D/NetworkService( 6608): network service created
08-19 22:46:24.680 D/GsmCdmaPhone( 6608): [0] EVENT EVENT_RADIO_STATE_CHANGED
08-19 22:46:24.680 D/GsmCdmaPhone( 6608): handleRadioPowerStateChange, state= 1
08-19 22:46:24.681 D/SST     ( 6608): [0] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=1, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:24.682 D/SST     ( 6608): [0] pollState: modemTriggered=true, radioState=1
08-19 22:46:24.684 D/RILJ    ( 6608): [0088]> OPERATOR [PHONE0]
08-19 22:46:24.684 E/NRM-C-0 ( 6608): service not connected. Domain = PS
08-19 22:46:24.684 E/NRM-C-0 ( 6608): service not connected. Domain = CS
08-19 22:46:24.685 E/NRM-I-0 ( 6608): service not connected. Domain = PS
08-19 22:46:24.686 D/RILJ    ( 6608): [0089]> QUERY_NETWORK_SELECTION_MODE [PHONE0]
08-19 22:46:24.687 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:24.687 E/RILD    ( 6018): IO channel write error.
08-19 22:46:24.687 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:24.688 D/RILJ    ( 6608): [0090]> GET_CURRENT_CALLS [PHONE0]
08-19 22:46:24.688 D/RILJ    ( 6608): [0088]< OPERATOR {, , 43220} [PHONE0]
08-19 22:46:24.689 D/RILJ    ( 6608): [0091]> IMS_REGISTRATION_STATE [PHONE0]
08-19 22:46:24.690 D/GsmCdmaPhone( 6608): [0] Event EVENT_RADIO_ON Received
08-19 22:46:24.691 D/RILJ    ( 6608): [0091]< IMS_REGISTRATION_STATE {0, 1} [PHONE0]
08-19 22:46:24.691 E/RILD    ( 6018): DetermineKeepFakeCall - Don't keep fake call info as not initialized.
08-19 22:46:24.691 D/RILJ    ( 6608): [0092]> VOICE_RADIO_TECH [PHONE0]
08-19 22:46:24.692 D/RILJ    ( 6608): [0089]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE0]
08-19 22:46:24.692 E/RILD    ( 6018): VoiceRadioTechHandler - RilState: 2, VoiceRat: 0, Rat: 0
08-19 22:46:24.692 D/RILJ    ( 6608): [0090]< GET_CURRENT_CALLS {} [PHONE0]
08-19 22:46:24.693 D/RILJ    ( 6608): [0092]< VOICE_RADIO_TECH {0} [PHONE0]
08-19 22:46:24.693 D/RILJ    ( 6608): [0093]> CDMA_GET_SUBSCRIPTION_SOURCE [PHONE0]
08-19 22:46:24.694 D/SSCtr   ( 6608): onDeviceIdleStateChanged isDeviceIdle=false
08-19 22:46:24.696 E/RILC    ( 6018): responseInt: Invalid response
08-19 22:46:24.697 D/RILJ    ( 6608): [0093]< CDMA_GET_SUBSCRIPTION_SOURCE error 6 [PHONE0]
08-19 22:46:24.697 D/RilRequest( 6608): [0093]< CDMA_GET_SUBSCRIPTION_SOURCE error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret={-1} result={ when=-34s628ms what=2 target=com.android.internal.telephony.cdma.CdmaSubscriptionSourceManager }
08-19 22:46:24.697 D/RILJ    ( 6608): [0094]> SET_UNSOLICITED_RESPONSE_FILTER 127 [PHONE0]
08-19 22:46:24.698 D/RILJ    ( 6608): [0094]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE0]
08-19 22:46:24.698 D/RILJ    ( 6608): [0095]> GET_BARRING_INFO [PHONE0]
08-19 22:46:24.699 D/SatelliteController( 6608): handleCmdUpdateNtnSignalStrengthReporting: ignore request, satellite is disabled
08-19 22:46:24.699 D/DRM-0   ( 6608): Remove all retry and throttling entries, reason=RADIO_ON
08-19 22:46:24.700 D/PhoneSwitcher( 6608): No active subscriptions: resetting preferred phone to 0 for emergency
08-19 22:46:24.700 D/PhoneSwitcher( 6608): evaluating due to EVENT_RADIO_ON phone[0] 0->-1 phone[1] 0->-1
08-19 22:46:24.700 D/PhoneSwitcher( 6608): sendRilCommands: setPreferredDataModem - phoneId: 0
08-19 22:46:24.700 D/RadioConfig( 6608): [0096]> SET_PREFERRED_DATA_MODEM 0
08-19 22:46:24.701 D/RILC    ( 6018): setPreferredDataModem: modemId=0
08-19 22:46:24.701 D/SST     ( 6608): [0] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:24.702 D/SST     ( 6608): [0] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:24.702 E/RILC    ( 6018): getBarringInfoResponse: Invalid response
08-19 22:46:24.702 D/ImsPhoneCallTracker( 6608): [0] onDataEnabledChanged: enabled=false, reason=-1
08-19 22:46:24.702 D/ImsPhoneCallTracker( 6608): [0] Ignore data disabled - carrier policy indicates that data is not metered for ViLTE calls.
08-19 22:46:24.703 D/RILJ    ( 6608): [0095]< GET_BARRING_INFO error 6 [PHONE0]
08-19 22:46:24.703 D/DSRM-0  ( 6608): onMobileDataEnabledChanged: DataEnabled:false,DataStalled:false
08-19 22:46:24.703 D/RilRequest( 6608): [0095]< GET_BARRING_INFO error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret=BarringInfo {mCellIdentity=null, mBarringServiceInfos={}} result=null
08-19 22:46:24.703 D/DNC-0   ( 6608): onDataEnabledChanged: enabled=false
08-19 22:46:24.704 D/GsmInboundSmsHandler( 6608): IdleState.processMessage: processing EVENT_RELEASE_WAKELOCK
08-19 22:46:24.705 D/GsmInboundSmsHandler( 6608): IdleState.processMessage: EVENT_RELEASE_WAKELOCK: mWakeLock released
08-19 22:46:24.705 D/CdmaInboundSmsHandler( 6608): IdleState.processMessage: processing EVENT_RELEASE_WAKELOCK
08-19 22:46:24.706 D/CdmaInboundSmsHandler( 6608): IdleState.processMessage: EVENT_RELEASE_WAKELOCK: mWakeLock released
08-19 22:46:24.706 D/RadioConfigResponseAidl( 6608): [0096]< SET_PREFERRED_DATA_MODEM
08-19 22:46:24.707 E/GsmCdmaPhone( 6608): [1] parseImeiInfo :: Exception received : com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED
08-19 22:46:24.707 D/GsmCdmaPhone( 6608): EVENT_GET_RADIO_CAPABILITY: phone rc: {mPhoneId = 1 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1}
08-19 22:46:24.707 D/GsmCdmaPhone( 6608): [1] EVENT_SET_NULL_CIPHER_AND_INTEGRITY_DONE
08-19 22:46:24.707 D/GsmCdmaPhone( 6608): [1] EVENT_SET_IDENTIFIER_DISCLOSURE_ENABLED_DONE
08-19 22:46:24.707 D/GsmCdmaPhone( 6608): [1] EVENT_SET_SECURITY_ALGORITHMS_UPDATED_ENABLED_DONE
08-19 22:46:24.707 D/GsmCdmaPhone( 6608): [1] Baseband version: A217FXXSCDXE1
08-19 22:46:24.709 D/GsmCdmaPhone( 6608): [1] Received exception on event55 : com.android.internal.telephony.CommandException: SIM_ABSENT
08-19 22:46:24.709 D/GsmCdmaPhone( 6608): [1] EVENT EVENT_RADIO_STATE_CHANGED
08-19 22:46:24.709 D/GsmCdmaPhone( 6608): handleRadioPowerStateChange, state= 1
08-19 22:46:24.710 D/SST     ( 6608): [1] setPowerStateToDesired: mDeviceShuttingDown=false, mDesiredPowerState=true, getRadioState=1, mRadioPowerOffReasons=[], IMS reg state=false, pending radio off=false
08-19 22:46:24.711 D/SST     ( 6608): [1] pollState: modemTriggered=true, radioState=1
08-19 22:46:24.713 D/RILJ    ( 6608): [0097]> OPERATOR [PHONE1]
08-19 22:46:24.713 E/NRM-C-1 ( 6608): service not connected. Domain = PS
08-19 22:46:24.713 E/NRM-C-1 ( 6608): service not connected. Domain = CS
08-19 22:46:24.713 E/NRM-I-1 ( 6608): service not connected. Domain = PS
08-19 22:46:24.714 D/RILJ    ( 6608): [0098]> QUERY_NETWORK_SELECTION_MODE [PHONE1]
08-19 22:46:24.715 E/RILD2   ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd2]
08-19 22:46:24.715 E/RILD2   ( 6018): IO channel write error.
08-19 22:46:24.715 E/RILD2   ( 6018): Can't send SSAC info to IMS
08-19 22:46:24.716 D/RILJ    ( 6608): [0099]> GET_CURRENT_CALLS [PHONE1]
08-19 22:46:24.716 D/RILJ    ( 6608): [0097]< OPERATOR {, , } [PHONE1]
08-19 22:46:24.717 D/RILJ    ( 6608): [0100]> IMS_REGISTRATION_STATE [PHONE1]
08-19 22:46:24.717 D/GsmCdmaPhone( 6608): [1] Event EVENT_RADIO_ON Received
08-19 22:46:24.718 D/RILJ    ( 6608): [0100]< IMS_REGISTRATION_STATE {0, 1} [PHONE1]
08-19 22:46:24.718 E/RILD2   ( 6018): DetermineKeepFakeCall - Don't keep fake call info as not initialized.
08-19 22:46:24.718 D/RILJ    ( 6608): [0101]> VOICE_RADIO_TECH [PHONE1]
08-19 22:46:24.719 D/SSCtr   ( 6608): onDeviceIdleStateChanged isDeviceIdle=false
08-19 22:46:24.719 D/RILJ    ( 6608): [0099]< GET_CURRENT_CALLS {} [PHONE1]
08-19 22:46:24.719 E/RILD2   ( 6018): VoiceRadioTechHandler - RilState: 2, VoiceRat: 0, Rat: 0
08-19 22:46:24.719 D/RILJ    ( 6608): [0098]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE1]
08-19 22:46:24.719 D/RILJ    ( 6608): [0101]< VOICE_RADIO_TECH {0} [PHONE1]
08-19 22:46:24.720 D/RILJ    ( 6608): [0102]> SET_UNSOLICITED_RESPONSE_FILTER 127 [PHONE1]
08-19 22:46:24.721 D/RILJ    ( 6608): [0102]< SET_UNSOLICITED_RESPONSE_FILTER  [PHONE1]
08-19 22:46:24.721 D/RILJ    ( 6608): [0103]> GET_BARRING_INFO [PHONE1]
08-19 22:46:24.721 D/DRM-1   ( 6608): Remove all retry and throttling entries, reason=RADIO_ON
08-19 22:46:24.722 D/ImsPhoneCallTracker( 6608): [1] onDataEnabledChanged: enabled=false, reason=-1
08-19 22:46:24.722 D/ImsPhoneCallTracker( 6608): [1] Ignore data disabled - carrier policy indicates that data is not metered for ViLTE calls.
08-19 22:46:24.722 D/DNC-1   ( 6608): onDataEnabledChanged: enabled=false
08-19 22:46:24.722 D/DSRM-1  ( 6608): onMobileDataEnabledChanged: DataEnabled:false,DataStalled:false
08-19 22:46:24.723 D/SST     ( 6608): [1] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:24.723 D/SST     ( 6608): [1] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:24.723 E/RILC    ( 6018): getBarringInfoResponse: Invalid response
08-19 22:46:24.723 D/RILJ    ( 6608): [0103]< GET_BARRING_INFO error 6 [PHONE1]
08-19 22:46:24.724 D/RilRequest( 6608): [0103]< GET_BARRING_INFO error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret=BarringInfo {mCellIdentity=null, mBarringServiceInfos={}} result=null
08-19 22:46:24.869 D/PhoneCfgMgr( 6608): setStaticPhoneCapability: mStaticCapability mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.870 D/PhoneCfgMgr( 6608): getStaticPhoneCapability: isDefault=false, caps=mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.871 D/PhoneCfgMgr( 6608): setStaticPhoneCapability: mStaticCapability mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.871 D/PhoneCfgMgr( 6608): getStaticPhoneCapability: isDefault=false, caps=mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:24.872 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.872 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.872 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.872 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.873 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.873 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.873 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.873 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.874 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.874 D/DSM-C-1 ( 6608): onServiceConnected: ComponentInfo{com.android.phone/com.android.internal.telephony.data.CellularDataService}
08-19 22:46:24.876 D/CellularDataService( 6608): Cellular data service created for slot 1
08-19 22:46:24.876 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.876 D/DSM-C-0 ( 6608): onServiceConnected: ComponentInfo{com.android.phone/com.android.internal.telephony.data.CellularDataService}
08-19 22:46:24.878 D/CellularDataService( 6608): Cellular data service created for slot 0
08-19 22:46:24.878 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.878 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.878 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.878 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.879 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ BACKGROUND_REQUEST id=2, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.880 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.880 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.880 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.880 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.880 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.881 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.882 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ BACKGROUND_REQUEST id=2, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ]
08-19 22:46:24.883 D/UiccController( 6608): updateSimState: phoneId=0, state=ABSENT, reason=null
08-19 22:46:24.885 E/GsmCdmaPhone( 6608): [0] reapplyUiccAppsEnablementIfNeeded: slot state=CARDSTATE_ABSENT
08-19 22:46:24.885 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 0
08-19 22:46:24.885 D/SST     ( 6608): [0] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.885 D/SST     ( 6608): [0] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.885 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:24.886 D/SST     ( 6608): [0] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.886 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:24.886 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:24.886 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.886 E/GsmCdmaPhone( 6608): [1] reapplyUiccAppsEnablementIfNeeded: slot state=CARDSTATE_ABSENT
08-19 22:46:24.886 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 1
08-19 22:46:24.886 D/SST     ( 6608): [1] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.886 D/SST     ( 6608): [1] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.886 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:24.886 D/SST     ( 6608): [1] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.886 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:24.886 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:24.886 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.886 D/UiccController( 6608): updateSimState: phoneId=1, state=ABSENT, reason=null
08-19 22:46:24.887 E/GsmCdmaPhone( 6608): [0] reapplyUiccAppsEnablementIfNeeded: slot state=CARDSTATE_ABSENT
08-19 22:46:24.888 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 0
08-19 22:46:24.888 D/SST     ( 6608): [0] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.888 D/SST     ( 6608): [0] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.888 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:24.888 D/SST     ( 6608): [0] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.888 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:24.888 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:24.888 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.889 E/GsmCdmaPhone( 6608): [1] reapplyUiccAppsEnablementIfNeeded: slot state=CARDSTATE_ABSENT
08-19 22:46:24.889 D/GsmSMSDispatcher( 6608): GsmSMSDispatcher: subId = -1 slotId = 1
08-19 22:46:24.889 D/SST     ( 6608): [1] EVENT_ICC_CHANGED: SIM absent
08-19 22:46:24.889 D/SST     ( 6608): [1] cancelAllNotifications: mPrevSubId=-1
08-19 22:46:24.889 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:24.889 D/SST     ( 6608): [1] updateSpnDisplay: radio is on but out of service, set plmn='No service'
08-19 22:46:24.889 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:24.889 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:24.889 D/CarrierResolver( 6608): handleMessage: 2
08-19 22:46:24.889 D/GsmCdmaPhone( 6608): [0] EVENT_SUBSCRIPTIONS_CHANGED
08-19 22:46:24.889 I/NullCipherNotifier( 6608): Ignoring setSubscriptionMapping. Notifier is disabled.
08-19 22:46:24.890 D/GsmCdmaPhone( 6608): [1] EVENT_SUBSCRIPTIONS_CHANGED
08-19 22:46:24.890 I/NullCipherNotifier( 6608): Ignoring setSubscriptionMapping. Notifier is disabled.
08-19 22:46:24.891 D/GsmCdmaPhone( 6608): [0] EVENT_SUBSCRIPTIONS_CHANGED
08-19 22:46:24.891 I/NullCipherNotifier( 6608): Ignoring setSubscriptionMapping. Notifier is disabled.
08-19 22:46:24.891 D/GsmCdmaPhone( 6608): [1] EVENT_SUBSCRIPTIONS_CHANGED
08-19 22:46:24.891 I/NullCipherNotifier( 6608): Ignoring setSubscriptionMapping. Notifier is disabled.
08-19 22:46:24.892 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:24.944 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:24.960 D/RILJ    ( 6608): [0104]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:24.961 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:24.961 D/NRM-C-1 ( 6608): service ComponentInfo{com.android.phone/com.android.internal.telephony.CellularNetworkService} for transport WWAN is now connected.
08-19 22:46:24.961 D/RILJ    ( 6608): [0104]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE0]
08-19 22:46:24.961 D/NRM-C-0 ( 6608): service ComponentInfo{com.android.phone/com.android.internal.telephony.CellularNetworkService} for transport WWAN is now connected.
08-19 22:46:24.962 D/SST     ( 6608): [0] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 E/SST     ( 6608): [0] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 D/SST     ( 6608): [0] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 E/SST     ( 6608): [0] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 D/SST     ( 6608): [0] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 E/SST     ( 6608): [0] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:24.962 D/SmsDispatchersController( 6608): IMS registration state: false format: 3gpp
08-19 22:46:24.962 D/SST     ( 6608): [0] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:24.963 D/SST     ( 6608): [0] combinePsRegistrationStates: {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.964 D/SST     ( 6608): [0] Could not set ServiceState channel number. CellIdentity null
08-19 22:46:24.964 D/SST     ( 6608): [0] Poll ServiceState done: oldSS={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.964 D/SST     ( 6608): [0] Poll ServiceState done: newSS={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:24.964 D/SST     ( 6608): [0] Poll ServiceState done: oldMaxDataCalls=1 mNewMaxDataCalls=1 oldReasonDataDenied=-1 mNewReasonDataDenied=-1
08-19 22:46:24.965 D/SST     ( 6608): [0] pollStateDone: hasRegistered = false hasDeregistered = false hasDataAttached = {1=false, 2=false} hasDataDetached = {1=false, 2=false} hasDataRegStateChanged = {1=false, 2=false} hasRilVoiceRadioTechnologyChanged = false hasRilDataRadioTechnologyChanged = {1=true, 2=true} hasDataTransportPreferenceChanged = false hasChanged = true hasVoiceRoamingOn = false hasVoiceRoamingOff = false hasDataRoamingOn =false hasDataRoamingOff = false hasLocationChanged = false has4gHandoff = false hasMultiApnSupport = false hasLostMultiApnSupport = false hasCssIndicatorChanged = false hasNrFrequencyRangeChanged = false hasNrStateChanged = false hasAirplaneModeOnlChanged = true
08-19 22:46:24.966 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:24.966 D/SST     ( 6608): [0] updateSpnDisplay: radio is off w/ showPlmn=true plmn=null
08-19 22:46:24.966 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:24.966 D/SST     ( 6608): [0] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='null', showSpn='false', spn='null', dataSpn='', subId='-1'
08-19 22:46:24.968 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:24.970 D/LocaleTracker-0( 6608): Operator numeric changes to "43220"
08-19 22:46:24.975 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:24.975 D/LocaleTracker-0( 6608): updateLocale: Change the current country to "ir", countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}"), mCellInfoList = null
08-19 22:46:24.975 D/LocaleTracker-0( 6608): update country iso in sharedPrefs ir
08-19 22:46:24.978 D/TelephonyCountryDetector( 6608): currentNetworkCountryCodeInfo=NetworkCountryCodeInfo[phoneId: 0, countryCode: ir, timestamp: 0]
08-19 22:46:24.979 D/TelephonyCountryDetector( 6608): getCurrentNetworkCountryIso: invalid countryIso= for phoneId=1, subId=-1
08-19 22:46:24.979 D/TelephonyCountryDetector( 6608): Location update was not requested yet
08-19 22:46:24.979 D/TelephonyCountryDetector( 6608): mCountryCodeChangedRegistrants.notifyRegistrants()
08-19 22:46:24.979 D/SatelliteAccessController( 6608): handleSatelliteAllowedRegionPossiblyChanged
08-19 22:46:24.979 D/SatelliteAccessController( 6608): setIsSatelliteAllowedRegionPossiblyChanged : true
08-19 22:46:24.980 D/SatelliteAccessController( 6608): requestIsCommunicationAllowedForCurrentLocation : enablingSatellite is false
08-19 22:46:24.980 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:24.980 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:24.981 E/SatelliteModemInterface( 6608): requestIsSatelliteSupported: Satellite service is unavailable.
08-19 22:46:24.981 E/SatelliteServiceUtils( 6608): isSatelliteSupported SatelliteException: android.telephony.satellite.SatelliteManager$SatelliteException
08-19 22:46:24.982 D/SatelliteServiceUtils( 6608): isSatelliteSupported error: 10
08-19 22:46:24.982 D/SatelliteAccessController( 6608): handleIsSatelliteSupportedResult: resultCode=10
08-19 22:46:24.982 D/SatelliteAccessController( 6608): sendSatelliteAllowResultToReceivers : resultCode is 10
08-19 22:46:24.983 D/SatelliteAccessController( 6608): query satellite allowed for current location, resultCode=10, resultData=Bundle[{}]
08-19 22:46:24.983 D/SatelliteAccessController( 6608): Stop retry validating the possible change in satellite allowed region
08-19 22:46:24.983 D/SatelliteAccessController( 6608): setIsSatelliteAllowedRegionPossiblyChanged : false
08-19 22:46:24.997 D/NitzStateMachineImpl( 6608): doTimeZoneDetection: countryIsoCode=ir, nitzSignal=null, suggestion=TelephonyTimeZoneSuggestion{mSlotIndex=0, mZoneId='Asia/Tehran', mMatchType=2, mQuality=1, mDebugInfo=[findTimeZoneFromNetworkCountryCode: whenMillis=1787166984980, countryIsoCode=ir, findTimeZoneFromNetworkCountryCode: lookupResult=CountryResult{zoneId='Asia/Tehran', quality=1, mDebugInfo=One effective time zone found at whenMillis=1787166984980}, Detection reason=handleCountryDetected("ir")]}, reason=handleCountryDetected("ir")
08-19 22:46:25.000 D/SST     ( 6608): [0] Broadcasting ServiceState : {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.001 D/SatelliteController( 6608): handleStateChangedForCarrierRoamingNtnEligibility: carrierRoamingNbIotNtn flag is disabled
08-19 22:46:25.001 D/DefaultPhoneNotifier( 6608): notifyServiceStateForSubId: mRegistryMgr=android.telephony.TelephonyRegistryManager@f7f132 ss={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} sender=Handler (com.android.internal.telephony.GsmCdmaPhone) {1048021} phondId=0 subId=-1
08-19 22:46:25.001 D/SatelliteController( 6608): determineAutoConnectSystemNotification: isNtn.first = false IsNotiToShow = true mIsNotificationShowing = false
08-19 22:46:25.002 D/TelephonyRegistry( 6138): notifyServiceStateForSubscriber: INVALID subId=-1
08-19 22:46:25.023 W/ImsStats( 6608): [0] conclude: discarding UNKNOWN RAT, duration=2102
08-19 22:46:25.026 D/SST     ( 6608): [0] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=3 rat=0
08-19 22:46:25.027 D/GsmCdmaCallTracker( 6608): [0] update phone state, old=IDLE new=IDLE
08-19 22:46:25.027 D/GsmCdmaPhone( 6608): [0] EVENT_REQUEST_VOICE_RADIO_TECH_DONE: newVoiceTech=0
08-19 22:46:25.027 D/GsmCdmaPhone( 6608): [0] phoneObjectUpdater: newVoiceRadioTech=0
08-19 22:46:25.028 D/GsmCdmaPhone( 6608): [0] phoneObjectUpdater: volteReplacementRat=0
08-19 22:46:25.028 E/GsmCdmaPhone( 6608): [0] phoneObjectUpdater: newVoiceRadioTech=0 doesn't match either CDMA or GSM - error! No phone change
08-19 22:46:25.031 D/RILJ    ( 6608): [0105]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:25.032 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:25.032 D/CdmaSSM ( 6608): CDMA_SUBSCRIPTION_SOURCE event = 2
08-19 22:46:25.032 D/RILJ    ( 6608): [0105]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE0]
08-19 22:46:25.032 W/CdmaSSM ( 6608): Unable to get CDMA Subscription Source, Exception: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED, result: [I@3bb1e83
08-19 22:46:25.034 D/ADSC    ( 6608): onSubscriptionChanged: [{phone 0 score=0 dataRegState=UNKNOWN NOT_USABLE TelephonyDisplayInfo {network=UNKNOWN, overrideNetwork=NONE, isRoaming=false} signalStrength=0 listeningForEvents=false}, {phone 1 score=0 dataRegState=UNKNOWN NOT_USABLE TelephonyDisplayInfo {network=UNKNOWN, overrideNetwork=NONE, isRoaming=false} signalStrength=0 listeningForEvents=false}]
08-19 22:46:25.034 D/DNC-0   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.035 D/PhoneSwitcher( 6608): onDdsSwitchResponse: DDS switch success on phoneId = 0
08-19 22:46:25.035 D/PhoneSwitcher( 6608): notifyPreferredDataSubIdChanged to -1
08-19 22:46:25.035 D/TelephonyRegistry( 6138): notifyActiveDataSubIdChanged: activeDataSubId=-1
08-19 22:46:25.037 D/SST     ( 6608): [1] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.037 E/SST     ( 6608): [1] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.037 D/SST     ( 6608): [1] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.037 E/SST     ( 6608): [1] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.038 D/SST     ( 6608): [1] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.038 E/SST     ( 6608): [1] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.038 D/SmsDispatchersController( 6608): IMS registration state: false format: 3gpp
08-19 22:46:25.040 D/RILJ    ( 6608): [0106]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE1]
08-19 22:46:25.040 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:25.041 D/SST     ( 6608): [1] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:25.041 D/RILJ    ( 6608): [0106]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE1]
08-19 22:46:25.041 D/SST     ( 6608): [1] combinePsRegistrationStates: {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.041 D/SST     ( 6608): [1] Could not set ServiceState channel number. CellIdentity null
08-19 22:46:25.042 D/SST     ( 6608): [1] Poll ServiceState done: oldSS={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.042 D/SST     ( 6608): [1] Poll ServiceState done: newSS={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.042 D/SST     ( 6608): [1] Poll ServiceState done: oldMaxDataCalls=1 mNewMaxDataCalls=1 oldReasonDataDenied=-1 mNewReasonDataDenied=-1
08-19 22:46:25.042 D/SST     ( 6608): [1] pollStateDone: hasRegistered = false hasDeregistered = false hasDataAttached = {1=false, 2=false} hasDataDetached = {1=false, 2=false} hasDataRegStateChanged = {1=false, 2=false} hasRilVoiceRadioTechnologyChanged = false hasRilDataRadioTechnologyChanged = {1=true, 2=true} hasDataTransportPreferenceChanged = false hasChanged = true hasVoiceRoamingOn = false hasVoiceRoamingOff = false hasDataRoamingOn =false hasDataRoamingOff = false hasLocationChanged = false has4gHandoff = false hasMultiApnSupport = false hasLostMultiApnSupport = false hasCssIndicatorChanged = false hasNrFrequencyRangeChanged = false hasNrStateChanged = false hasAirplaneModeOnlChanged = true
08-19 22:46:25.043 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:25.043 D/SST     ( 6608): [1] updateSpnDisplay: radio is off w/ showPlmn=true plmn=null
08-19 22:46:25.043 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:25.043 D/SST     ( 6608): [1] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='null', showSpn='false', spn='null', dataSpn='', subId='-1'
08-19 22:46:25.046 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:25.049 D/SST     ( 6608): [1] localeOperator  is invalid
08-19 22:46:25.050 D/SST     ( 6608): [1] Broadcasting ServiceState : {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.050 D/SatelliteController( 6608): handleStateChangedForCarrierRoamingNtnEligibility: carrierRoamingNbIotNtn flag is disabled
08-19 22:46:25.050 D/DefaultPhoneNotifier( 6608): notifyServiceStateForSubId: mRegistryMgr=android.telephony.TelephonyRegistryManager@f7f132 ss={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} sender=Handler (com.android.internal.telephony.GsmCdmaPhone) {bc6f7a7} phondId=1 subId=-1
08-19 22:46:25.051 D/SatelliteController( 6608): determineAutoConnectSystemNotification: isNtn.first = false IsNotiToShow = true mIsNotificationShowing = false
08-19 22:46:25.051 D/TelephonyRegistry( 6138): notifyServiceStateForSubscriber: INVALID subId=-1
08-19 22:46:25.062 W/ImsStats( 6608): [1] conclude: discarding UNKNOWN RAT, duration=2126
08-19 22:46:25.066 D/SST     ( 6608): [1] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=3 rat=0
08-19 22:46:25.066 D/GsmCdmaCallTracker( 6608): [1] update phone state, old=IDLE new=IDLE
08-19 22:46:25.066 D/GsmCdmaPhone( 6608): [1] EVENT_REQUEST_VOICE_RADIO_TECH_DONE: newVoiceTech=0
08-19 22:46:25.066 D/GsmCdmaPhone( 6608): [1] phoneObjectUpdater: newVoiceRadioTech=0
08-19 22:46:25.067 D/GsmCdmaPhone( 6608): [1] phoneObjectUpdater: volteReplacementRat=0
08-19 22:46:25.067 E/GsmCdmaPhone( 6608): [1] phoneObjectUpdater: newVoiceRadioTech=0 doesn't match either CDMA or GSM - error! No phone change
08-19 22:46:25.067 D/DNC-1   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.094 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.094 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.094 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.094 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.094 D/PhoneCfgMgr( 6608): getStaticPhoneCapability: isDefault=false, caps=mMaxActiveVoiceSubscriptions=1 mMaxActiveDataSubscriptions=2 mNetworkValidationBeforeSwitchSupported=false mDeviceNrCapability []
08-19 22:46:25.097 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.096, evaluation result=null] shouldApply false
08-19 22:46:25.098 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.097, evaluation result=null] shouldApply false
08-19 22:46:25.098 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.098, evaluation result=null] shouldApply false
08-19 22:46:25.100 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.099, evaluation result=null] shouldApply false
08-19 22:46:25.100 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.101 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.100, evaluation result=null] shouldApply false
08-19 22:46:25.101 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ]
08-19 22:46:25.102 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.101, evaluation result=null] shouldApply false
08-19 22:46:25.102 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.101, evaluation result=null] shouldApply false
08-19 22:46:25.103 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.103, evaluation result=null] shouldApply false
08-19 22:46:25.104 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.103, evaluation result=null] shouldApply false
08-19 22:46:25.104 D/DNC-1   ( 6608): onDataServiceBindingChanged: WWAN data service is bound.
08-19 22:46:25.105 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.104, evaluation result=null] shouldApply false
08-19 22:46:25.105 D/DNC-0   ( 6608): onDataServiceBindingChanged: WWAN data service is bound.
08-19 22:46:25.106 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.105, evaluation result=null] shouldApply false
08-19 22:46:25.107 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.107, evaluation result=null] shouldApply false
08-19 22:46:25.108 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.108, evaluation result=null] shouldApply false
08-19 22:46:25.109 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.108, evaluation result=null] shouldApply false
08-19 22:46:25.109 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.109, evaluation result=null] shouldApply false
08-19 22:46:25.110 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.109, evaluation result=null] shouldApply false
08-19 22:46:25.111 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.111, evaluation result=null] shouldApply false
08-19 22:46:25.112 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.112, evaluation result=null] shouldApply false
08-19 22:46:25.113 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.112, evaluation result=null] shouldApply false
08-19 22:46:25.114 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ BACKGROUND_REQUEST id=2, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.113, evaluation result=null] shouldApply false
08-19 22:46:25.115 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.114, evaluation result=null] shouldApply false
08-19 22:46:25.116 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.115, evaluation result=null] shouldApply false
08-19 22:46:25.116 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.116, evaluation result=null] shouldApply false
08-19 22:46:25.117 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.116, evaluation result=null] shouldApply false
08-19 22:46:25.118 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.118, evaluation result=null] shouldApply false
08-19 22:46:25.119 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.118, evaluation result=null] shouldApply false
08-19 22:46:25.119 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.119, evaluation result=null] shouldApply false
08-19 22:46:25.120 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.119, evaluation result=null] shouldApply false
08-19 22:46:25.121 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.121, evaluation result=null] shouldApply false
08-19 22:46:25.122 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.121, evaluation result=null] shouldApply false
08-19 22:46:25.122 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.121, evaluation result=null] shouldApply false
08-19 22:46:25.123 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.123, evaluation result=null] shouldApply false
08-19 22:46:25.124 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.123, evaluation result=null] shouldApply false
08-19 22:46:25.125 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.124, evaluation result=null] shouldApply false
08-19 22:46:25.125 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.124, evaluation result=null] shouldApply false
08-19 22:46:25.126 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.126, evaluation result=null] shouldApply false
08-19 22:46:25.127 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.126, evaluation result=null] shouldApply false
08-19 22:46:25.127 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.126, evaluation result=null] shouldApply false
08-19 22:46:25.128 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.128, evaluation result=null] shouldApply false
08-19 22:46:25.129 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.128, evaluation result=null] shouldApply false
08-19 22:46:25.130 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.129, evaluation result=null] shouldApply false
08-19 22:46:25.130 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.129, evaluation result=null] shouldApply false
08-19 22:46:25.131 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.130, evaluation result=null] shouldApply false
08-19 22:46:25.132 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.132, evaluation result=null] shouldApply false
08-19 22:46:25.133 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.133, evaluation result=null] shouldApply false
08-19 22:46:25.134 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.133, evaluation result=null] shouldApply false
08-19 22:46:25.134 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.134, evaluation result=null] shouldApply false
08-19 22:46:25.135 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.135, evaluation result=null] shouldApply false
08-19 22:46:25.136 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ BACKGROUND_REQUEST id=2, [ Transports: CELLULAR Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.135, evaluation result=null] shouldApply false
08-19 22:46:25.136 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.135, evaluation result=null] shouldApply false
08-19 22:46:25.137 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.137, evaluation result=null] shouldApply false
08-19 22:46:25.138 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.137, evaluation result=null] shouldApply false
08-19 22:46:25.138 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.137, evaluation result=null] shouldApply false
08-19 22:46:25.139 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.139, evaluation result=null] shouldApply false
08-19 22:46:25.140 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.139, evaluation result=null] shouldApply false
08-19 22:46:25.140 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.139, evaluation result=null] shouldApply false
08-19 22:46:25.141 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.140, evaluation result=null] shouldApply false
08-19 22:46:25.142 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.142, evaluation result=null] shouldApply false
08-19 22:46:25.142 D/SMSVC   ( 6608): updateSimState: slot 0 ABSENT
08-19 22:46:25.142 D/SMSVC   ( 6608): updateSubscription: phoneId=0, simState=ABSENT
08-19 22:46:25.143 D/SMSVC   ( 6608):   [UiccSlot: mActive=true, mIccId={0=}, mIsEuicc=false, MEP=false, mPortIdxToPhoneId={0=-1}, mEid=null, mCardState={0=CARDSTATE_ABSENT} mSupportedMepMode=NONE]
08-19 22:46:25.143 D/SMSVC   ( 6608):   [UiccSlot: mActive=true, mIccId={0=}, mIsEuicc=false, MEP=false, mPortIdxToPhoneId={0=-1}, mEid=null, mCardState={0=CARDSTATE_ABSENT} mSupportedMepMode=NONE]
08-19 22:46:25.143 D/SMSVC   ( 6608): updateSubscription: Re-enable Uicc application on sub 1
08-19 22:46:25.144 D/SMSVC   ( 6608): updateSubscription: Re-enable Uicc application on sub 2
08-19 22:46:25.144 D/SMSVC   ( 6608): setNumberFromIms: subId=-1, number=
08-19 22:46:25.144 E/SDMGR   ( 6608): Subscription doesn't exist. subId=-1, columnName=phone_number_source_ims
08-19 22:46:25.145 E/SMSVC   ( 6608): setNumberFromIms: invalid subId=-1
08-19 22:46:25.145 D/SMSVC   ( 6608): areAllSubscriptionsLoaded: SIM 1 state is still unknown.
08-19 22:46:25.146 D/SMSVC   ( 6608): updateSimState: slot 1 ABSENT
08-19 22:46:25.146 D/SMSVC   ( 6608): updateSubscription: phoneId=1, simState=ABSENT
08-19 22:46:25.146 D/SMSVC   ( 6608):   [UiccSlot: mActive=true, mIccId={0=}, mIsEuicc=false, MEP=false, mPortIdxToPhoneId={0=-1}, mEid=null, mCardState={0=CARDSTATE_ABSENT} mSupportedMepMode=NONE]
08-19 22:46:25.146 D/SMSVC   ( 6608):   [UiccSlot: mActive=true, mIccId={0=}, mIsEuicc=false, MEP=false, mPortIdxToPhoneId={0=-1}, mEid=null, mCardState={0=CARDSTATE_ABSENT} mSupportedMepMode=NONE]
08-19 22:46:25.146 D/SMSVC   ( 6608): updateSubscription: Re-enable Uicc application on sub 1
08-19 22:46:25.146 D/SMSVC   ( 6608): updateSubscription: Re-enable Uicc application on sub 2
08-19 22:46:25.147 D/SMSVC   ( 6608): setNumberFromIms: subId=-1, number=
08-19 22:46:25.147 E/SDMGR   ( 6608): Subscription doesn't exist. subId=-1, columnName=phone_number_source_ims
08-19 22:46:25.147 E/SMSVC   ( 6608): setNumberFromIms: invalid subId=-1
08-19 22:46:25.147 D/SMSVC   ( 6608): Notify all subscriptions loaded.
08-19 22:46:25.148 D/DIC-0   ( 6608): ServiceState updated, isRoaming=false
08-19 22:46:25.149 D/NetworkTypeController( 6608): [0] LegacyState: process EVENT_SERVICE_STATE_CHANGED
08-19 22:46:25.149 D/NetworkTypeController( 6608): [0] Reset timers since NR is not allowed.
08-19 22:46:25.149 D/NetworkTypeController( 6608): [0] ServiceState updated: {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.149 D/NetworkTypeController( 6608): [0] Reset timers since 2G and 3G don't need NR timers.
08-19 22:46:25.150 D/DNC-0   ( 6608): onServiceStateChanged: changed to {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.150 D/DNC-0   ( 6608): onServiceStateChanged: [WWAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] [WLAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] . Evaluating network requests is not needed, evaluating existing data networks is not needed.
08-19 22:46:25.150 D/EmergencyNumberTracker( 6608): [0]ACTION_NETWORK_COUNTRY_CHANGED: PhoneId: 0 CountryIso: ir
08-19 22:46:25.152 D/Phone-0 ( 6608): isImsRegistered =false
08-19 22:46:25.153 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:25.205 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:25.220 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.220 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.220 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:25.220 D/ImsPhone( 6608): [0] handleMessage what=83
08-19 22:46:25.221 D/ImsPhone( 6608): [0] handleMessage what=82
08-19 22:46:25.221 D/ImsPhone( 6608): [0] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.221 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.221 D/ImsPhone( 6608): [0] handleMessage what=82
08-19 22:46:25.221 D/ImsPhone( 6608): [0] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.222 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.222 D/GsmCdmaPhone( 6608): [0] onVoiceRegStateOrRatChanged
08-19 22:46:25.222 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, current vrs=3, vrat=0
08-19 22:46:25.222 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, result calcVrat=0
08-19 22:46:25.222 D/TelephonyNetworkFactory[0]( 6608): onActivePhoneSwitch
08-19 22:46:25.223 D/TelephonyNetworkFactory[1]( 6608): onActivePhoneSwitch
08-19 22:46:25.223 D/DIC-1   ( 6608): ServiceState updated, isRoaming=false
08-19 22:46:25.224 D/NetworkTypeController( 6608): [1] LegacyState: process EVENT_SERVICE_STATE_CHANGED
08-19 22:46:25.224 D/NetworkTypeController( 6608): [1] Reset timers since NR is not allowed.
08-19 22:46:25.224 D/NetworkTypeController( 6608): [1] ServiceState updated: {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.224 D/NetworkTypeController( 6608): [1] Reset timers since 2G and 3G don't need NR timers.
08-19 22:46:25.224 D/DNC-1   ( 6608): onServiceStateChanged: changed to {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.225 D/DNC-1   ( 6608): onServiceStateChanged: [WWAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] [WLAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] . Evaluating network requests is not needed, evaluating existing data networks is not needed.
08-19 22:46:25.225 D/LocaleTracker-1( 6608): updateLocale: countryIso = , countryIsoDebugInfo = empty as default
08-19 22:46:25.225 D/LocaleTracker-1( 6608): updateLocale: Change the current country to "", countryIsoDebugInfo = empty as default, mCellInfoList = null
08-19 22:46:25.226 D/TelephonyCountryDetector( 6608): currentNetworkCountryCodeInfo=NetworkCountryCodeInfo[phoneId: 1, countryCode: , timestamp: 0]
08-19 22:46:25.227 D/TelephonyCountryDetector( 6608): handleNetworkCountryCodeChangedEvent: Got invalid or empty country code for phoneId=1
08-19 22:46:25.227 D/TelephonyCountryDetector( 6608): getCurrentNetworkCountryIso: invalid countryIso= for phoneId=1, subId=-1
08-19 22:46:25.227 D/TelephonyCountryDetector( 6608): Location update was not requested yet
08-19 22:46:25.227 D/TelephonyCountryDetector( 6608): mCountryCodeChangedRegistrants.notifyRegistrants()
08-19 22:46:25.227 D/SatelliteAccessController( 6608): handleSatelliteAllowedRegionPossiblyChanged
08-19 22:46:25.227 D/SatelliteAccessController( 6608): setIsSatelliteAllowedRegionPossiblyChanged : true
08-19 22:46:25.227 D/SatelliteAccessController( 6608): requestIsCommunicationAllowedForCurrentLocation : enablingSatellite is false
08-19 22:46:25.228 E/SatelliteModemInterface( 6608): requestIsSatelliteSupported: Satellite service is unavailable.
08-19 22:46:25.228 E/SatelliteServiceUtils( 6608): isSatelliteSupported SatelliteException: android.telephony.satellite.SatelliteManager$SatelliteException
08-19 22:46:25.228 D/SatelliteServiceUtils( 6608): isSatelliteSupported error: 10
08-19 22:46:25.228 D/SatelliteAccessController( 6608): handleIsSatelliteSupportedResult: resultCode=10
08-19 22:46:25.228 D/SatelliteAccessController( 6608): sendSatelliteAllowResultToReceivers : resultCode is 10
08-19 22:46:25.228 D/SatelliteAccessController( 6608): query satellite allowed for current location, resultCode=10, resultData=Bundle[{}]
08-19 22:46:25.229 D/SatelliteAccessController( 6608): Stop retry validating the possible change in satellite allowed region
08-19 22:46:25.229 D/SatelliteAccessController( 6608): setIsSatelliteAllowedRegionPossiblyChanged : false
08-19 22:46:25.229 D/LocaleTracker-1( 6608): updateLocale: timeZoneCountryIso = , timeZoneCountryIsoDebugInfo = empty as default
08-19 22:46:25.229 D/NitzStateMachineImpl( 6608): handleCountryUnavailable: mLatestNitzSignal=null
08-19 22:46:25.229 D/NitzStateMachineImpl( 6608): doTimeZoneDetection: countryIsoCode=null, nitzSignal=null, suggestion=TelephonyTimeZoneSuggestion{mSlotIndex=1, mZoneId='null', mMatchType=0, mQuality=0, mDebugInfo=[getTimeZoneSuggestion: nitzSignal=null, countryIsoCode=null, Detection reason=handleCountryUnavailable]}, reason=handleCountryUnavailable
08-19 22:46:25.230 D/ImsPhone( 6608): [1] handleMessage what=83
08-19 22:46:25.230 D/ImsPhone( 6608): [1] handleMessage what=82
08-19 22:46:25.230 D/ImsPhone( 6608): [1] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.230 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.231 D/ImsPhone( 6608): [1] handleMessage what=82
08-19 22:46:25.231 D/ImsPhone( 6608): [1] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.231 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=null, mOperatorAlphaShortRaw=null, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.231 D/GsmCdmaPhone( 6608): [1] onVoiceRegStateOrRatChanged
08-19 22:46:25.231 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, current vrs=3, vrat=0
08-19 22:46:25.231 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, result calcVrat=0
08-19 22:46:25.232 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.231, evaluation result=null] shouldApply false
08-19 22:46:25.233 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.232, evaluation result=null] shouldApply false
08-19 22:46:25.234 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.233, evaluation result=null] shouldApply false
08-19 22:46:25.235 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.235, evaluation result=null] shouldApply false
08-19 22:46:25.236 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.235, evaluation result=null] shouldApply false
08-19 22:46:25.236 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:25.235, evaluation result=null] shouldApply false
08-19 22:46:25.237 D/DRM-1   ( 6608): Remove all retry and throttling entries, reason=DATA_SERVICE_BOUND
08-19 22:46:25.237 D/DRM-0   ( 6608): Remove all retry and throttling entries, reason=DATA_SERVICE_BOUND
08-19 22:46:25.238 D/UiccController( 6608): Broadcasting intent ACTION_SIM_STATE_CHANGED ABSENT reason null for phone: 0 sub: -1
08-19 22:46:25.241 D/UiccController( 6608): Broadcasting intent ACTION_SIM_CARD_STATE_CHANGED ABSENT for phone: 0 slot: 0 port: 0 sub: -1
08-19 22:46:25.254 D/UiccController( 6608): updateSimState: resolve carrier id and update carrier services.
08-19 22:46:25.254 D/CarrierResolver( 6608): [resolveSubscriptionCarrierId] simState: ABSENT
08-19 22:46:25.264 D/UiccController( 6608): Broadcasting intent ACTION_SIM_STATE_CHANGED ABSENT reason null for phone: 1 sub: -1
08-19 22:46:25.268 D/UiccController( 6608): Broadcasting intent ACTION_SIM_CARD_STATE_CHANGED ABSENT for phone: 1 slot: 1 port: 0 sub: -1
08-19 22:46:25.276 D/UiccController( 6608): updateSimState: resolve carrier id and update carrier services.
08-19 22:46:25.277 D/CarrierResolver( 6608): [resolveSubscriptionCarrierId] simState: ABSENT
08-19 22:46:25.279 D/EmergencyNumberTracker( 6608): [0]updateEmergencyNumberListDatabaseAndNotify(): receiving countryIso: ir
08-19 22:46:25.288 D/EmergencyNumberTracker( 6608): [0]ir asset emergency database is loaded. Ver: 2 Phone Id: 0 countryIso: ir
08-19 22:46:25.289 E/EmergencyNumberTracker( 6608): [0]Cache ota emergency database IOException: java.io.FileNotFoundException: /data/misc/emergencynumberdb/emergency_number_db: open failed: ENOENT (No such file or directory)
08-19 22:46:25.289 D/EmergencyNumberTracker( 6608): [0]Using Asset Emergency database. Version: 2
08-19 22:46:25.291 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.291 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.293 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.293 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.294 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.294 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.295 D/EmergencyNumberTracker( 6608): [0]notifyEmergencyNumberList(): notified
08-19 22:46:25.296 D/EmergencyNumberTracker( 6608): [1]updateEmergencyNumberListDatabaseAndNotify(): receiving countryIso: ir
08-19 22:46:25.304 D/EmergencyNumberTracker( 6608): [1]ir asset emergency database is loaded. Ver: 2 Phone Id: 1 countryIso: ir
08-19 22:46:25.305 E/EmergencyNumberTracker( 6608): [1]Cache ota emergency database IOException: java.io.FileNotFoundException: /data/misc/emergencynumberdb/emergency_number_db: open failed: ENOENT (No such file or directory)
08-19 22:46:25.305 D/EmergencyNumberTracker( 6608): [1]Using Asset Emergency database. Version: 2
08-19 22:46:25.306 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.307 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.308 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.308 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.309 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.309 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.309 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.310 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.310 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.310 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.311 D/EmergencyNumberTracker( 6608): [1]notifyEmergencyNumberList(): notified
08-19 22:46:25.312 D/SSCtr   ( 6608): clearSignalStrengthUpdateRequest subId=-1 callingUid=1002 request=SignalStrengthUpdateRequest{mSignalThresholdInfos=[] mIsReportingRequestedWhileIdle=false mIsSystemThresholdReportingRequestedWhileIdle=true mLiveTokenandroid.os.BinderProxy@7a5891e}
08-19 22:46:25.312 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:25.367 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:25.380 D/EmergencyNumberTracker( 6608): [1]ACTION_NETWORK_COUNTRY_CHANGED: PhoneId: 1 CountryIso: 
08-19 22:46:25.383 D/Phone-0 ( 6608): isImsRegistered =false
08-19 22:46:25.383 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:25.435 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:25.448 D/SAT     ( 6608): [0]onSimAbsent, reset activation state to UNKNOWN
08-19 22:46:25.448 D/SAT     ( 6608): [0]setVoiceActivationState=0
08-19 22:46:25.449 D/SAT     ( 6608): [0]setDataActivationState=0
08-19 22:46:25.450 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.451 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.451 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.451 D/SAT     ( 6608): [1]onSimAbsent, reset activation state to UNKNOWN
08-19 22:46:25.451 D/SAT     ( 6608): [1]setVoiceActivationState=0
08-19 22:46:25.452 D/SAT     ( 6608): [1]setDataActivationState=0
08-19 22:46:25.452 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.453 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.453 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.459 D/RILJ    ( 6608): [0107]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:25.460 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:25.460 D/EmergencyNumberTracker( 6608): [1]updateEmergencyNumberListDatabaseAndNotify(): receiving countryIso: 
08-19 22:46:25.460 D/RILJ    ( 6608): [0107]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE0]
08-19 22:46:25.460 D/EmergencyNumberTracker( 6608): [1]updateEmergencyNumberListDatabaseAndNotify(): using cached APM country ir
08-19 22:46:25.469 D/EmergencyNumberTracker( 6608): [1]ir asset emergency database is loaded. Ver: 2 Phone Id: 1 countryIso: ir
08-19 22:46:25.470 E/EmergencyNumberTracker( 6608): [1]Cache ota emergency database IOException: java.io.FileNotFoundException: /data/misc/emergencynumberdb/emergency_number_db: open failed: ENOENT (No such file or directory)
08-19 22:46:25.470 D/EmergencyNumberTracker( 6608): [1]Using Asset Emergency database. Version: 2
08-19 22:46:25.471 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.471 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.472 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.472 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.472 E/EmergencyNumberTracker( 6608): [0]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.473 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.473 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.473 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.473 E/EmergencyNumberTracker( 6608): [1]getEmergencyNumberListFromEccListDatabaseAndTest: radio indication is unavailable in 1.4 HAL.
08-19 22:46:25.474 E/EmergencyNumber( 6608): Found unexpected duplicate numbers [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=] vs [EmergencyNumber: 110, countryIso=ir, mnc=, src=db , routing=unknown, categories=police , urns=]
08-19 22:46:25.475 D/EmergencyNumberTracker( 6608): [1]notifyEmergencyNumberList(): notified
08-19 22:46:25.475 E/Phone-0 ( 6608): [0] getUserHandle: ex=java.lang.IllegalArgumentException: [getSubscriptionUserHandle]: Invalid subscriptionId: -1
08-19 22:46:25.527 D/ImsManagerIM [0]( 6608): ImsService not up yet - timeout waiting for connection.
08-19 22:46:25.538 E/CarrierActionAgent( 6608): [0]Unsupported action: 7
08-19 22:46:25.538 D/CarrierActionAgent( 6608): [0]EVENT_SIM_STATE_CHANGED status: ABSENT
08-19 22:46:25.553 D/SAT     ( 6608): [0]onSimAbsent, reset activation state to UNKNOWN
08-19 22:46:25.553 D/SAT     ( 6608): [0]setVoiceActivationState=0
08-19 22:46:25.554 D/SAT     ( 6608): [0]setDataActivationState=0
08-19 22:46:25.555 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.555 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.555 D/AnkitSimAbsent( 6608): Sim is Absent
08-19 22:46:25.556 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.556 D/SAT     ( 6608): [1]onSimAbsent, reset activation state to UNKNOWN
08-19 22:46:25.556 D/SAT     ( 6608): [1]setVoiceActivationState=0
08-19 22:46:25.557 D/SAT     ( 6608): [1]setDataActivationState=0
08-19 22:46:25.559 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.559 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.559 D/SMSDispatcher( 6608): Received broadcast android.intent.action.SIM_STATE_CHANGED
08-19 22:46:25.560 D/AnkitSimAbsent( 6608): Sim is Absent
08-19 22:46:25.561 D/PinStorage( 6608): SIM card/application changed[0]: ABSENT
08-19 22:46:25.561 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.561 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.561 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:25.562 E/CarrierActionAgent( 6608): [1]Unsupported action: 7
08-19 22:46:25.562 D/CarrierActionAgent( 6608): [1]EVENT_SIM_STATE_CHANGED status: ABSENT
08-19 22:46:25.563 D/DNC-0   ( 6608): onSimStateChanged: state=ABSENT
08-19 22:46:25.563 D/DNC-0   ( 6608): onSimStateChanged: SIM absent.
08-19 22:46:25.564 D/DNC-0   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.564 D/PinStorage( 6608): SIM card/application changed[1]: ABSENT
08-19 22:46:25.564 D/AnkitSimAbsent( 6608): Sim is Absent
08-19 22:46:25.565 D/AnkitSimAbsent( 6608): Sim is Absent
08-19 22:46:25.566 D/LocaleTracker-1( 6608): updateLocale: countryIso = , countryIsoDebugInfo = empty as default
08-19 22:46:25.566 D/LocaleTracker-1( 6608): updateLocale: timeZoneCountryIso = , timeZoneCountryIsoDebugInfo = empty as default
08-19 22:46:25.566 D/NitzStateMachineImpl( 6608): handleCountryUnavailable: mLatestNitzSignal=null
08-19 22:46:25.566 D/NitzStateMachineImpl( 6608): doTimeZoneDetection: countryIsoCode=null, nitzSignal=null, suggestion=TelephonyTimeZoneSuggestion{mSlotIndex=1, mZoneId='null', mMatchType=0, mQuality=0, mDebugInfo=[getTimeZoneSuggestion: nitzSignal=null, countryIsoCode=null, Detection reason=handleCountryUnavailable]}, reason=handleCountryUnavailable
08-19 22:46:25.567 D/DNC-1   ( 6608): onSimStateChanged: state=ABSENT
08-19 22:46:25.567 D/DNC-1   ( 6608): onSimStateChanged: SIM absent.
08-19 22:46:25.567 D/DNC-1   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.658 D/SatelliteController( 6608): handleCarrierConfigChanged(): slotIndex(0), subId(-1), carrierId(-1), specificCarrierId(-1)
08-19 22:46:25.658 D/SatelliteEntitlementController( 6608): handleCarrierConfigChanged(): slotIndex(0), subId(-1), carrierId(-1), specificCarrierId(-1)
08-19 22:46:25.658 D/SatelliteEntitlementController( 6608): processSimChanged prev subId:-1
08-19 22:46:25.676 D/CarrierSignalAgent( 6608): [0]Loading carrier config: carrier_app_wake_signal_config
08-19 22:46:25.677 D/CarrierSignalAgent( 6608): [0]Loading carrier config: carrier_app_no_wake_signal_config
08-19 22:46:25.683 E/SSCtr   ( 6608): Invalid parameters for NR RSRP boost
08-19 22:46:25.687 D/RILJ    ( 6608): [0108]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE0]
08-19 22:46:25.688 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:25.689 D/RILJ    ( 6608): [0108]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE0]
08-19 22:46:25.691 E/ANM-0   ( 6608): Can't find the binding package
08-19 22:46:25.694 D/SST     ( 6608): [0] CarrierConfigChange PersistableBundle[{imsvoice.voice_on_default_bearer_supported_bool=false, imsvoice.rtp_inactivity_time_threshold_millis_long=5000, imsss.ut_transport_type_int=1, imsemergency.emergency_call_setup_timer_on_current_network_sec_int=0, carrier_volte_provisioned_bool=false, support_cdma_1x_voice_calls_bool=true, support_ss_over_cdma_bool=false, disable_charge_indication_bool=false, ims.sip_timer_t4_millis_int=17000, support_tdscdma_bool=false, httpSocketTimeout=60000, allowed_initial_attach_apn_types_string_array=[ia, default], disable_supplementary_services_in_airplane_mode_bool=false, call_barring_default_service_class_int=1, call_redirection_service_component_name_string=null, carrier_wfc_supports_wifi_only_bool=false, carrier_default_actions_on_default_network_available_string_array=[false: 7, true: 8], imsvoice.minimum_session_expires_timer_sec_int=90, vonr_on_by_default_bool=true, iwlan_handover_policy_string_array=[source=GERAN|UTRAN|EUTRAN|NGRAN|IWLAN, target=GERAN|UTRAN|EUTRAN|NGRAN|IWLAN, type=allowed], operator_selection_expand_bool=true, disable_cdma_activation_code_bool=false, simplified_network_settings_bool=false, imsemergency.emergency_registration_timer_millis_int=10000, call_forwarding_when_unanswered_supported_bool=true, imsvt.h264_payload_description_bundle=PersistableBundle[{99=PersistableBundle[{}], 100=PersistableBundle[{imsvt.video_codec_attribute_packetization_mode_int=0}]}], support_tdscdma_roaming_networks_string_array=null, opportunistic.5g_data_switch_hysteresis_time_long=2000, ims.sip_timer_d_millis_int=130000, gps.lpp_profile=2, call_barring_visibility_bool=false, gba_mode_int=1, ims.registration_subscribe_expiry_timer_sec_int=600000, gps.es_extension_sec=0, enable_apps_string_array=null, 5g_icon_display_secondary_grace_period_string=, carrier_default_wfc_ims_roaming_enabled_bool=false, cdma_nonroaming_networks_string_array=null, imsss.ut_as_server_fqdn_string=, imsemergency.emergency_lte_preferred_after_nr_failed_bool=false, signal_strength_nr_nsa_use_lte_as_primary_bool=true, 5g_ultra_wideband_icon_nsa_band_mode=2147483647, aliasMinChars=2, fdn_number_length_limit_int=20, support_ims_call_forwarding_while_roaming_bool=true, wfc_data_spn_format_idx_int=0, hide_sim_lock_settings_bool=false, premium_capability_network_setup_time_millis_long=300000, satellite_esos_supported_bool=false, drop_video_call_when_answering_audio_call_bool=false, data_stall_recovery_timers_long_array=[180000, 180000, 180000, 180000], satellite_connection_hysteresis_sec_int=180, opportunistic_esim_download_via_wifi_only_bool=false, imsss.xcap_over_ut_supported_rats_int_array=[3, 5, 6], ci_action_on_sys_update_bool=false, carrier_certificate_string_array=[], convert_cdma_caller_id_mmi_codes_while_roaming_on_3gpp_bool=false, support_enhanced_call_blocking_bool=true, iwlan.ike_rekey_hard_timer_in_sec=14400, vvm_port_number_int=0, premium_capability_notification_display_timeout_millis_long=1800000, wifi_connectivity_extend_cell_delay=-1, imsemergency.emergency_requires_ims_registration_bool=false, carrier_default_wfc_ims_enabled_bool=false, iwlan.ike_session_encryption_aes_ctr_key_size_int_array=[128, 192, 256], dial_string_replace_string_array=null, opportunistic_network_entry_threshold_bandwidth_int=1024, imsemergency.emergency_requires_volte_enabled_bool=false, opportunistic_network_data_switch_exit_hysteresis_time_long=3000, imsss.use_csfb_on_xcap_over_ut_failure_bool=true, gsm_nonroaming_networks_string_array=null, imsserviceentitlement.ims_provisioning_bool=false, wifi.avoid_5ghz_softap_for_laa_bool=false, hide_ims_apn_bool=false, carrier_network_service_wlan_class_override_string=, vvm_destination_number_string=, ims.ipsec_encryption_algorithms_int_array=[0, 1, 2], opportunistic.5g_backoff_time_long=10000, enable_cross_sim_calling_on_opportunistic_data_bool=false, vonr_setting_visibility_bool=true, imssms.sms_over_ims_supported_bool=true, dtmf_type_enabled_bool=false, ims.sip_timer_f_millis_int=128000, allow_video_calling_fallback_bool=true, nr_advanced_threshold
08-19 22:46:25.694 E/Phone-0 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.694 E/Phone-0 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.694 V/Phone-0 ( 6608): getCallForwardingIndicator: iccForwardingFlag=null, sharedPrefFlag=0
08-19 22:46:25.695 D/DefaultPhoneNotifier( 6608): notifyCallForwardingChanged: subId=-1, isCFActive=false
08-19 22:46:25.695 E/Phone-0 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.695 E/Phone-0 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.695 V/Phone-0 ( 6608): getCallForwardingIndicator: iccForwardingFlag=null, sharedPrefFlag=0
08-19 22:46:25.695 D/SST     ( 6608): [0] pollState: modemTriggered=false, radioState=1
08-19 22:46:25.696 D/RILJ    ( 6608): [0109]> GSM_SET_BROADCAST_CONFIG with 7 configs :  [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4352,4354] Code [0,255] ENABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4355,4355] Code [0,255] DISABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4356,4356] Code [0,255] ENABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4370,4379] Code [0,255] ENABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4380,4382] Code [0,255] DISABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4383,4392] Code [0,255] ENABLED [PHONE0]
08-19 22:46:25.697 D/RILJ    ( 6608): SmsBroadcastConfigInfo: Id [4393,4395] Code [0,255] DISABLED [PHONE0]
08-19 22:46:25.698 D/RILJ    ( 6608): [0110]> OPERATOR [PHONE0]
08-19 22:46:25.698 E/RILD    ( 6018): GetBroadcastSmsConfig: selectedId 0x80 msgIdCount 24
08-19 22:46:25.698 E/NRM-I-0 ( 6608): service not connected. Domain = PS
08-19 22:46:25.699 E/RILD    ( 6018): enableCb: 1, cbSelectionId: 0x80
08-19 22:46:25.699 D/RILJ    ( 6608): [0111]> DATA_REGISTRATION_STATE [PHONE0]
08-19 22:46:25.699 D/RILJ    ( 6608): getDataRegistrationState: overrideHalVersion=null [PHONE0]
08-19 22:46:25.700 D/RILJ    ( 6608): [0112]> QUERY_NETWORK_SELECTION_MODE [PHONE0]
08-19 22:46:25.700 D/NRM-C-0 ( 6608): Carrier config changed. Try to bind network service.
08-19 22:46:25.701 D/RILJ    ( 6608): [0113]> VOICE_REGISTRATION_STATE [PHONE0]
08-19 22:46:25.701 D/RILJ    ( 6608): getVoiceRegistrationState: overrideHalVersion=null [PHONE0]
08-19 22:46:25.701 D/NRM-C-0 ( 6608): Service com.android.phone already bound or being bound.
08-19 22:46:25.701 D/CSST    ( 6608): onCarrierConfigChanged: slotIndex=0, subId=-1, carrierId=-1
08-19 22:46:25.702 E/RILD    ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd]
08-19 22:46:25.702 E/RILD    ( 6018): IO channel write error.
08-19 22:46:25.702 E/RILD    ( 6018): Can't send SSAC info to IMS
08-19 22:46:25.702 I/CSST    ( 6608): reading time to delay notification pref network: -1
08-19 22:46:25.702 I/CSST    ( 6608): reading enabled notification pref network: true
08-19 22:46:25.703 I/CSST    ( 6608): reading time to delay notification emergency: -1
08-19 22:46:25.703 D/RILJ    ( 6608): [0109]< GSM_SET_BROADCAST_CONFIG  [PHONE0]
08-19 22:46:25.703 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:25.703 D/RILJ    ( 6608): [0110]< OPERATOR {, , 43220} [PHONE0]
08-19 22:46:25.703 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 0 networkType = 316295
08-19 22:46:25.705 D/RILJ    ( 6608): [0114]> GSM_BROADCAST_ACTIVATION activate = true [PHONE0]
08-19 22:46:25.705 D/Phone-0 ( 6608): [0] Allowed network types for 'carrier' reason is changed by carrier config = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:25.705 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:25.706 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:25.706 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,true,false,-1,false,true
08-19 22:46:25.706 E/RILD    ( 6018): DoGsmSetCBActivation: CBEnable: 1
08-19 22:46:25.706 E/RILD    ( 6018): DoGsmSetCBActivation: enableCb: 1
08-19 22:46:25.707 D/RILJ    ( 6608): [0114]< GSM_BROADCAST_ACTIVATION  [PHONE0]
08-19 22:46:25.707 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:25.708 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:25.708 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:25.708 D/Phone-0 ( 6608): isWifiCallingEnabled =false
08-19 22:46:25.708 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:25.708 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:25.709 D/DCM-0   ( 6608): EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.709 D/RILJ    ( 6608): [0115]> CDMA_SET_BROADCAST_CONFIG with 2 configs :  [PHONE0]
08-19 22:46:25.710 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4096, 4099] ENABLED [PHONE0]
08-19 22:46:25.710 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4100, 4100] DISABLED [PHONE0]
08-19 22:46:25.711 D/RILJ    ( 6608): [0115]< CDMA_SET_BROADCAST_CONFIG error 6 [PHONE0]
08-19 22:46:25.712 D/RilRequest( 6608): [0115]< CDMA_SET_BROADCAST_CONFIG error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result={ when=-35s643ms what=2 obj=Request[mCbRangesRequest3gpp = [CellBroadcastIdRange[4352, 4354, 1, true], CellBroadcastIdRange[4355, 4355, 1, false], CellBroadcastIdRange[4356, 4356, 1, true], CellBroadcastIdRange[4370, 4379, 1, true], CellBroadcastIdRange[4380, 4382, 1, false], CellBroadcastIdRange[4383, 4392, 1, true], CellBroadcastIdRange[4393, 4395, 1, false]], mCbRangesRequest3gpp2 = [CellBroadcastIdRange[4096, 4099, 2, true], CellBroadcastIdRange[4100, 4100, 2, false]]] target=com.android.internal.telephony.StateMachine$SmHandler }
08-19 22:46:25.712 D/RILJ    ( 6608): Unsol response received; Sending ack to ril.cpp [PHONE0]
08-19 22:46:25.713 D/RILJ    ( 6608): [UNSL]< UNSOL_CELL_INFO_LIST [CellInfoWcdma:{mRegistered=YES mTimeStamp=35644651051ns mCellConnectionStatus=0 CellIdentityWcdma:{ mLac=17570 mCid=0 mPsc=21 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong=43220 mAlphaShort=43220 mAdditionalPlmns={} mCsgInfo=null} CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-24 ecno=0 level=0}] [PHONE0]
08-19 22:46:25.714 D/CellularNetworkService( 6608): No access tech specific info passes for RegStateResult
08-19 22:46:25.715 D/NRM-C-0 ( 6608): onRequestNetworkRegistrationInfoComplete result: 0, info: NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.715 D/RILJ    ( 6608): [0111]< DATA_REGISTRATION_STATE RegStateResult{regState: NOT_REG_MT_NOT_SEARCHING_OP, rat: UNKNOWN, reasonForDenial: NONE, cellIdentity: CellIdentity.wcdma(CellIdentityWcdma{mcc: 432, mnc: 20, lac: 17570, cid: 43338759, psc: 0, uarfcn: -1, operatorNames: OperatorInfo{alphaLong: , alphaShort: , operatorNumeric: , status: 0}, additionalPlmns: [], csgInfo: null}), registeredPlmn: 43220, accessTechnologySpecificInfo: AccessTechnologySpecificInfo.noinit(false)} [PHONE0]
08-19 22:46:25.715 D/DCM-0   ( 6608): Carrier config updated. Config is not carrier specific.
08-19 22:46:25.716 D/RILJ    ( 6608): [0112]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE0]
08-19 22:46:25.717 D/DIC-0   ( 6608): Carrier configs updated: PersistableBundle[{carrier_config_applied_bool=false, show_roaming_indicator_bool=true, carrier_config_version_string=}]
08-19 22:46:25.718 D/NRM-I-0 ( 6608): Carrier config changed. Try to bind network service.
08-19 22:46:25.718 I/AnomalyReporter( 6608): reportAnomaly: Received anomaly event report with eventId= 62ed270f-e139-418a-a427-8bcc1bca8f21 and description= RIL Missing Reg Fail Reason
08-19 22:46:25.718 D/RILJ    ( 6608): [0113]< VOICE_REGISTRATION_STATE RegStateResult{regState: REG_DENIED_EM, rat: UMTS, reasonForDenial: NONE, cellIdentity: CellIdentity.wcdma(CellIdentityWcdma{mcc: 432, mnc: 20, lac: 17570, cid: 43338759, psc: 0, uarfcn: 2938, operatorNames: OperatorInfo{alphaLong: , alphaShort: , operatorNumeric: , status: 0}, additionalPlmns: [], csgInfo: null}), registeredPlmn: 43220, accessTechnologySpecificInfo: AccessTechnologySpecificInfo.noinit(false)} [PHONE0]
08-19 22:46:25.719 D/CellularNetworkService( 6608): No access tech specific info passes for RegStateResult
08-19 22:46:25.719 E/NRM-I-0 ( 6608): Can't find the binding package
08-19 22:46:25.719 D/NRM-C-0 ( 6608): onRequestNetworkRegistrationInfoComplete result: 0, info: NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.719 D/DSM-I-0 ( 6608): Carrier config changed. Try to bind data service.
08-19 22:46:25.725 E/DSM-I-0 ( 6608): Can't find the binding package
08-19 22:46:25.726 D/DSM-C-0 ( 6608): Carrier config changed. Try to bind data service.
08-19 22:46:25.727 D/DSM-C-0 ( 6608): Service com.android.phone already bound or being bound.
08-19 22:46:25.729 D/ImsPhoneCallTracker( 6608): [0] onReceive: caching carrier config until ImsService connects for subId: -1
08-19 22:46:25.729 D/ImsPhoneCallTracker( 6608): [1] onReceive: Skipping indication for other phoneId: 0
08-19 22:46:25.729 D/NetworkTypeController( 6608): [0] LegacyState: process EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.729 D/NetworkTypeController( 6608): [0] Reset timers since NR is not allowed.
08-19 22:46:25.729 D/NetworkTypeController( 6608): [0] DefaultState: process EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.730 D/NetworkTypeController( 6608): [0] mOverrideTimerRules: {connected={mState=connected, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_con={mState=not_restricted_rrc_con, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, legacy={mState=legacy, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_idle={mState=not_restricted_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, restricted={mState=restricted, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, connected_mmwave={mState=connected_mmwave, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, connected_rrc_idle={mState=connected_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}}
08-19 22:46:25.730 D/NetworkTypeController( 6608): [0] Physical channel configs updated: anchorNrCell=-1, nrBandwidths=0, nrBands=[], configs=null
08-19 22:46:25.730 D/NetworkTypeController( 6608): [0] Reset timers since carrier configurations changed.
08-19 22:46:25.732 D/GsmCdmaPhone( 6608): mBroadcastReceiver: action android.telephony.action.CARRIER_CONFIG_CHANGED
08-19 22:46:25.732 D/GsmCdmaPhone( 6608): mBroadcastReceiver: action android.telephony.action.CARRIER_CONFIG_CHANGED
08-19 22:46:25.732 E/ImsStateCallbackController( 6608): onReceive ACTION_CARRIER_CONFIG_CHANGED invalid subId
08-19 22:46:25.738 D/SatelliteController( 6608): handleCarrierConfigChanged(): slotIndex(1), subId(-1), carrierId(-1), specificCarrierId(-1)
08-19 22:46:25.738 D/SatelliteEntitlementController( 6608): handleCarrierConfigChanged(): slotIndex(1), subId(-1), carrierId(-1), specificCarrierId(-1)
08-19 22:46:25.738 D/SatelliteEntitlementController( 6608): processSimChanged prev subId:-1
08-19 22:46:25.753 D/SST     ( 6608): [0] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.753 E/SST     ( 6608): [0] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.755 D/SST     ( 6608): [0] handlePollStateResultMessage: PS cellular. NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.755 D/DPM-0   ( 6608): Update data profiles due to carrier config updated.
08-19 22:46:25.780 D/RILJ    ( 6608): [0117]> CDMA_SET_BROADCAST_CONFIG with 2 configs :  [PHONE0]
08-19 22:46:25.780 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4096, 4099] ENABLED [PHONE0]
08-19 22:46:25.780 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4100, 4100] DISABLED [PHONE0]
08-19 22:46:25.780 D/DPM-0   ( 6608): Added default EIMS data profile.
08-19 22:46:25.781 D/DPM-0   ( 6608): Found 1 data profiles. profiles = [[DataProfile=[ApnSetting] DEFAULT EIMS, 0, null, sos, null, null, null, null, null, 0, emergency, IPV4V6, IPV4V6, true, 0, false, 0, 0, 0, 0, 0, null, null, false, UNKNOWN, UNKNOWN, -1, -1, -1, false, 3, 961, false, UNEDITED, TrafficDescriptor={mDnn=sos, null}, preferred=false]]
08-19 22:46:25.781 D/RILJ    ( 6608): [0117]< CDMA_SET_BROADCAST_CONFIG error 6 [PHONE0]
08-19 22:46:25.781 D/DPM-0   ( 6608): Data profiles changed.
08-19 22:46:25.781 D/RilRequest( 6608): [0117]< CDMA_SET_BROADCAST_CONFIG error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result={ when=-35s713ms what=2 obj=Request[mCbRangesRequest3gpp = [CellBroadcastIdRange[4352, 4354, 1, true], CellBroadcastIdRange[4355, 4355, 1, false], CellBroadcastIdRange[4356, 4356, 1, true], CellBroadcastIdRange[4370, 4379, 1, true], CellBroadcastIdRange[4380, 4382, 1, false], CellBroadcastIdRange[4383, 4392, 1, true], CellBroadcastIdRange[4393, 4395, 1, false]], mCbRangesRequest3gpp2 = [CellBroadcastIdRange[4096, 4099, 2, true], CellBroadcastIdRange[4100, 4100, 2, false]]] target=com.android.internal.telephony.StateMachine$SmHandler }
08-19 22:46:25.784 D/DPM-0   ( 6608): getPreferredDataProfileSetId: cursor is null
08-19 22:46:25.785 D/DPM-0   ( 6608): updateDataProfilesAtModem: set 1 data profiles.
08-19 22:46:25.785 D/DSM-C-0 ( 6608): setDataProfile
08-19 22:46:25.786 D/DPM-0   ( 6608): Initial attach data profile updated as null or forceUpdateIa= true
08-19 22:46:25.786 D/DNC-0   ( 6608): onCarrierConfigUpdated: config is not carrier specific. mSimState=ABSENT
08-19 22:46:25.787 D/RILJ    ( 6608): [0118]> SET_DATA_PROFILE with data profiles :  [PHONE0]
08-19 22:46:25.787 D/DNC-0   ( 6608): Re-evaluating 0 unsatisfied network requests in 0 groups,  due to DATA_CONFIG_CHANGED
08-19 22:46:25.787 D/DRM-0   ( 6608): Remove all retry and throttling entries, reason=DATA_CONFIG_CHANGED
08-19 22:46:25.788 D/RILJ    ( 6608): [DataProfile=[ApnSetting] DEFAULT EIMS, 0, null, sos, null, null, null, null, null, 0, emergency, IPV4V6, IPV4V6, true, 0, false, 0, 0, 0, 0, 0, null, null, false, UNKNOWN, UNKNOWN, -1, -1, -1, false, 3, 961, false, UNEDITED, TrafficDescriptor={mDnn=sos, null}, preferred=false] [PHONE0]
08-19 22:46:25.789 D/DRM-0   ( 6608): onDataConfigUpdated: mDataSetupRetryRuleList=[[DataSetupRetryRule: Network capabilities:[EIMS], Fail causes={}, Retry intervals=[1000], Maximum retries=20], [DataSetupRetryRule: Network capabilities:[], Fail causes=[32, 65537, 33, -3, 35, 65538, -5, -6, 65543, 8, 65547, 2252, 2253, 2254, 111, 50, 51, 27, 28, 29, 30], Retry intervals=[2500], Maximum retries=10], [DataSetupRetryRule: Network capabilities:[MMS|SUPL|CBS|RCS], Fail causes={}, Retry intervals=[2000], Maximum retries=10], [DataSetupRetryRule: Network capabilities:[DUN|PRIORITIZE_LATENCY|FOTA|PRIORITIZE_BANDWIDTH|IMS|MCX|XCAP|INTERNET|ENTERPRISE], Fail causes={}, Retry intervals=[2500, 3000, 5000, 10000, 15000, 20000, 40000, 60000, 120000, 240000, 600000, 1200000, 1800000], Maximum retries=20]], mDataHandoverRetryRuleList=[[DataHandoverRetryRule: Retry intervals=[1000, 2000, 4000, 8000, 16000], Fail causes={}, Maximum retries=5]]
08-19 22:46:25.789 D/DSRM-0  ( 6608): Enabled actions is null
08-19 22:46:25.789 D/DSRM-0  ( 6608): Duration millis is null
08-19 22:46:25.789 D/SST     ( 6608): [0] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:25.790 D/SST     ( 6608): [0] handlePollStateResultMessage: CS cellular. NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.790 D/SST     ( 6608): [0] combinePsRegistrationStates: {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2938, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.790 E/RILD    ( 6018): NeedChnNullApn(): apn is null
08-19 22:46:25.791 E/RILD    ( 6018): SetSimOperator: invalid operator
08-19 22:46:25.791 E/RILD    ( 6018): LoadSimOperator(): Failed to set IMSI from [gsm.sim.operator.numeric] RilIndex=0
08-19 22:46:25.791 E/RILD    ( 6018): LoadSimOperatorFromImsi(): Failed, GetImsi is empty
08-19 22:46:25.791 E/RILD    ( 6018): GetSimOperator(): Error, mSimOperator = , mSimOperatorFromImsi = 
08-19 22:46:25.791 E/RILD    ( 6018): IsEsmFlagZeroNetwork(): invalid sim operator
08-19 22:46:25.791 D/RILJ    ( 6608): [0118]< SET_DATA_PROFILE  [PHONE0]
08-19 22:46:25.791 D/DSM-C-0 ( 6608): onSetDataProfileComplete. resultCode = 0
08-19 22:46:25.792 D/SatelliteController( 6608): Satellite for carrier is not supported.
08-19 22:46:25.793 D/SatelliteController( 6608): Satellite for carrier is not supported.
08-19 22:46:25.793 D/SST     ( 6608): [0] Poll ServiceState done: oldSS={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.794 D/SST     ( 6608): [0] Poll ServiceState done: newSS={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.794 D/SST     ( 6608): [0] Poll ServiceState done: oldMaxDataCalls=1 mNewMaxDataCalls=16 oldReasonDataDenied=-1 mNewReasonDataDenied=0
08-19 22:46:25.794 D/SST     ( 6608): [0] pollStateDone: hasRegistered = false hasDeregistered = false hasDataAttached = {1=false, 2=false} hasDataDetached = {1=false, 2=false} hasDataRegStateChanged = {1=true, 2=false} hasRilVoiceRadioTechnologyChanged = true hasRilDataRadioTechnologyChanged = {1=false, 2=false} hasDataTransportPreferenceChanged = false hasChanged = true hasVoiceRoamingOn = false hasVoiceRoamingOff = false hasDataRoamingOn =false hasDataRoamingOff = false hasLocationChanged = true has4gHandoff = false hasMultiApnSupport = false hasLostMultiApnSupport = false hasCssIndicatorChanged = false hasNrFrequencyRangeChanged = false hasNrStateChanged = false hasAirplaneModeOnlChanged = false
08-19 22:46:25.794 D/SST     ( 6608): [0] RAT switched Unknown -> UMTS at cell 43338759
08-19 22:46:25.795 D/SST     ( 6608): [0] updatePhoneObject: Ignore update
08-19 22:46:25.795 D/SST     ( 6608): [0] updateSpnDisplayLegacy+
08-19 22:46:25.796 D/SST     ( 6608): [0] updateSpnDisplay: radio is on but out of service, set plmn='Emergency calls only'
08-19 22:46:25.796 D/SST     ( 6608): [0] updateSpnDisplay: rawSpn = 
08-19 22:46:25.796 D/SST     ( 6608): [0] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='Emergency calls only', showSpn='false', spn='', dataSpn='', subId='-1'
08-19 22:46:25.798 D/SST     ( 6608): [0] updateSpnDisplayLegacy-
08-19 22:46:25.801 D/SST     ( 6608): [0] Broadcasting ServiceState : {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.802 D/SatelliteController( 6608): handleStateChangedForCarrierRoamingNtnEligibility: carrierRoamingNbIotNtn flag is disabled
08-19 22:46:25.802 D/DefaultPhoneNotifier( 6608): notifyServiceStateForSubId: mRegistryMgr=android.telephony.TelephonyRegistryManager@f7f132 ss={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} sender=Handler (com.android.internal.telephony.GsmCdmaPhone) {1048021} phondId=0 subId=-1
08-19 22:46:25.802 D/SatelliteController( 6608): determineAutoConnectSystemNotification: isNtn.first = false IsNotiToShow = true mIsNotificationShowing = false
08-19 22:46:25.803 D/TelephonyRegistry( 6138): notifyServiceStateForSubscriber: INVALID subId=-1
08-19 22:46:25.818 W/ImsStats( 6608): [0] conclude: discarding transient stats, duration=796
08-19 22:46:25.823 D/RILJ    ( 6608): [0119]> SIGNAL_STRENGTH [PHONE0]
08-19 22:46:25.824 D/SST     ( 6608): [0] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=3
08-19 22:46:25.825 D/RILJ    ( 6608): [0119]< SIGNAL_STRENGTH SignalStrength:{mCdma=CellSignalStrengthCdma: cdmaDbm=2147483647 cdmaEcio=2147483647 evdoDbm=2147483647 evdoEcio=2147483647 evdoSnr=2147483647 level=0,mGsm=CellSignalStrengthGsm: rssi=2147483647 ber=2147483647 mTa=2147483647 mLevel=0,mWcdma=CellSignalStrengthWcdma: ss=-113 ber=99 rscp=-120 ecno=0 level=0,mTdscdma=CellSignalStrengthTdscdma: rssi=2147483647 ber=2147483647 rscp=2147483647 level=0,mLte=CellSignalStrengthLte: rssi=2147483647 rsrp=2147483647 rsrq=2147483647 rssnr=2147483647 cqiTableIndex=2147483647 cqi=2147483647 ta=2147483647 level=0 parametersUseForLevel=1,mNr=CellSignalStrengthNr:{ csiRsrp = 2147483647 csiRsrq = 2147483647 csiCqiTableIndex = 2147483647 csiCqiReport = [] ssRsrp = 2147483647 ssRsrq = 2147483647 ssSinr = 2147483647 level = 0 parametersUseForLevel = 1 timingAdvance = 2147483647 },primary=CellSignalStrengthWcdma} [PHONE0]
08-19 22:46:25.825 D/TelephonyRegistry( 6138): notifyCellLocationForSubscriber: subId=-1 cellIdentity=[uzJvDilx9oEomaa2Q2ZPbhYW1NY]
08-19 22:46:25.827 D/GsmCdmaPhone( 6608): [0] broadcastEmergencyCallStateChanges = false
08-19 22:46:25.831 D/RILJ    ( 6608): [0120]> GET_RADIO_CAPABILITY [PHONE0]
08-19 22:46:25.832 D/RILJ    ( 6608): convertHalRadioCapability: session=0, phase=4, rat=130047, logicModemUuid=, status=1, rcRil.raf=262142 [PHONE0]
08-19 22:46:25.832 D/RILJ    ( 6608): [0120]< GET_RADIO_CAPABILITY {mPhoneId = 0 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1} [PHONE0]
08-19 22:46:25.837 D/RILJ    ( 6608): [0121]> CDMA_SET_BROADCAST_CONFIG with 2 configs :  [PHONE0]
08-19 22:46:25.837 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4096, 4099] ENABLED [PHONE0]
08-19 22:46:25.837 D/RILJ    ( 6608): CdmaSmsBroadcastConfigInfo: Id [4100, 4100] DISABLED [PHONE0]
08-19 22:46:25.837 D/CarrierSignalAgent( 6608): [1]Loading carrier config: carrier_app_wake_signal_config
08-19 22:46:25.838 D/CarrierSignalAgent( 6608): [1]Loading carrier config: carrier_app_no_wake_signal_config
08-19 22:46:25.838 D/RILJ    ( 6608): [0121]< CDMA_SET_BROADCAST_CONFIG error 6 [PHONE0]
08-19 22:46:25.838 D/RilRequest( 6608): [0121]< CDMA_SET_BROADCAST_CONFIG error: com.android.internal.telephony.CommandException: REQUEST_NOT_SUPPORTED ret= result={ when=-35s770ms what=2 obj=Request[mCbRangesRequest3gpp = [CellBroadcastIdRange[4352, 4354, 1, true], CellBroadcastIdRange[4355, 4355, 1, false], CellBroadcastIdRange[4356, 4356, 1, true], CellBroadcastIdRange[4370, 4379, 1, true], CellBroadcastIdRange[4380, 4382, 1, false], CellBroadcastIdRange[4383, 4392, 1, true], CellBroadcastIdRange[4393, 4395, 1, false]], mCbRangesRequest3gpp2 = [CellBroadcastIdRange[4096, 4099, 2, true], CellBroadcastIdRange[4100, 4100, 2, false]]] target=com.android.internal.telephony.StateMachine$SmHandler }
08-19 22:46:25.840 E/ANM-1   ( 6608): Can't find the binding package
08-19 22:46:25.841 E/SSCtr   ( 6608): Invalid parameters for NR RSRP boost
08-19 22:46:25.844 D/RILJ    ( 6608): [0122]> SET_SIGNAL_STRENGTH_REPORTING_CRITERIA [PHONE1]
08-19 22:46:25.844 D/SSCtr   ( 6608): setSignalStrengthReportingCriteria consolidatedSignalThresholdInfos=[SignalThresholdInfo{mRan=1 mSignalMeasurementType=1 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-107, -103, -97, -89] mIsEnabled=true}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=2 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-115, -105, -95, -85] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=3 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-128, -118, -108, -98] mIsEnabled=true}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=4 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=3 mSignalMeasurementType=5 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=6 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[-110, -90, -80, -65] mIsEnabled=true}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=7 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=6 mSignalMeasurementType=8 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}, SignalThresholdInfo{mRan=2 mSignalMeasurementType=9 mHysteresisMs=3000 mHysteresisDb=2 mThresholds=[] mIsEnabled=false}]
08-19 22:46:25.846 D/RILJ    ( 6608): [0122]< SET_SIGNAL_STRENGTH_REPORTING_CRITERIA  [PHONE1]
08-19 22:46:25.849 D/SST     ( 6608): [1] CarrierConfigChange PersistableBundle[{imsvoice.voice_on_default_bearer_supported_bool=false, imsvoice.rtp_inactivity_time_threshold_millis_long=5000, imsss.ut_transport_type_int=1, imsemergency.emergency_call_setup_timer_on_current_network_sec_int=0, carrier_volte_provisioned_bool=false, support_cdma_1x_voice_calls_bool=true, support_ss_over_cdma_bool=false, disable_charge_indication_bool=false, ims.sip_timer_t4_millis_int=17000, support_tdscdma_bool=false, httpSocketTimeout=60000, allowed_initial_attach_apn_types_string_array=[ia, default], disable_supplementary_services_in_airplane_mode_bool=false, call_barring_default_service_class_int=1, call_redirection_service_component_name_string=null, carrier_wfc_supports_wifi_only_bool=false, carrier_default_actions_on_default_network_available_string_array=[false: 7, true: 8], imsvoice.minimum_session_expires_timer_sec_int=90, vonr_on_by_default_bool=true, iwlan_handover_policy_string_array=[source=GERAN|UTRAN|EUTRAN|NGRAN|IWLAN, target=GERAN|UTRAN|EUTRAN|NGRAN|IWLAN, type=allowed], operator_selection_expand_bool=true, disable_cdma_activation_code_bool=false, simplified_network_settings_bool=false, imsemergency.emergency_registration_timer_millis_int=10000, call_forwarding_when_unanswered_supported_bool=true, imsvt.h264_payload_description_bundle=PersistableBundle[{99=PersistableBundle[{}], 100=PersistableBundle[{imsvt.video_codec_attribute_packetization_mode_int=0}]}], support_tdscdma_roaming_networks_string_array=null, opportunistic.5g_data_switch_hysteresis_time_long=2000, ims.sip_timer_d_millis_int=130000, gps.lpp_profile=2, call_barring_visibility_bool=false, gba_mode_int=1, ims.registration_subscribe_expiry_timer_sec_int=600000, gps.es_extension_sec=0, enable_apps_string_array=null, 5g_icon_display_secondary_grace_period_string=, carrier_default_wfc_ims_roaming_enabled_bool=false, cdma_nonroaming_networks_string_array=null, imsss.ut_as_server_fqdn_string=, imsemergency.emergency_lte_preferred_after_nr_failed_bool=false, signal_strength_nr_nsa_use_lte_as_primary_bool=true, 5g_ultra_wideband_icon_nsa_band_mode=2147483647, aliasMinChars=2, fdn_number_length_limit_int=20, support_ims_call_forwarding_while_roaming_bool=true, wfc_data_spn_format_idx_int=0, hide_sim_lock_settings_bool=false, premium_capability_network_setup_time_millis_long=300000, satellite_esos_supported_bool=false, drop_video_call_when_answering_audio_call_bool=false, data_stall_recovery_timers_long_array=[180000, 180000, 180000, 180000], satellite_connection_hysteresis_sec_int=180, opportunistic_esim_download_via_wifi_only_bool=false, imsss.xcap_over_ut_supported_rats_int_array=[3, 5, 6], ci_action_on_sys_update_bool=false, carrier_certificate_string_array=[], convert_cdma_caller_id_mmi_codes_while_roaming_on_3gpp_bool=false, support_enhanced_call_blocking_bool=true, iwlan.ike_rekey_hard_timer_in_sec=14400, vvm_port_number_int=0, premium_capability_notification_display_timeout_millis_long=1800000, wifi_connectivity_extend_cell_delay=-1, imsemergency.emergency_requires_ims_registration_bool=false, carrier_default_wfc_ims_enabled_bool=false, iwlan.ike_session_encryption_aes_ctr_key_size_int_array=[128, 192, 256], dial_string_replace_string_array=null, opportunistic_network_entry_threshold_bandwidth_int=1024, imsemergency.emergency_requires_volte_enabled_bool=false, opportunistic_network_data_switch_exit_hysteresis_time_long=3000, imsss.use_csfb_on_xcap_over_ut_failure_bool=true, gsm_nonroaming_networks_string_array=null, imsserviceentitlement.ims_provisioning_bool=false, wifi.avoid_5ghz_softap_for_laa_bool=false, hide_ims_apn_bool=false, carrier_network_service_wlan_class_override_string=, vvm_destination_number_string=, ims.ipsec_encryption_algorithms_int_array=[0, 1, 2], opportunistic.5g_backoff_time_long=10000, enable_cross_sim_calling_on_opportunistic_data_bool=false, vonr_setting_visibility_bool=true, imssms.sms_over_ims_supported_bool=true, dtmf_type_enabled_bool=false, ims.sip_timer_f_millis_int=128000, allow_video_calling_fallback_bool=true, nr_advanced_threshold
08-19 22:46:25.849 E/Phone-1 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.849 E/Phone-1 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.849 V/Phone-1 ( 6608): getCallForwardingIndicator: iccForwardingFlag=null, sharedPrefFlag=0
08-19 22:46:25.850 D/DefaultPhoneNotifier( 6608): notifyCallForwardingChanged: subId=-1, isCFActive=false
08-19 22:46:25.850 E/Phone-1 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.850 E/Phone-1 ( 6608): getCallForwardingIndicatorFromSharedPref: invalid subId -1
08-19 22:46:25.850 V/Phone-1 ( 6608): getCallForwardingIndicator: iccForwardingFlag=null, sharedPrefFlag=0
08-19 22:46:25.852 D/SST     ( 6608): [1] pollState: modemTriggered=false, radioState=1
08-19 22:46:25.854 D/RILJ    ( 6608): [0123]> OPERATOR [PHONE1]
08-19 22:46:25.854 E/NRM-I-1 ( 6608): service not connected. Domain = PS
08-19 22:46:25.856 D/RILJ    ( 6608): [0124]> DATA_REGISTRATION_STATE [PHONE1]
08-19 22:46:25.856 D/RILJ    ( 6608): getDataRegistrationState: overrideHalVersion=null [PHONE1]
08-19 22:46:25.856 E/RILD2   ( 6018): HalIoChannel::Write: mSehChannelImpl->mSehChannelCallback == null [imsd2]
08-19 22:46:25.856 E/RILD2   ( 6018): IO channel write error.
08-19 22:46:25.856 E/RILD2   ( 6018): Can't send SSAC info to IMS
08-19 22:46:25.857 D/RILJ    ( 6608): [0125]> QUERY_NETWORK_SELECTION_MODE [PHONE1]
08-19 22:46:25.857 D/RILJ    ( 6608): [0123]< OPERATOR {, , } [PHONE1]
08-19 22:46:25.857 D/NRM-C-1 ( 6608): Carrier config changed. Try to bind network service.
08-19 22:46:25.858 D/RILJ    ( 6608): [0126]> VOICE_REGISTRATION_STATE [PHONE1]
08-19 22:46:25.858 D/RILJ    ( 6608): getVoiceRegistrationState: overrideHalVersion=null [PHONE1]
08-19 22:46:25.858 D/NRM-C-1 ( 6608): Service com.android.phone already bound or being bound.
08-19 22:46:25.858 D/NRM-I-1 ( 6608): Carrier config changed. Try to bind network service.
08-19 22:46:25.859 E/NRM-I-1 ( 6608): Can't find the binding package
08-19 22:46:25.862 D/CSST    ( 6608): onCarrierConfigChanged: slotIndex=1, subId=-1, carrierId=-1
08-19 22:46:25.862 E/RILD2   ( 6018): UpdateReportRegState: reqId - 21, CellInfo NULL
08-19 22:46:25.862 I/CSST    ( 6608): reading time to delay notification pref network: -1
08-19 22:46:25.862 I/CSST    ( 6608): reading enabled notification pref network: true
08-19 22:46:25.862 I/CSST    ( 6608): reading time to delay notification emergency: -1
08-19 22:46:25.862 D/CellularNetworkService( 6608): No access tech specific info passes for RegStateResult
08-19 22:46:25.863 D/RILJ    ( 6608): [0124]< DATA_REGISTRATION_STATE RegStateResult{regState: NOT_REG_MT_NOT_SEARCHING_OP, rat: UNKNOWN, reasonForDenial: NONE, cellIdentity: CellIdentity.noinit(false), registeredPlmn: 000000, accessTechnologySpecificInfo: AccessTechnologySpecificInfo.noinit(false)} [PHONE1]
08-19 22:46:25.863 D/Phone-1 ( 6608): [1] SubId-1,get allowed network types user: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:25.863 D/NRM-C-1 ( 6608): onRequestNetworkRegistrationInfoComplete result: 0, info: NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.863 D/PhoneFactory( 6608): calculatePreferredNetworkType: phoneId = 1 networkType = 316295
08-19 22:46:25.864 D/RILJ    ( 6608): [0125]< QUERY_NETWORK_SELECTION_MODE {0} [PHONE1]
08-19 22:46:25.864 D/Phone-0 ( 6608): [0] SubId-1,get allowed network types carrier: value = GPRS|EDGE|UMTS|HSDPA|HSUPA|HSPA|LTE|HSPA+|GSM|LTE_CA
08-19 22:46:25.864 I/CSST    ( 6608): isNrSupported:  carrierConfigEnabled: true, AccessFamilySupported: false, isNrNetworkTypeAllowed: false
08-19 22:46:25.864 I/CSST    ( 6608): PrefNetworkNotification: sendMessage() w/values: ,true,false,-1,false,true
08-19 22:46:25.865 I/CSST    ( 6608): canceling notifications: 1000
08-19 22:46:25.865 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:25.865 D/CSST    ( 6608): isPhoneRegisteredForWifiCalling: false
08-19 22:46:25.865 D/Phone-1 ( 6608): isWifiCallingEnabled =false
08-19 22:46:25.865 I/CSST    ( 6608): EmergencyNetworkNotification: sendMessage() w/values: ,-1,false,true
08-19 22:46:25.866 I/CSST    ( 6608): canceling notifications: 1001
08-19 22:46:25.866 D/DSM-I-1 ( 6608): Carrier config changed. Try to bind data service.
08-19 22:46:25.869 E/DSM-I-1 ( 6608): Can't find the binding package
08-19 22:46:25.869 D/DSM-C-1 ( 6608): Carrier config changed. Try to bind data service.
08-19 22:46:25.869 D/DSM-C-1 ( 6608): Service com.android.phone already bound or being bound.
08-19 22:46:25.869 D/DCM-1   ( 6608): EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.871 E/RILD2   ( 6018): UpdateReportRegState: reqId - 20, CellInfo NULL
08-19 22:46:25.872 D/CellularNetworkService( 6608): No access tech specific info passes for RegStateResult
08-19 22:46:25.872 D/RILJ    ( 6608): [0126]< VOICE_REGISTRATION_STATE RegStateResult{regState: NOT_REG_MT_NOT_SEARCHING_OP, rat: UNKNOWN, reasonForDenial: NONE, cellIdentity: CellIdentity.noinit(false), registeredPlmn: 000000, accessTechnologySpecificInfo: AccessTechnologySpecificInfo.noinit(false)} [PHONE1]
08-19 22:46:25.872 D/NRM-C-1 ( 6608): onRequestNetworkRegistrationInfoComplete result: 0, info: NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.876 D/DCM-1   ( 6608): Carrier config updated. Config is not carrier specific.
08-19 22:46:25.880 D/NetworkTypeController( 6608): [1] LegacyState: process EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.880 D/NetworkTypeController( 6608): [1] Reset timers since NR is not allowed.
08-19 22:46:25.880 D/NetworkTypeController( 6608): [1] DefaultState: process EVENT_CARRIER_CONFIG_CHANGED
08-19 22:46:25.881 D/NetworkTypeController( 6608): [1] mOverrideTimerRules: {connected={mState=connected, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_con={mState=not_restricted_rrc_con, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, legacy={mState=legacy, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, not_restricted_rrc_idle={mState=not_restricted_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, restricted={mState=restricted, mOverrideType=NONE, mPrimaryTimers={}, mSecondaryTimers={}}, connected_mmwave={mState=connected_mmwave, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}, connected_rrc_idle={mState=connected_rrc_idle, mOverrideType=NR_NSA, mPrimaryTimers={}, mSecondaryTimers={}}}
08-19 22:46:25.881 D/NetworkTypeController( 6608): [1] Physical channel configs updated: anchorNrCell=-1, nrBandwidths=0, nrBands=[], configs=null
08-19 22:46:25.881 D/NetworkTypeController( 6608): [1] Reset timers since carrier configurations changed.
08-19 22:46:25.883 D/ImsPhoneCallTracker( 6608): [1] onReceive: caching carrier config until ImsService connects for subId: -1
08-19 22:46:25.884 D/DIC-1   ( 6608): Carrier configs updated: PersistableBundle[{carrier_config_applied_bool=false, show_roaming_indicator_bool=true, carrier_config_version_string=}]
08-19 22:46:25.884 D/ImsPhoneCallTracker( 6608): [0] onReceive: Skipping indication for other phoneId: 1
08-19 22:46:25.884 D/LocaleTracker-0( 6608): processCellInfo: cell info=[CellInfoWcdma:{mRegistered=YES mTimeStamp=35644651051ns mCellConnectionStatus=0 CellIdentityWcdma:{ mLac=17570 mCid=0 mPsc=21 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong=43220 mAlphaShort=43220 mAdditionalPlmns={} mCsgInfo=null} CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-24 ecno=0 level=0}]
08-19 22:46:25.885 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.885 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.885 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:25.885 D/GsmCdmaPhone( 6608): mBroadcastReceiver: action android.telephony.action.CARRIER_CONFIG_CHANGED
08-19 22:46:25.885 D/GsmCdmaPhone( 6608): mBroadcastReceiver: action android.telephony.action.CARRIER_CONFIG_CHANGED
08-19 22:46:25.885 E/ImsStateCallbackController( 6608): onReceive ACTION_CARRIER_CONFIG_CHANGED invalid subId
08-19 22:46:25.887 D/DRM-0   ( 6608): Remove all retry and throttling entries, reason=DATA_PROFILES_CHANGED
08-19 22:46:25.887 D/DIC-0   ( 6608): ServiceState updated, isRoaming=false
08-19 22:46:25.887 D/NetworkTypeController( 6608): [0] LegacyState: process EVENT_SERVICE_STATE_CHANGED
08-19 22:46:25.887 D/NetworkTypeController( 6608): [0] Reset timers since NR is not allowed.
08-19 22:46:25.888 D/NetworkTypeController( 6608): [0] ServiceState updated: {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.888 D/NetworkTypeController( 6608): [0] Reset timers since 2G and 3G don't need NR timers.
08-19 22:46:25.889 D/DNC-0   ( 6608): onServiceStateChanged: changed to {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.889 D/DNC-0   ( 6608): onServiceStateChanged: [WWAN: UNKNOWN->UNKNOWN, UNKNOWN->NOT_REG_OR_SEARCHING, TERRESTRIAL->TERRESTRIAL] [WLAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] . Evaluating network requests is not needed, evaluating existing data networks is not needed.
08-19 22:46:25.889 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.889 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.890 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:25.890 D/LocaleTracker-0( 6608): Starting LocaleTracker
08-19 22:46:25.890 D/ImsPhone( 6608): [0] handleMessage what=83
08-19 22:46:25.891 D/ImsPhone( 6608): [0] handleMessage what=82
08-19 22:46:25.891 D/ImsPhone( 6608): [0] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.891 D/ImsPhone( 6608): [0] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=2147483647, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=3(UMTS), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=true, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=DENIED networkRegistrationState=DENIED roamingType=NOT_ROAMING accessNetworkTechnology=UMTS rejectCause=0 emergencyEnabled=true availableServices=[EMERGENCY] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570 mCid=43338759 mPsc=0 mUarfcn=2147483647 mMcc=432 mMnc=20 mAlphaLong= mAlphaShort= mAdditionalPlmns={} mCsgInfo=null} voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=43220 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=CellIdentityWcdma:{ mLac=17570
08-19 22:46:25.892 D/GsmCdmaPhone( 6608): [0] onVoiceRegStateOrRatChanged
08-19 22:46:25.892 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, current vrs=1, vrat=3
08-19 22:46:25.892 D/GsmCdmaPhone( 6608): [0] getCsCallRadioTech, result calcVrat=0
08-19 22:46:25.894 D/GsmCdmaPhone( 6608): EVENT_GET_RADIO_CAPABILITY: phone rc: {mPhoneId = 0 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1}
08-19 22:46:25.894 D/SST     ( 6608): [1] handlePollStateResult exception java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.894 E/SST     ( 6608): [1] handlePollStateResult: RIL returned an error where it must succeed: java.lang.IllegalStateException: Service not connected.
08-19 22:46:25.894 D/SST     ( 6608): [1] handlePollStateResultMessage: PS cellular. NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.895 D/SST     ( 6608): [1] EVENT_POLL_STATE_NETWORK_SELECTION_MODE
08-19 22:46:25.895 D/SST     ( 6608): [1] Could not set ServiceState channel number. CellIdentity null
08-19 22:46:25.895 D/SST     ( 6608): [1] handlePollStateResultMessage: CS cellular. NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}
08-19 22:46:25.895 D/SST     ( 6608): [1] combinePsRegistrationStates: {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.896 D/SatelliteController( 6608): Satellite for carrier is not supported.
08-19 22:46:25.897 D/SatelliteController( 6608): Satellite for carrier is not supported.
08-19 22:46:25.897 D/SST     ( 6608): [1] Could not set ServiceState channel number. CellIdentity null
08-19 22:46:25.897 D/SST     ( 6608): [1] Poll ServiceState done: oldSS={mVoiceRegState=3(POWER_OFF), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.897 D/SST     ( 6608): [1] Poll ServiceState done: newSS={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.897 D/SST     ( 6608): [1] Poll ServiceState done: oldMaxDataCalls=1 mNewMaxDataCalls=16 oldReasonDataDenied=-1 mNewReasonDataDenied=0
08-19 22:46:25.898 D/SST     ( 6608): [1] pollStateDone: hasRegistered = false hasDeregistered = false hasDataAttached = {1=false, 2=false} hasDataDetached = {1=false, 2=false} hasDataRegStateChanged = {1=true, 2=false} hasRilVoiceRadioTechnologyChanged = false hasRilDataRadioTechnologyChanged = {1=false, 2=false} hasDataTransportPreferenceChanged = false hasChanged = true hasVoiceRoamingOn = false hasVoiceRoamingOff = false hasDataRoamingOn =false hasDataRoamingOff = false hasLocationChanged = false has4gHandoff = false hasMultiApnSupport = false hasLostMultiApnSupport = false hasCssIndicatorChanged = false hasNrFrequencyRangeChanged = false hasNrStateChanged = false hasAirplaneModeOnlChanged = false
08-19 22:46:25.898 D/SST     ( 6608): [1] updateSpnDisplayLegacy+
08-19 22:46:25.898 D/SST     ( 6608): [1] updateSpnDisplay: radio is on but out of service, set plmn='Emergency calls only'
08-19 22:46:25.898 D/SST     ( 6608): [1] updateSpnDisplay: rawSpn = 
08-19 22:46:25.899 D/SST     ( 6608): [1] updateSpnDisplay: updateSpnDisplay: changed sending intent, rule=2, showPlmn='true', plmn='Emergency calls only', showSpn='false', spn='', dataSpn='', subId='-1'
08-19 22:46:25.900 D/SST     ( 6608): [1] updateSpnDisplayLegacy-
08-19 22:46:25.902 D/SST     ( 6608): [1] localeOperator  is invalid
08-19 22:46:25.903 D/SST     ( 6608): [1] Broadcasting ServiceState : {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.904 D/SatelliteController( 6608): handleStateChangedForCarrierRoamingNtnEligibility: carrierRoamingNbIotNtn flag is disabled
08-19 22:46:25.904 D/DefaultPhoneNotifier( 6608): notifyServiceStateForSubId: mRegistryMgr=android.telephony.TelephonyRegistryManager@f7f132 ss={mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} sender=Handler (com.android.internal.telephony.GsmCdmaPhone) {bc6f7a7} phondId=1 subId=-1
08-19 22:46:25.904 D/SatelliteController( 6608): determineAutoConnectSystemNotification: isNtn.first = false IsNotiToShow = true mIsNotificationShowing = false
08-19 22:46:25.905 D/TelephonyRegistry( 6138): notifyServiceStateForSubscriber: INVALID subId=-1
08-19 22:46:25.916 W/ImsStats( 6608): [1] conclude: discarding transient stats, duration=854
08-19 22:46:25.920 D/RILJ    ( 6608): [0127]> SIGNAL_STRENGTH [PHONE1]
08-19 22:46:25.920 D/SST     ( 6608): [1] notifyVoiceRegStateRilRadioTechnologyChanged: vrs=1 rat=0
08-19 22:46:25.920 D/DSRM-1  ( 6608): Enabled actions is null
08-19 22:46:25.920 D/DSRM-1  ( 6608): Duration millis is null
08-19 22:46:25.921 D/DNC-1   ( 6608): onCarrierConfigUpdated: config is not carrier specific. mSimState=ABSENT
08-19 22:46:25.921 D/DNC-1   ( 6608): Re-evaluating 0 unsatisfied network requests in 0 groups,  due to DATA_CONFIG_CHANGED
08-19 22:46:25.921 D/DPM-1   ( 6608): Update data profiles due to carrier config updated.
08-19 22:46:25.921 D/RILJ    ( 6608): [0127]< SIGNAL_STRENGTH SignalStrength:{mCdma=CellSignalStrengthCdma: cdmaDbm=2147483647 cdmaEcio=2147483647 evdoDbm=2147483647 evdoEcio=2147483647 evdoSnr=2147483647 level=0,mGsm=CellSignalStrengthGsm: rssi=2147483647 ber=2147483647 mTa=2147483647 mLevel=0,mWcdma=CellSignalStrengthWcdma: ss=2147483647 ber=2147483647 rscp=2147483647 ecno=2147483647 level=0,mTdscdma=CellSignalStrengthTdscdma: rssi=2147483647 ber=2147483647 rscp=2147483647 level=0,mLte=CellSignalStrengthLte: rssi=2147483647 rsrp=2147483647 rsrq=2147483647 rssnr=2147483647 cqiTableIndex=2147483647 cqi=2147483647 ta=2147483647 level=0 parametersUseForLevel=1,mNr=CellSignalStrengthNr:{ csiRsrp = 2147483647 csiRsrq = 2147483647 csiCqiTableIndex = 2147483647 csiCqiReport = [] ssRsrp = 2147483647 ssRsrq = 2147483647 ssSinr = 2147483647 level = 0 parametersUseForLevel = 1 timingAdvance = 2147483647 },primary=CellSignalStrengthLte} [PHONE1]
08-19 22:46:25.926 D/DPM-1   ( 6608): Added default EIMS data profile.
08-19 22:46:25.927 D/DPM-1   ( 6608): Found 1 data profiles. profiles = [[DataProfile=[ApnSetting] DEFAULT EIMS, 0, null, sos, null, null, null, null, null, 0, emergency, IPV4V6, IPV4V6, true, 0, false, 0, 0, 0, 0, 0, null, null, false, UNKNOWN, UNKNOWN, -1, -1, -1, false, 3, 961, false, UNEDITED, TrafficDescriptor={mDnn=sos, null}, preferred=false]]
08-19 22:46:25.927 D/DPM-1   ( 6608): Data profiles changed.
08-19 22:46:25.927 D/DPM-1   ( 6608): getPreferredDataProfileSetId: cursor is null
08-19 22:46:25.927 D/DPM-1   ( 6608): updateDataProfilesAtModem: set 1 data profiles.
08-19 22:46:25.927 D/DSM-C-1 ( 6608): setDataProfile
08-19 22:46:25.928 D/DPM-1   ( 6608): Initial attach data profile updated as null or forceUpdateIa= true
08-19 22:46:25.928 D/DRM-1   ( 6608): Remove all retry and throttling entries, reason=DATA_CONFIG_CHANGED
08-19 22:46:25.929 D/DRM-1   ( 6608): onDataConfigUpdated: mDataSetupRetryRuleList=[[DataSetupRetryRule: Network capabilities:[EIMS], Fail causes={}, Retry intervals=[1000], Maximum retries=20], [DataSetupRetryRule: Network capabilities:[], Fail causes=[32, 65537, 33, -3, 35, 65538, -5, -6, 65543, 8, 65547, 2252, 2253, 2254, 111, 50, 51, 27, 28, 29, 30], Retry intervals=[2500], Maximum retries=10], [DataSetupRetryRule: Network capabilities:[MMS|SUPL|CBS|RCS], Fail causes={}, Retry intervals=[2000], Maximum retries=10], [DataSetupRetryRule: Network capabilities:[DUN|PRIORITIZE_LATENCY|FOTA|PRIORITIZE_BANDWIDTH|IMS|MCX|XCAP|INTERNET|ENTERPRISE], Fail causes={}, Retry intervals=[2500, 3000, 5000, 10000, 15000, 20000, 40000, 60000, 120000, 240000, 600000, 1200000, 1800000], Maximum retries=20]], mDataHandoverRetryRuleList=[[DataHandoverRetryRule: Retry intervals=[1000, 2000, 4000, 8000, 16000], Fail causes={}, Maximum retries=5]]
08-19 22:46:25.929 D/GsmCdmaPhone( 6608): [1] broadcastEmergencyCallStateChanges = false
08-19 22:46:25.929 D/RILJ    ( 6608): [0128]> SET_DATA_PROFILE with data profiles :  [PHONE1]
08-19 22:46:25.930 D/RILJ    ( 6608): [DataProfile=[ApnSetting] DEFAULT EIMS, 0, null, sos, null, null, null, null, null, 0, emergency, IPV4V6, IPV4V6, true, 0, false, 0, 0, 0, 0, 0, null, null, false, UNKNOWN, UNKNOWN, -1, -1, -1, false, 3, 961, false, UNEDITED, TrafficDescriptor={mDnn=sos, null}, preferred=false] [PHONE1]
08-19 22:46:25.930 E/RILD2   ( 6018): NeedChnNullApn(): apn is null
08-19 22:46:25.931 E/RILD2   ( 6018): SetSimOperator: invalid operator
08-19 22:46:25.931 E/RILD2   ( 6018): LoadSimOperator(): Failed to set IMSI from [gsm.sim.operator.numeric] RilIndex=1
08-19 22:46:25.931 E/RILD2   ( 6018): LoadSimOperatorFromImsi(): Failed, GetImsi is empty
08-19 22:46:25.931 E/RILD2   ( 6018): GetSimOperator(): Error, mSimOperator = , mSimOperatorFromImsi = 
08-19 22:46:25.931 E/RILD2   ( 6018): IsEsmFlagZeroNetwork(): invalid sim operator
08-19 22:46:25.931 D/RILJ    ( 6608): [0129]> GET_RADIO_CAPABILITY [PHONE1]
08-19 22:46:25.931 D/RILJ    ( 6608): [0128]< SET_DATA_PROFILE  [PHONE1]
08-19 22:46:25.931 D/DNC-0   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.931 D/DNC-0   ( 6608): Re-evaluating 0 unsatisfied network requests in 0 groups,  due to DATA_PROFILES_CHANGED
08-19 22:46:25.931 D/DSM-C-1 ( 6608): onSetDataProfileComplete. resultCode = 0
08-19 22:46:25.931 D/RILJ    ( 6608): convertHalRadioCapability: session=0, phase=4, rat=130047, logicModemUuid=, status=1, rcRil.raf=262142 [PHONE1]
08-19 22:46:25.931 D/RILJ    ( 6608): [0129]< GET_RADIO_CAPABILITY {mPhoneId = 1 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1} [PHONE1]
08-19 22:46:25.933 D/RILJ    ( 6608): [0130]> GET_CELL_INFO_LIST [PHONE0]
08-19 22:46:25.934 D/DIC-1   ( 6608): ServiceState updated, isRoaming=false
08-19 22:46:25.935 D/NetworkTypeController( 6608): [1] LegacyState: process EVENT_SERVICE_STATE_CHANGED
08-19 22:46:25.935 D/NetworkTypeController( 6608): [1] Reset timers since NR is not allowed.
08-19 22:46:25.935 D/NetworkTypeController( 6608): [1] ServiceState updated: {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.935 D/NetworkTypeController( 6608): [1] Reset timers since 2G and 3G don't need NR timers.
08-19 22:46:25.935 D/DNC-1   ( 6608): onServiceStateChanged: changed to {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false}
08-19 22:46:25.935 D/DNC-1   ( 6608): onServiceStateChanged: [WWAN: UNKNOWN->UNKNOWN, UNKNOWN->NOT_REG_OR_SEARCHING, TERRESTRIAL->TERRESTRIAL] [WLAN: UNKNOWN->UNKNOWN, UNKNOWN->UNKNOWN, TERRESTRIAL->TERRESTRIAL] . Evaluating network requests is not needed, evaluating existing data networks is not needed.
08-19 22:46:25.935 D/LocaleTracker-1( 6608): updateLocale: countryIso = , countryIsoDebugInfo = empty as default
08-19 22:46:25.935 D/LocaleTracker-1( 6608): updateLocale: timeZoneCountryIso = , timeZoneCountryIsoDebugInfo = empty as default
08-19 22:46:25.935 D/NitzStateMachineImpl( 6608): handleCountryUnavailable: mLatestNitzSignal=null
08-19 22:46:25.936 D/NitzStateMachineImpl( 6608): doTimeZoneDetection: countryIsoCode=null, nitzSignal=null, suggestion=TelephonyTimeZoneSuggestion{mSlotIndex=1, mZoneId='null', mMatchType=0, mQuality=0, mDebugInfo=[getTimeZoneSuggestion: nitzSignal=null, countryIsoCode=null, Detection reason=handleCountryUnavailable]}, reason=handleCountryUnavailable
08-19 22:46:25.936 D/LocaleTracker-1( 6608): Starting LocaleTracker
08-19 22:46:25.936 D/ImsPhone( 6608): [1] handleMessage what=83
08-19 22:46:25.936 D/RILJ    ( 6608): [0130]< GET_CELL_INFO_LIST [CellInfoWcdma:{mRegistered=YES mTimeStamp=35868135127ns mCellConnectionStatus=0 CellIdentityWcdma:{ mLac=17570 mCid=0 mPsc=21 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong=43220 mAlphaShort=43220 mAdditionalPlmns={} mCsgInfo=null} CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-24 ecno=0 level=0}] [PHONE0]
08-19 22:46:25.937 D/ImsPhone( 6608): [1] handleMessage what=82
08-19 22:46:25.937 D/ImsPhone( 6608): [1] EVENT_DEFAULT_PHONE_DATA_STATE_CHANGED
08-19 22:46:25.937 D/ImsPhone( 6608): [1] updateDataServiceState: defSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=, mOperatorAlphaShort=, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=VoiceSpecificRegistrationInfo { mCssSupported=false mRoamingIndicator=0 mSystemIsInPrl=0 mDefaultRoamingIndicator=0} dataSpecificInfo=null nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}], mNrFrequencyRange=0, mOperatorAlphaLongRaw=, mOperatorAlphaShortRaw=, mIsDataRoamingFromRegistration=false, mIsIwlanPreferred=false, mIsUsingNonTerrestrialNetwork=false} imsSs = {mVoiceRegState=1(OUT_OF_SERVICE), mDataRegState=1(OUT_OF_SERVICE), mChannelNumber=-1, duplexMode()=0, mCellBandwidths=[], mOperatorAlphaLong=null, mOperatorAlphaShort=null, isManualNetworkSelection=false(automatic), getRilVoiceRadioTechnology=0(Unknown), getRilDataRadioTechnology=0(Unknown), mCssIndicator=unsupported, mNetworkId=-1, mSystemId=-1, mCdmaRoamingIndicator=-1, mCdmaDefaultRoamingIndicator=-1, mIsEmergencyOnly=false, isUsingCarrierAggregation=false, mArfcnRsrpBoost=0, mNetworkRegistrationInfos=[NetworkRegistrationInfo{ domain=CS transportType=WWAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WLAN registrationState=UNKNOWN networkRegistrationState=UNKNOWN roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=null nrState=NONE rRplmn= isUsingCarrierAggregation=false isNonTerrestrialNetwork=TERRESTRIAL}, NetworkRegistrationInfo{ domain=PS transportType=WWAN registrationState=NOT_REG_OR_SEARCHING networkRegistrationState=NOT_REG_OR_SEARCHING roamingType=NOT_ROAMING accessNetworkTechnology=UNKNOWN rejectCause=0 emergencyEnabled=false availableServices=[] cellIdentity=null voiceSpecificInfo=null dataSpecificInfo=android.telephony.DataSpecificRegistrationInfo :{ maxDataCalls = 16 isDcNrRestricted = false isNrAvailable = false isEnDcAvailable = false mLteAttachResultType = 0 mLteAttachExtraInfo = 0 null } nrState=NONE rRplmn=000000 isUsingCarrierAggregat
08-19 22:46:25.938 D/GsmCdmaPhone( 6608): [1] onVoiceRegStateOrRatChanged
08-19 22:46:25.938 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, current vrs=1, vrat=0
08-19 22:46:25.938 D/GsmCdmaPhone( 6608): [1] getCsCallRadioTech, result calcVrat=0
08-19 22:46:25.938 D/DRM-1   ( 6608): Remove all retry and throttling entries, reason=DATA_PROFILES_CHANGED
08-19 22:46:25.938 D/GsmCdmaPhone( 6608): EVENT_GET_RADIO_CAPABILITY: phone rc: {mPhoneId = 1 mVersion=1 mSession=0 mPhase=4 mRadioAccessFamily=130047 mLogicModemId= mStatus=1}
08-19 22:46:25.941 D/RILJ    ( 6608): [0131]> GET_CELL_INFO_LIST [PHONE1]
08-19 22:46:25.942 D/DNC-1   ( 6608): onReevaluateExistingDataNetworks: No existing data networks to re-evaluate.
08-19 22:46:25.942 D/DNC-1   ( 6608): Re-evaluating 0 unsatisfied network requests in 0 groups,  due to DATA_PROFILES_CHANGED
08-19 22:46:25.942 D/LocaleTracker-0( 6608): processCellInfo: cell info=[CellInfoWcdma:{mRegistered=YES mTimeStamp=35868135127ns mCellConnectionStatus=0 CellIdentityWcdma:{ mLac=17570 mCid=0 mPsc=21 mUarfcn=2938 mMcc=432 mMnc=20 mAlphaLong=43220 mAlphaShort=43220 mAdditionalPlmns={} mCsgInfo=null} CellSignalStrengthWcdma: ss=-113 ber=0 rscp=-24 ecno=0 level=0}]
08-19 22:46:25.942 E/RILC    ( 6018): getCellInfoListResponse: Invalid response
08-19 22:46:25.942 D/LocaleTracker-0( 6608): updateLocale: countryIso = ir, countryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.942 D/LocaleTracker-0( 6608): updateLocale: timeZoneCountryIso = ir, timeZoneCountryIsoDebugInfo = OperatorNumeric(43220): MccTable.geoCountryCodeForMccMnc("MccMnc{mcc='432', mnc='20'}")
08-19 22:46:25.942 D/NitzStateMachineImpl( 6608): handleCountryDetected: countryIsoCode=ir, mLatestNitzSignal=null
08-19 22:46:25.943 D/RILJ    ( 6608): [0131]< GET_CELL_INFO_LIST error 66 [PHONE1]
08-19 22:46:25.943 D/RilRequest( 6608): [0131]< GET_CELL_INFO_LIST error: com.android.internal.telephony.CommandException: INVALID_RESPONSE ret=[] result={ when=-35s874ms what=43 target=com.android.internal.telephony.ServiceStateTracker }
08-19 22:46:25.943 D/SST     ( 6608): [1] EVENT_GET_CELL_INFO_LIST: error ret null, e=com.android.internal.telephony.CommandException: INVALID_RESPONSE
08-19 22:46:25.943 D/LocaleTracker-1( 6608): Can't get cell info. Try again in 2 secs.
08-19 22:46:25.990 D/DNC-0   ( 6608): Re-evaluating 0 unsatisfied network requests in 0 groups,  due to TAC_CHANGED
08-19 22:46:27.177 D/ONSNetworkScanCtlr( 6608): init called
08-19 22:46:27.184 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 78
08-19 22:46:27.184 D/TelephonyRegistry( 6138): listen ooscl: hasNotifyOpptSubInfoChangedOccurred==false no callback
08-19 22:46:27.185 D/ONSProfileSelector( 6608): ONSProfileSelector init complete
08-19 22:46:27.192 D/ONS     ( 6608): service is enable state true
08-19 22:46:27.199 W/TelephonyRegistry( 6138): Pid 6608 has exceeded half the number of permissible registered listeners. Now at 79
08-19 22:46:27.210 D/ONS     ( 6608): SIM state changed
08-19 22:46:27.945 D/RILJ    ( 6608): [0132]> GET_CELL_INFO_LIST [PHONE1]
08-19 22:46:27.949 E/RILC    ( 6018): getCellInfoListResponse: Invalid response
08-19 22:46:27.949 D/RILJ    ( 6608): [0132]< GET_CELL_INFO_LIST error 66 [PHONE1]
08-19 22:46:27.950 D/RilRequest( 6608): [0132]< GET_CELL_INFO_LIST error: com.android.internal.telephony.CommandException: INVALID_RESPONSE ret=[] result={ when=-37s881ms what=43 target=com.android.internal.telephony.ServiceStateTracker }
08-19 22:46:27.950 D/SST     ( 6608): [1] EVENT_GET_CELL_INFO_LIST: error ret null, e=com.android.internal.telephony.CommandException: INVALID_RESPONSE
08-19 22:46:27.950 D/LocaleTracker-1( 6608): Can't get cell info. Try again in 4 secs.
08-19 22:46:28.286 D/TelephonyNetworkFactory[0]( 6608): got request NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ]
08-19 22:46:28.286 D/TelephonyNetworkFactory[1]( 6608): got request NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ]
08-19 22:46:28.287 D/TelephonyNetworkFactory[0]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:28.286, evaluation result=null] shouldApply false
08-19 22:46:28.288 D/TelephonyNetworkFactory[1]( 6608): onNeedNetworkFor [NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:28.288, evaluation result=null] shouldApply false
08-19 22:46:29.546 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.547 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.661 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.661 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.664 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.664 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.681 D/RILC    ( 6018): SehRadioNetwork::setResponseFunctions
08-19 22:46:29.685 D/RILC    ( 6018): SehRadioNetwork::setResponseFunctions
08-19 22:46:29.982 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:29.982 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.041 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.041 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.062 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.063 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.063 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.063 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.063 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.063 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.065 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.065 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:30.117 E/RILD2   ( 6018): Run(): nlmsg_type = 20
08-19 22:46:30.117 E/RILD    ( 6018): Run(): nlmsg_type = 20
08-19 22:46:30.399 D/SatelliteController( 6608): handleCmdUpdateNtnSignalStrengthReporting: ignore request, satellite is disabled
08-19 22:46:30.400 D/TelephonyCountryDetector( 6608): Wifi network available: 100
08-19 22:46:30.405 D/TelephonyCountryDetector( 6608): getCurrentNetworkCountryIso: invalid countryIso= for phoneId=1, subId=-1
08-19 22:46:30.405 D/SatelliteController( 6608): EVENT_WIFI_CONNECTIVITY_STATE_CHANGED: mIsWifiConnected=true
08-19 22:46:30.406 D/SatelliteController( 6608): handleStateChangedForCarrierRoamingNtnEligibility: carrierRoamingNbIotNtn flag is disabled
08-19 22:46:30.411 D/TelephonyCountryDetector( 6608): Location update was not requested yet
08-19 22:46:31.095 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.094, evaluation result=null] applied false
08-19 22:46:31.095 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.095, evaluation result=null] applied false
08-19 22:46:31.097 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.096, evaluation result=null] applied false
08-19 22:46:31.097 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.096, evaluation result=null] applied false
08-19 22:46:31.098 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.098, evaluation result=null] applied false
08-19 22:46:31.099 E/RILD    ( 6018): OemClient::ProcessBuffer() from[2], token[1], datalen[14]
08-19 22:46:31.099 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.098, evaluation result=null] applied false
08-19 22:46:31.101 E/RILD    ( 6018): Oem OnRequestComplete:(2)
08-19 22:46:31.101 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.100, evaluation result=null] applied false
08-19 22:46:31.103 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.102, evaluation result=null] applied false
08-19 22:46:31.103 E/RILD    ( 6018): OemClient::ProcessBuffer() from[2], token[2], datalen[14]
08-19 22:46:31.103 E/RILD    ( 6018): OemClient::ProcessBuffer() from[2], token[4], datalen[14]
08-19 22:46:31.103 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.102, evaluation result=null] applied false
08-19 22:46:31.105 E/RILD    ( 6018): Oem OnRequestComplete:(2)
08-19 22:46:31.105 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.104, evaluation result=null] applied false
08-19 22:46:31.106 E/RILD    ( 6018): Oem OnRequestComplete:(2)
08-19 22:46:31.107 D/RILClient( 6011): processUnsolicited(): resp_id (11009), len(12)
08-19 22:46:31.107 D/RILClient( 6011): processUnsolicited(): unsol_func resp_id (11009), len(12)
08-19 22:46:31.108 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.106, evaluation result=null] applied false
08-19 22:46:31.108 D/RILClient( 6011): processUnsolicited(): resp_id (11009), len(12)
08-19 22:46:31.108 D/RILClient( 6011): processUnsolicited(): unsol_func resp_id (11009), len(12)
08-19 22:46:31.109 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.109 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.109 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.109 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.109 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.110 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.109, evaluation result=null] applied false
08-19 22:46:31.110 E/RILD    ( 6018): ProcessIpcMessageReceived: Incomplete IPC received.
08-19 22:46:31.110 D/RILClient( 6011): processUnsolicited(): resp_id (11009), len(12)
08-19 22:46:31.110 D/RILClient( 6011): processUnsolicited(): unsol_func resp_id (11009), len(12)
08-19 22:46:31.111 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.111, evaluation result=null] applied false
08-19 22:46:31.111 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.111, evaluation result=null] applied false
08-19 22:46:31.112 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.112, evaluation result=null] applied false
08-19 22:46:31.113 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.112, evaluation result=null] applied false
08-19 22:46:31.113 D/RILClient( 6011): processUnsolicited(): resp_id (11009), len(3178)
08-19 22:46:31.113 D/RILClient( 6011): processUnsolicited(): unsol_func resp_id (11009), len(3178)
08-19 22:46:31.113 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.113, evaluation result=null] applied false
08-19 22:46:31.114 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.113, evaluation result=null] applied false
08-19 22:46:31.115 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=22, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10222 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.114, evaluation result=null] applied false
08-19 22:46:31.116 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.115, evaluation result=null] applied false
08-19 22:46:31.117 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.116, evaluation result=null] applied false
08-19 22:46:31.119 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.118, evaluation result=null] applied false
08-19 22:46:31.119 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.118, evaluation result=null] applied false
08-19 22:46:31.120 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.119, evaluation result=null] applied false
08-19 22:46:31.121 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.120, evaluation result=null] applied false
08-19 22:46:31.121 E/RILD    ( 6018): Run(): nlmsg_type = 20
08-19 22:46:31.121 E/RILD2   ( 6018): Run(): nlmsg_type = 20
08-19 22:46:31.125 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.125, evaluation result=null] applied false
08-19 22:46:31.128 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.127, evaluation result=null] applied false
08-19 22:46:31.130 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.129, evaluation result=null] applied false
08-19 22:46:31.131 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.131, evaluation result=null] applied false
08-19 22:46:31.132 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=85, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.131, evaluation result=null] applied false
08-19 22:46:31.132 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.132, evaluation result=null] applied false
08-19 22:46:31.133 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.133, evaluation result=null] applied false
08-19 22:46:31.134 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.133, evaluation result=null] applied false
08-19 22:46:31.134 D/TelephonyNetworkFactory[0]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.134, evaluation result=null] applied false
08-19 22:46:31.135 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=26, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10207 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.135, evaluation result=null] applied false
08-19 22:46:31.135 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=28, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10205 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.135, evaluation result=null] applied false
08-19 22:46:31.136 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.135, evaluation result=null] applied false
08-19 22:46:31.137 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=16, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10247 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.136, evaluation result=null] applied false
08-19 22:46:31.137 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=54, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.137, evaluation result=null] applied false
08-19 22:46:31.138 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=69, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.138, evaluation result=null] applied false
08-19 22:46:31.139 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=46, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.138, evaluation result=null] applied false
08-19 22:46:31.139 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=37, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10233 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.138, evaluation result=null] applied false
08-19 22:46:31.140 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=82, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.139, evaluation result=null] applied false
08-19 22:46:31.140 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=14, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10252 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.140, evaluation result=null] applied false
08-19 22:46:31.141 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=76, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.140, evaluation result=null] applied false
08-19 22:46:31.141 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=31, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.141, evaluation result=null] applied false
08-19 22:46:31.142 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=91, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.141, evaluation result=null] applied false
08-19 22:46:31.142 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=20, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10226 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.142, evaluation result=null] applied false
08-19 22:46:31.143 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=96, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 10206 RequestorPkg: com.google.android.gms UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.142, evaluation result=null] applied false
08-19 22:46:31.143 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=18, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10232 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.142, evaluation result=null] applied false
08-19 22:46:31.144 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=43, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.143, evaluation result=null] applied false
08-19 22:46:31.144 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=49, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1073 RequestorUid: 1073 RequestorPkg: com.android.networkstack UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.143, evaluation result=null] applied false
08-19 22:46:31.145 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=41, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.145, evaluation result=null] applied false
08-19 22:46:31.146 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=79, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.145, evaluation result=null] applied false
08-19 22:46:31.146 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=33, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10206 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.145, evaluation result=null] applied false
08-19 22:46:31.147 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=67, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.146, evaluation result=null] applied false
08-19 22:46:31.147 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=73, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.147, evaluation result=null] applied false
08-19 22:46:31.147 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=88, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.147, evaluation result=null] applied false
08-19 22:46:31.148 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=35, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10192 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.148, evaluation result=null] applied false
08-19 22:46:31.148 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=39, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10217 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.148, evaluation result=null] applied false
08-19 22:46:31.149 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=63, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1001 RequestorUid: 1001 RequestorPkg: com.android.phone UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.148, evaluation result=null] applied false
08-19 22:46:31.149 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=56, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10154 RequestorUid: 10154 RequestorPkg: com.android.systemui UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.149, evaluation result=null] applied false
08-19 22:46:31.149 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=7, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 1000 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.149, evaluation result=null] applied false
08-19 22:46:31.149 D/TelephonyNetworkFactory[1]( 6608): onReleaseNetworkFor [NetworkRequest [ REQUEST id=24, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VCN_MANAGED&NOT_BANDWIDTH_CONSTRAINED Uid: 10216 RequestorUid: 1000 RequestorPkg: android UnderlyingNetworks: Null] ], mPriority=20, state=UNSATISFIED, mAttachedDataNetwork=null, created time=22:46:31.149, evaluation result=null] applied false
08-19 22:46:31.953 D/RILJ    ( 6608): [0133]> GET_CELL_INFO_LIST [PHONE1]
08-19 22:46:31.960 E/RILC    ( 6018): getCellInfoListResponse: Invalid response
08-19 22:46:31.961 D/RILJ    ( 6608): [0133]< GET_CELL_INFO_LIST error 66 [PHONE1]
08-19 22:46:31.961 D/RilRequest( 6608): [0133]< GET_CELL_INFO_LIST error: com.android.internal.telephony.CommandException: INVALID_RESPONSE ret=[] result={ when=-41s892ms what=43 target=com.android.internal.telephony.ServiceStateTracker }
08-19 22:46:31.961 D/SST     ( 6608): [1] EVENT_GET_CELL_INFO_LIST: error ret null, e=com.android.internal.telephony.CommandException: INVALID_RESPONSE
08-19 22:46:31.961 D/LocaleTracker-1( 6608): Can't get cell info. Try again in 8 secs.
08-19 22:46:36.379 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.379 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.379 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.379 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.390 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.392 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.732 D/RILClient( 7290): Connect_RILD_Internal: socket allocated 5
08-19 22:46:36.732 D/RILClient( 7290): Connect_RILD_Internal: Success to connect
08-19 22:46:36.733 E/RILD    ( 6018): OemClient::ProcessBuffer() from[7], token[1], datalen[4]
08-19 22:46:36.736 E/RILD    ( 6018): Oem OnRequestComplete:(7)
08-19 22:46:36.771 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.771 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.772 E/RILD    ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.773 E/RILD2   ( 6018): Run(): nlmsg_type = 16
08-19 22:46:36.773 E/RILD    ( 6018): Run(): nlmsg_type = 17
08-19 22:46:36.775 E/RILD2   ( 6018): Run(): nlmsg_type = 17
08-19 22:46:37.189 D/RILClient( 7289): Connect_RILD_Internal: socket allocated 12
08-19 22:46:37.190 D/RILClient( 7289): Connect_RILD_Internal: Success to connect
08-19 22:46:37.190 D/RILClient( 7289): Connect_RILD_Internal: socket allocated 15
08-19 22:46:37.190 D/RILClient( 7289): Connect_RILD_Internal: Success to connect
08-19 22:46:39.638 E/RILC    ( 6018): currentSignalStrengthInd: Error : status -32
08-19 22:46:42.202 E/RILC    ( 6018): currentSignalStrengthInd: Error : status -32
08-19 22:46:44.758 E/RILC    ( 6018): currentSignalStrengthInd: Error : status -32
