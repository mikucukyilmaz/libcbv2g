# Define the component and its properties
idf_component_register(
    SRCS
        "lib/"
        "lib/cbv2g/exi_v2gtp.c"
        "lib/cbv2g/din/din_msgDefDatatypes.c"
        "lib/cbv2g/din/din_msgDefDecoder.c"
        "lib/cbv2g/din/din_msgDefEncoder.c"
        "lib/cbv2g/iso_2/iso2_msgDefDatatypes.c"
        "lib/cbv2g/iso_2/iso2_msgDefDecoder.c"
        "lib/cbv2g/iso_2/iso2_msgDefEncoder.c"
        "lib/cbv2g/app_handshake/appHand_Datatypes.c"
        "lib/cbv2g/app_handshake/appHand_Decoder.c"
        "lib/cbv2g/app_handshake/appHand_Encoder.c"
        "lib/cbv2g/common/exi_basetypes.c"
        "lib/cbv2g/common/exi_basetypes_decoder.c"
        "lib/cbv2g/common/exi_basetypes_encoder.c"
        "lib/cbv2g/common/exi_bitstream.c"
        "lib/cbv2g/common/exi_header.c"
        "lib/cbv2g/common/exi_types_decoder.c"
    INCLUDE_DIRS
        "./include/"
        "./include/cbv2g/"
        "./include/cbv2g/app_handshake/"
        "./include/cbv2g/common/"
        "./include/cbv2g/din/"
        "./include/cbv2g/iso_2/"
        "./include/cbv2g/iso_20/"
)

# If the component depends on other ESP-IDF components, you can specify them here.
# REQUIRES driver
