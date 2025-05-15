# HeatMap
#convert your gff to a gtf before you run the HeatMap script
module load AGAT/0.9.2-GCC-11.2.0
agat_convert_sp_gff2gtf.pl --gff input_file.gff --gtf_version 3 --output output_file.gtf
