# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.

install(FILES
    fullduplex_packet_decap.xml
    fullduplex_packet_encap.xml
    fullduplex_packet_encap2.xml
    fullduplex_parse_stream_sync.xml
    fullduplex_digital_sic.xml
    fullduplex_residual_si_vis.xml
    fullduplex_ofdm_constellation.xml
    fullduplex_snr_calc.xml
    #fullduplex_compute_ofdm_prr.xml
    fullduplex_count_packets.xml
    fullduplex_async_divide.xml
    fullduplex_fde_config.xml
    fullduplex_sub20_init.xml DESTINATION share/gnuradio/grc/blocks
)
