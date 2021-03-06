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
    isdbt_ofdm_sym_acquisition.xml
    isdbt_sync_and_channel_estimation.xml
    isdbt_subset_of_carriers.xml
    isdbt_frequency_deinterleaver.xml
    isdbt_time_deinterleaver.xml
    isdbt_symbol_demapper.xml
    isdbt_tmcc_decoder.xml
    isdbt_bit_deinterleaver.xml
    isdbt_energy_descrambler.xml
    isdbt_byte_deinterleaver.xml
    #isdbt_bit_deinterleaver_streamed.xml
    isdbt_ofdm_sym_acquisition_dvbt.xml
    isdbt_reed_solomon_dec_isdbt.xml
    isdbt_frequency_deinterleaver_1seg.xml
    isdbt_time_deinterleaver_1seg.xml
    isdbt_symbol_demapper_1seg.xml
    isdbt_viterbi_decoder.xml
    isdbt_isdbt_rf_channel_decoding.xml
    isdbt_isdbt_channel_decoding.xml
    isdbt_ofdm_synchronization.xml
    isdbt_ofdm_synchronization_1seg.xml
    isdbt_tmcc_decoder_1seg.xml
    isdbt_pilot_signals.xml
    isdbt_frequency_interleaver.xml
    isdbt_time_interleaver.xml
    isdbt_hierarchical_combinator.xml
    isdbt_carrier_modulation.xml
    isdbt_byte_interleaver.xml
    isdbt_energy_dispersal.xml
    isdbt_tmcc_encoder.xml DESTINATION share/gnuradio/grc/blocks
)
