install(FILES
    kiss_submitter.grc
    csp_rx_asmgolay_vector.grc
    README.md
    
    DESTINATION share/gnuradio/examples/satellites
)

install(FILES
    doppler_correction/doppler_correction_example.grc
    doppler_correction/doppler_file.txt
    
    DESTINATION share/gnuradio/examples/satellites/doppler_correction
)

install(FILES
    satellite_decoder/satellite_decoder.grc
    
    DESTINATION share/gnuradio/examples/satellites/satellite_decoder
)

install(FILES
    ber/lilacsat1_bpsk.grc
    ber/lilacsat1_viterbi.grc
    ber/lilacsat1_ber_bpsk.py
    ber/lilacsat1_ber_viterbi.py
    ber/lilacsat1.py
    ber/lilacsat1.png

    DESTINATION share/gnuradio/examples/satellites/ber
)

install(FILES
    satellites/tanusha3_pm.grc
    satellites/k2sat_image.grc
    satellites/nexus.grc
    satellites/equisat.grc

    DESTINATION share/gnuradio/examples/satellites/satellites
)


install(FILES
    satellites/nx_decoder/dstar_one.grc
    satellites/nx_decoder/amgu_1.grc
    satellites/nx_decoder/sokrat.grc
    satellites/nx_decoder/beesat.grc

    DESTINATION share/gnuradio/examples/satellites/satellites/nx_decoder
)

install(FILES
    ax25/afsk.grc
    ax25/bpsk.grc
    ax25/fsk.grc
    ax25/bpsk9k6.grc
    ax25/README.md

    DESTINATION share/gnuradio/examples/satellites/ax25
)
   
install(FILES
    ccsds/TC_Packet.grc
    ccsds/Space_Packet_with_TimeStamp.grc
    ccsds/Space_Packet_without_TimeStamp.grc
    ccsds/TM_Packet_with_OCF.grc
    ccsds/TM_Packet_with_VC_demux.grc
    ccsds/TM_Packet.grc
    ccsds/TM_Packet_with_Space_Packet.grc
    ccsds/Space_Packet_with_PathID_Demux.grc
    
    DESTINATION share/gnuradio/examples/satellites/satellites/ccsds
)

install(FILES
    qo100-multimedia-beacon/qo100_multimedia_beacon.grc
    qo100-multimedia-beacon/qo100_multimedia_beacon_ea4gpz.grc
    qo100-multimedia-beacon/qo100_multimedia_beacon_df2et.grc
    qo100-multimedia-beacon/qo100_websocket_server.py
    qo100-multimedia-beacon/README.md
    
    DESTINATION share/gnuradio/examples/satellites/satellites/qo100-multimedia-beacon
)

install(FILES
    components/afsk_demodulator.grc
    components/bpsk_demodulator.grc
    components/telemetry_parser.grc
    components/kiss_transport.grc
    components/ax25_deframer.grc
    components/ccsds_deframer.grc
    components/ao40_fec_deframer.grc
    components/u482c_deframer.grc
    components/image_receiver.grc
    components/fsk_demodulator.grc
    components/ax100_deframer.grc

    DESTINATION share/gnuradio/examples/satellites/components
)
