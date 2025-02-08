# landrover-seq - MinION read quality in a Land Rover

Source data and analysis scripts for the Land Rover Sequencing study.

Home: <https://github.com/zwets/landrover-seq>


## Run Metadata

@TODO@ MinKNOW version was ???

From the run [final summary](01-run-meta/final_summary_FAP48412_e78b393c.txt):

    sample_id=C2020
    protocol_group_id=KIDH_01

    instrument=MN36551
    flow_cell_id=FAP48412
    protocol=sequencing/sequencing_MIN106_DNA:FLO-MIN106:SQK-LSK109
    started=2021-03-10T21:51:17.158001+03:00
    acquisition_stopped=2021-03-11T08:10:02.933127+03:00
    processing_stopped=2021-03-11T08:10:08.473044+03:00
    fast5_files_in_final_dest=685
    fastq_files_in_final_dest=685

    protocol_run_id=378c00ac-c642-4a1f-a167-524c471186dd
    acquisition_run_id=e78b393cae8ec468269f5fcfa954c3ff8bbb1344
    basecalling_enabled=1


## Run Data

Source data for the analysis is the sequencing summary file produced by MinKNOW,
a compressed copy of which is available
[here](https://zwets.it/landrover-seq/sequencing_summary_FAP48412_e78b393c.txt.xz).

The sequencing data can be made available on request.  The derived data, to wit
five SARS-CoV-2 viral genomes, have been deposited in GenBank and GISAID, and are
[published here](doi:https://doi.org/10.3389/fmed.2022.1034682):

> Mziray SR, van Zwetselaar M, Kayuki CC, Mbelele PM, Makubi AN, Magesa AS, et al.
> _Whole-genome sequencing of SARS-CoV-2 isolates from symptomatic and asymptomatic
> individuals in Tanzania._ Frontiers in Medicine. 2023;9.


## Timeline

From [final summary](01-run-meta/final_summary_FAP48412_e78b393c.txt):

    started=2021-03-10T21:51:17.158001+03:00
    acquisition_stopped=2021-03-11T08:10:02.933127+03:00
    processing_stopped=2021-03-11T08:10:08.473044+03:00

Estimated times:

 - Start of run 2024-03-10 21:51:17
 - Walking photo 2024-03-10 22:54:44
 - Descent to Boma ~23:00 - ??
 - Flat ride to Moshi ?? - ??
 - Driving photo 2024-03-11 (time? @TODO@ mziray original)
 - Arrival hotel 2023-03-11 ??:??
 - Stationary sequencing ??:?? - 08:10:08
 - End of run 2023-03-11 08:10:47


## Photos

Photos


---

### Licence

landrover-seq - MinION read quality in a Land Rover repository
Copyright (C) 2025  Marco van Zwetselaar

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

