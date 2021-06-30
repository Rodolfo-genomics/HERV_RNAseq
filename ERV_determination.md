###Data_processing
bedToGenePred ERV.bed stdout | genePredToGtf file stdin ERV.gtf
fastq-dump --split-spot SRR8925540
fastq-dump --split-spot SRR8925543
fastq-dump --split-spot SRR1258868
fastq-dump --split-spot ERR3852460
fastq-dump --split-spot ERR3852448
fastq-dump --split-spot SRR13151218
fastq-dump --split-spot SRR333709
fastq-dump --split-spot SRR333711
fastq-dump --split-spot SRR333713
fastq-dump --split-spot SRR333715
fastq-dump --split-spot SRR333717
fastq-dump --split-spot SRR333719
fastq-dump --split-spot SRR333721
fastq-dump --split-spot ERR1954308
fastq-dump --split-spot ERR1954310
fastq-dump --split-spot ERR1954311
fastq-dump --split-spot ERR1954314
fastq-dump --split-spot ERR1954315
fastq-dump --split-spot ERR1954352
fastq-dump --split-spot ERR1954353


fastq-dump --split-3 SRR4344081
fastq-dump --split-3 SRR4344059
fastq-dump --split-3 SRR4344047
fastq-dump --split-3 SRR10967902
fastq-dump --split-3 SRR10967902
fastq-dump --split-3 SRR10967904
fastq-dump --split-3 SRR10440862
fastq-dump --split-3 SRR8587783
fastq-dump --split-3 SRR10611965
fastq-dump --split-3 SRR1754126
fastq-dump --split-3 SRR3707437
fastq-dump --split-3 SRR3707439
fastq-dump --split-3 SRR1799911
fastq-dump --split-3 SRR969856
fastq-dump --split-3 ERR532592
fastq-dump --split-3 SRR11095734
fastq-dump --split-3 SRR11095739
fastq-dump --split-3 SRR8364177
fastq-dump --split-3 SRR957884
fastq-dump --split-3 SRR3308896
fastq-dump --split-3 ERR4628090
fastq-dump --split-3 SRR10007736
fastq-dump --split-3 SRR7204625
fastq-dump --split-3 SRR1751232
fastq-dump --split-3 SRR7538104
fastq-dump --split-3 ERR4627839
fastq-dump --split-3 SRR12696735
fastq-dump --split-3 SRR309262
fastq-dump --split-3 SRR12494331
fastq-dump --split-3 SRR10198733
fastq-dump --split-3 SRR13425455
fastq-dump --split-3 SRR9216811


AdapterRemoval --threads 8 --file1 SRR4344081_1.fastq --file2 SRR4344081_2.fastq --gzip --basename SRR4344081
AdapterRemoval --threads 8 --file1 SRR4344059_1.fastq --file2 SRR4344059_2.fastq --gzip --basename SRR4344059
AdapterRemoval --threads 8 --file1 SRR4344047_1.fastq --file2 SRR4344047_2.fastq --gzip --basename SRR4344047
AdapterRemoval --threads 8 --file1 SRR10967902_1.fastq --file2 SRR10967902_2.fastq --gzip --basename SRR10967902
AdapterRemoval --threads 8 --file1 SRR10967909_1.fastq --file2 SRR10967909_2.fastq --gzip --basename SRR10967909
AdapterRemoval --threads 8 --file1 SRR10967904_1.fastq --file2 SRR10967904_2.fastq --gzip --basename SRR10967904
AdapterRemoval --threads 8 --file1 SRR10440862_1.fastq --file2 SRR10440862_2.fastq --gzip --basename SRR10440862
AdapterRemoval --threads 8 --file1 SRR8587783_1.fastq --file2 SRR8587783_2.fastq --gzip --basename SRR8587783
AdapterRemoval --threads 8 --file1 SRR10611965_1.fastq --file2 SRR10611965_2.fastq --gzip --basename SRR10611965
AdapterRemoval --threads 8 --file1 SRR1754126_1.fastq --file2 SRR1754126_2.fastq --gzip --basename SRR1754126
AdapterRemoval --threads 8 --file1 SRR3707437_1.fastq --file2 SRR3707437_2.fastq --gzip --basename SRR3707437
AdapterRemoval --threads 8 --file1 SRR3707439_1.fastq --file2 SRR3707439_2.fastq --gzip --basename SRR3707439
AdapterRemoval --threads 8 --file1 SRR1799911_1.fastq --file2 SRR1799911_2.fastq --gzip --basename SRR1799911
AdapterRemoval --threads 8 --file1 SRR969856_1.fastq --file2 SRR969856_2.fastq --gzip --basename SRR969856
AdapterRemoval --threads 8 --file1 ERR532592_1.fastq --file2 ERR532592_2.fastq --gzip --basename ERR532592
AdapterRemoval --threads 8 --file1 SRR11095734_1.fastq --file2 SRR11095734_2.fastq --gzip --basename SRR11095734
AdapterRemoval --threads 8 --file1 SRR11095739_1.fastq --file2 SRR11095739_2.fastq --gzip --basename SRR11095739
AdapterRemoval --threads 8 --file1 SRR8364177_1.fastq --file2 SRR8364177_2.fastq --gzip --basename SRR8364177
AdapterRemoval --threads 8 --file1 SRR957884_1.fastq --file2 SRR957884_2.fastq --gzip --basename SRR957884
AdapterRemoval --threads 8 --file1 SRR3308896_1.fastq --file2 SRR3308896_2.fastq --gzip --basename SRR3308896 #####
AdapterRemoval --threads 8 --file1 ERR4628090_1.fastq --file2 ERR4628090_2.fastq --gzip --basename ERR4628090
AdapterRemoval --threads 8 --file1 SRR10313353_1.fastq --file2 SRR10313353_2.fastq --gzip --basename SRR10313353
AdapterRemoval --threads 8 --file1 SRR8925540.fastq --gzip --basename  SRR8925540
AdapterRemoval --threads 8 --file1 SRR8925543.fastq --gzip --basename SRR8925543
AdapterRemoval --threads 8 --file1 SRR1258868.fastq --gzip --basename SRR1258868
AdapterRemoval --threads 8 --file1 ERR3852460.fastq --gzip --basename ERR3852460
AdapterRemoval --threads 8 --file1 ERR3852448.fastq --gzip --basename ERR3852448
AdapterRemoval --threads 8 --file1 SRR13151218.fastq --gzip --basename SRR13151218
AdapterRemoval --threads 8 --file1 SRR10007736_1.fastq --file2 SRR10007736_2.fastq --gzip --basename SRR10007736
AdapterRemoval --threads 8 --file1 SRR7204625_1.fastq --file2 SRR7204625_2.fastq --gzip --basename SRR7204625
AdapterRemoval --threads 8 --file1 SRR1751232_1.fastq --file2 SRR1751232_2.fastq --gzip --basename SRR1751232
AdapterRemoval --threads 8 --file1 SRR7538104_1.fastq --file2 SRR7538104_2.fastq --gzip --basename SRR7538104
AdapterRemoval --threads 8 --file1 ERR4627839_1.fastq --file2 ERR4627839_2.fastq --gzip --basename ERR4627839
AdapterRemoval --threads 8 --file1 SRR12696735_1.fastq --file2 SRR12696735_2.fastq --gzip --basename SRR12696735
AdapterRemoval --threads 8 --file1 SRR309262_1.fastq --file2 SRR309262_2.fastq --gzip --basename SRR309262
AdapterRemoval --threads 8 --file1 SRR12494331_1.fastq --file2 SRR12494331_2.fastq --gzip --basename  SRR12494331
AdapterRemoval --threads 8 --file1 SRR10198733_1.fastq --file2 SRR10198733_2.fastq --gzip --basename SRR10198733
AdapterRemoval --threads 8 --file1 SRR13425455_1.fastq --file2 SRR13425455_2.fastq --gzip --basename SRR13425455
AdapterRemoval --threads 8 --file1 SRR9216811_1.fastq --file2 SRR9216811_2.fastq --gzip --basename SRR9216811
AdapterRemoval --threads 8 --file1 SRR333709.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333711.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333713.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333715.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333717.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333719.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR333721.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954308.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954310.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954311.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954314.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954315.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954352.fastq --gzip 
AdapterRemoval --threads 8 --file1 ERR1954353.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR8925540.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR8925540.fastq --gzip 
AdapterRemoval --threads 8 --file1 SRR8925540.fastq --gzip 



hisat2 -k 10 -p 8 -x hg_38_index -S bone_N.sam -1 SRR4344081_1.fastq -2 SRR4344081_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S bone_P.sam -1 SRR4344059_1.fastq -2 SRR4344059_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S bone_M.sam -1 SRR4344047_1.fastq -2 SRR4344047_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S colon_N.sam -1 SRR10967902_1.fastq -2 SRR10967902_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S colon_P.sam -1 SRR10967909_1.fastq -2 SRR10967909_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S colon_M.sam -1 SRR10967904_1.fastq -2 SRR10967904_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S lung_N.sam -1 SRR10440862_1.fastq -2 SRR10440862_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S lung_P.sam -1 SRR8587783_1.fastq -2 SRR8587783_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S lung_M.sam -1 SRR10611965_1.fastq -2 SRR10611965_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S thyroid_N.sam -1 SRR1754126_1.fastq -2 SRR1754126_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S thyroid_P.sam -1 SRR3707437_1.fastq -2 SRR3707437_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S thyroid_M.sam -1 SRR3707439_1.fastq -2 SRR3707439_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S prostate_N.sam -1 SRR1799911_1.fastq -2 SRR1799911_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S prostate_P.sam -1 SRR969856_1.fastq -2 SRR969856_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S prostate_M.sam -1 ERR532592_1.fastq -2 ERR532592_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S cervix_N.sam -1 SRR11095734_1.fastq -2 SRR11095734_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S cervix_P.sam -1 SRR11095739_1.fastq -2 SRR11095739_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S cervix_M.sam -1 SRR8364177_1.fastq -2 SRR8364177_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S pancreatic_N.sam -1 SRR957884_1.fastq -2 SRR957884_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S pancreatic_P.sam -1 SRR3308896_1.fastq -2 SRR3308896_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S pancreatic_M.sam -1 ERR4628090_1.fastq -2 ERR4628090_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S ovary_N.sam -1 SRR10313353_1.fastq -2 SRR10313353_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S ovary_P.sam -U SRR8925540.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S ovary_M.sam -U SRR8925543.fastq 
hisat2 -k 10 -p 8 -x hg_38_index -S testes_N.sam -U SRR1258868.fastq 
hisat2 -k 10 -p 8 -x hg_38_index -S testes_P.sam -U SRR333709.fastq,SRR333711.fastq,SRR333713.fastq,SRR333715.fastq,SRR333717.fastq,SRR333719.fastq,SRR333721.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S testes_M.sam -U ERR1954308.fastq,ERR1954310.fastq,ERR1954311.fastq,ERR1954314.fastq,ERR1954315.fastq,ERR1954352.fastq,ERR1954353.fastq 
hisat2 -k 10 -p 8 -x hg_38_index -S breast_N.sam -1 SRR10007736_1.fastq -2 SRR10007736_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S breast_P.sam -1 SRR7204625_1.fastq -2 SRR7204625_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S breast_M.sam -1 SRR1751232_1.fastq -2 SRR1751232_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S mela_N.sam -1 SRR7538104_1.fastq -2 SRR7538104_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S mela_P.sam -1 ERR4627839_1.fastq -2 ERR4627839_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S mela_M.sam -1 SRR12696735_1.fastq -2 SRR12696735_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S brain_N.sam -1 SRR309262_1.fastq -2 SRR309262_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S brain_P.sam -U ERR3852460.fastq 
hisat2 -k 10 -p 8 -x hg_38_index -S brain_M.sam -U ERR3852448.fastq 
hisat2 -k 10 -p 8 -x hg_38_index -S lympatic_node.sam -1 SRR12494331_1.fastq -2 SRR12494331_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S lymphoma_H.sam -1 SRR10198733_1.fastq -2 SRR10198733_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S bone_marrow.sam -1 SRR13425455_1.fastq -2 SRR13425455_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S ALL.sam -1 SRR9216811_1.fastq -2 SRR9216811_2.fastq
hisat2 -k 10 -p 8 -x hg_38_index -S MM.sam -U SRR13151218.fastq 


samtools view -S -b bone_N.sam > bone_N.bam | samtools sort bone_N.bam -o sbone_N.bam
samtools view -S -b bone_P.sam > bone_P.bam | samtools sort bone_P.bam -o sbone_P.bam
samtools view -S -b bone_M.sam > bone_M.bam | samtools sort bone_M.bam -o sbone_M.bam
samtools view -S -b colon_N.sam > colon_N.bam | samtools sort colon_N.bam -o scolon_N.bam
samtools view -S -b colon_P.sam > colon_N.bam | samtools sort colon_P.bam -o scolon_P.bam
samtools view -S -b colon_M.sam > colon_N.bam | samtools sort colon_M.bam -o scolon_M.bam
samtools view -S -b bone_N.sam > lung_N.Bam | samtools sort lung_N.bam -o slung_N.bam
samtools view -S -b bone_N.sam > lung_P.bam | samtools sort lung_P.bam -o slung_P.bam
samtools view -S -b bone_N.sam > lung_M.bam | samtools sort lung_M.bam -o slung_M.bam
samtools view -S -b thyroid_N.sam > thyroid_N.bam | samtools sort thyroid_N.bam -o sthyroid_N.bam
samtools view -S -b thyroid_P.sam > thyroid_P.bam | samtools sort thyroid_P.bam -o sthyroid_P.bam
samtools view -S -b thyroid_M.sam > thyroid_M.bam | samtools sort thyroid_M.bam -o sthyroid_M.bam
samtools view -S -b prostate_N.sam > prostate_N.bam | samtools sort prostate_N.bam -o sprostate_N.bam
samtools view -S -b prostate_P.sam > prostate_P.bam | samtools sort prostate_P.bam -o sprostate_P.bam
samtools view -S -b prostate_M.sam > prostate_M.bam | samtools sort prostate_M.bam -o sprostate_M.bam
samtools view -S -b cervix_N.sam > cervix_N.bam | samtools sort cervix_N.bam -o scervix_N.bam
samtools view -S -b cervix_P.sam > cervix_P.bam | samtools sort cervix_P.bam -o scervix_P.bam
samtools view -S -b cervix_M.sam > cervix_M.bam | samtools sort cervix_M.bam -o scervix_M.bam
samtools view -S -b pancreatic_N.sam > pancreatic_N.bam | samtools sort pancreatic_N.bam -o pancreatic_N.bam
samtools view -S -b pancreatic_P.sam > pancreatic_N.bam | samtools sort pancreatic_N.bam -o pancreatic_N.bam
samtools view -S -b pancreatic_M.sam > pancreatic_N.bam | samtools sort pancreatic_N.bam -o pancreatic_N.bam
samtools view -S -b ovary_N.sam > ovary_N.bam | samtools sort ovary_N.bam -o sovary_N.bam
samtools view -S -b ovary_P.sam > ovary_P.bam | samtools sort ovary_P.bam -o sovary_P.bam
samtools view -S -b ovary_M.sam > ovary_M.bam | samtools sort ovary_M.bam -o sovary_M.bam
samtools view -S -b testes_N.sam > testes_N.bam | samtools sort testes_N.bam -o stestes_N.bam
samtools view -S -b testes_P.sam > testes_P.bam | samtools sort testes_P.bam -o stestes_P.bam
samtools view -S -b testes_M.sam > testes_M.bam | samtools sort testes_M.bam -o stestes_M.bam
samtools view -S -b breast_N.sam > breast_N.bam | samtools sort breast_N.bam -o sbreast_N.bam
samtools view -S -b breast_P.sam > breast_P.bam | samtools sort breast_P.bam -o sbreast_P.bam
samtools view -S -b breast_M.sam > breast_M.bam | samtools sort breast_M.bam -o sbreast_M.bam
samtools view -S -b mela_N.sam > mela_N.bam | samtools sort mela_N.bam -o smela_N.bam
samtools view -S -b mela_P.sam > mela_P.bam | samtools sort mela_P.bam -o smela_P.bam
samtools view -S -b mela_M.sam > mela_M.bam | samtools sort mela_M.bam -o smela_M.bam
samtools view -S -b brain_N.sam > brain_N.bam | samtools sort brain_N.bam -o sbrain_N.bam
samtools view -S -b brain_P.sam > brain_P.bam | samtools sort brain_P.bam -o sbrain_P.bam
samtools view -S -b brain_M.sam > brain_M.bam | samtools sort brain_M.bam -o sbrain_M.bam
samtools view -S -b lympatic_node.sam > lympatic_node.bam | samtools sort lympatic_node.bam -o slympatic_node.bam
samtools view -S -b lymphoma_H.sam > lymphoma_H.bam | samtools sort lymphoma_H.bam -o slymphoma_H.bam
samtools view -S -b bone_marrow.sam > bone_marrow.bam | samtools sort bone_marrow.bam -o sbone_marrow.bam
samtools view -S -b ALL.sam > ALL.bam | samtools sort ALL.bam -o sALL.bam
samtools view -S -b MM.sam > MM.bam | samtools sort MM.bam -o sMM.bam



featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o bone_N sbone_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o bone_P sbone_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o bone_M sbone_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o colon_N scolon_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o colon_P scolon_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o colon_M scolon_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o lung_N slung_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o lung_P slung_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o lung_M slung_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o thyroid_N sthyroid_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o thyroid_P sthyroid_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o thyroid_M sthyroid_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o prostate_N sprostate_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o prostate_P sprostate_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o prostate_M sprostate_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o cervix_N scervix_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o cervix_P scervix_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o cervix_M scervix_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o pancreatic_N pancreatic_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o pancreatic_P pancreatic_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o pancreatic_M pancreatic_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o ovary_N sovary_N.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o ovary_P sovary_P.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o ovary_M sovary_M.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o testes_N stestes_N.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o testes_P stestes_P.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o testes_M stestes_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o breast_N sbreast_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o breast_P sbreast_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o breast_M sbreast_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o mela_N smela_N.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o mela_P smela_P.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o mela_M smela_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o brain_N sbrain_N.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o brain_P sbrain_P.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o brain_M sbrain_M.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o lympatic_node slympatic_node.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o lymphoma_H slymphoma_H.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o bone_marrow sbone_marrow.bam
featureCounts -T 8 -p -a ERV.gtf -t exon_id -g gene_id -o ALL sALL.bam
featureCounts -T 8 -a ERV.gtf -t exon_id -g gene_id -o MM sMM.bam

###Workflow in R to determining the expression of HERV in human genome
###Packages
library(DESeq2)
library(RColorBrewer)
library(gplots)
library(vsn)
library(genefilter)
library(ggplot2)
library(pheatmap)
library(IHW)
library(vsn)
library(dplyr)
library(BiocParallel)
library(scales)
library(viridis)
library(reshape2)
library(genefilter)
library(ggrepel)
library(clusterProfiler)
library(org.Sc.sgd.db)
library(BiocParallel)
library()
library(tidyverse)
library(dplyr)
register(MulticoreParam(8))

#### Differential expression

meta <- read.table("meta.txt", header = T, sep = '\t', row.names = 1)
meta

meta_2 <- read.table("meta_2.txt", header = T, quote = "",  )
meta_2
all(colnames(meta) == rownames(meta_2))

diff <- DESeqDataSetFromMatrix(countData = meta_2, colData = meta,
                               design = ~ tissue_status, tidy = T, )

keep <- rowSums(counts(diff)) >= 400 
dim(keep)
diff <- diff[keep,]
dim(diff)

dds <- estimateSizeFactors(diff, type = "poscounts") ### no funciona con 2000
dds <- sizeFactors(dds)

dds <- DESeq(dds)

### brain

res <- results(dds, contrast = c("tissue_status", "Brain-N","Brain-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Brain_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Brain-N","Brain-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Brain_NM.cvs")


#### bone

res <- results(dds, contrast = c("tissue_status", "Bone-N","Bone-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Bone_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Bone-N","Bone-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Bone_NM.cvs")

#### breast

res <- results(dds, contrast = c("tissue_status", "Breast-N","Breast-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Breast_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Breast-N","Breast-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Breast_NM.cvs")

#### melanocyte cells

res <- results(dds, contrast = c("tissue_status", "Mela-N","Mela-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Mela_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Mela-N","Mela-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Mela_NM.cvs")

#### ovary

res <- results(dds, contrast = c("tissue_status", "Ovary-N","Ovary-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Ovary_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Ovary-N","Ovary-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Ovary_NM.cvs")

#### Testes

res <- results(dds, contrast = c("tissue_status", "Testes-N","Testes-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "testes_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Testes-N","Testes-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "testes_NM.cvs")

#### thyroid

res <- results(dds, contrast = c("tissue_status", "Thyroid-N","Thyroid-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Thyroid_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Thyroid-N","Thyroid-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Thyroid_NM.cvs")

#### prostate

res <- results(dds, contrast = c("tissue_status", "Prostate-N","Prostate-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Prostate_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Prostate-N","Prostate-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Prostate_NM.cvs")

#### pancreatic


res <- results(dds, contrast = c("tissue_status", "Pancreatic-N","Pancreatic-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Pancreatic_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Pancreatic-N","Pancreatic-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Pancreatic_NM.cvs")

#### colon 



res <- results(dds, contrast = c("tissue_status", "Colon-N","Colon-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Colon_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Colon-N","Colon-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Colon_NM.cvs")

#### lung

res <- results(dds, contrast = c("tissue_status", "Lung-N","Lung-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Lung_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Lung-N","Lung-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Lung_NM.cvs")


#### cervix

res <- results(dds, contrast = c("tissue_status", "Cervix-N","Cervix-PT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Cervix_NP.cvs")

res <- results(dds, contrast = c("tissue_status", "Cervix-N","Cervix-MT"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "Cervix_NM.cvs")

#### lymatic

res <- results(dds, contrast = c("tissue_status", "Lymphatic node","Lymphoma H"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "lymptatic_NP.cvs")


#### leukemia



res <- results(dds, contrast = c("tissue_status", "Bone marrow","Leukemia (ALL)"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "MM.cvs")

res <- results(dds, contrast = c("tissue_status", "Bone marrow","Myeloma (MM)"))

deseq2ResDF <- as.data.frame(res)

deseq2ResDF$significant <- ifelse(deseq2ResDF$pvalue < .01, "Significant", NA)
deseq2ResDF
dim(deseq2ResDF)

pad <- 0.01
sigGenes <- deseq2ResDF[which(deseq2ResDF$padj < pad),] 
dim (sigGenes)
sig  <- sigGenes[order(sigGenes$padj) , ]
sig <- as.data.frame(sig)
write.csv(sig, "ALL.cvs")

########## plots


top <- read.csv("top152.cvs")


tiff(filename = "cha", width = 8000, height = 2200, 
     compression = "lzw", bg= "white", res =450)

ggplot(top)+aes(x=HERV, y=log2FoldChange, colour = Tissue)+geom_point()
dev.off() 
####### heatmaps

prim <- read.csv("top_primary_tumors.csv")
row.names(prim) <- prim$HERV
prim <- select(prim,c(,2:16))
prim<- data.matrix(prim)


tiff(filename = "primary_tumors.tiff", width = 3000, height = 5200, 
     compression = "lzw", bg= "white", res =450)
pheatmap(prim,scale = "column", col = greenred(100), cluster_cols = T,
         border_color = NA, breaks = seq(-5.5, 5.5, length.out = 101),angle_col= 45,
         fontsize_row = 4, fontsize_col = 7, treeheight_col = 40,treeheight_row =60)

dev.off() 

metast<- read.csv("top_102_metastasic.csv")
row.names(metast) <- metast$HERV
metast <- select(metast,c(,2:13))
metast<- data.matrix(metast)


tiff(filename = "metastatic_tumors.tiff", width = 3000, height = 5200, 
     compression = "lzw", bg= "white", res =450)
pheatmap(metast,scale = "column", col = greenred(100), cluster_cols = T,
         border_color = NA, breaks = seq(-5.5, 5.5, length.out = 101),angle_col= 45,
         fontsize_row = 4, fontsize_col = 7, treeheight_col = 40,treeheight_row =60)

dev.off() 
