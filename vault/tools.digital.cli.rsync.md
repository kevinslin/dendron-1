---
id: 904dcb17-3307-4edd-99f9-a5cdd81bc376
title: Rsync
desc: ''
updated: 1609690795967
created: 1609680294356
---

Note : pasted from ZK sublime ()

Sub [[202002291826]] terminal and unix shortcuts


# local > x2go 

```bash
rsync -rvz -e 'ssh -p 80' --progress ./ allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/pybatchclassyfire/
rsync -rvz -e 'ssh -p 80' --progress ./ allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/
pybatchclassyfire/
rsync -rvz -e 'ssh' --progress ./ allardp@10.25.88.39:/home/EPGL.UNIGE.LOCAL/allardp/
rsync -rvz -e 'ssh' --progress ./ allardp@10.25.88.39:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/data/interim/tables/3_curated/

rsync -rvz -e 'ssh' --progress ./ allardp@x2go.epgl-geneve.org:/home/farma.unige.ch/allardp/Desktop/FARMAnetwork/RECHERCHE/COMMON\ FASIE-FATHO/PMA/Ubuntu_VM_img/ISDB_DNP/results


```

# local > baobab

```bash
rsync -rvz -e 'ssh' --progress ./opennpdb_tofrag allardp@baobab2.unige.ch:/home/allardp/data_to_frag/opennpdb/
rsync -rvz -e 'ssh' --progress ./ allardp@baobab2.unige.ch:/home/allardp/bash_files/opennpdb_bash
rsync -rvz -e 'ssh -p 80' --progress ./is_fragmentation allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/test_rsync
```



# x2go > local 

```bash
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/is_fragmentation/coconut_data/coconut_ISDB_pos.mgf /Users/pma/Dropbox/People/Swap_MS/ISDB_Coconut
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/1_databases/PLANTCYC/2_chemo/2_rdkit/PLANTCYC_chemo_rdkit_new_pm.tsv ./
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/1_databases/PLANTCYC/2_chemo/2_rdkit/PLANTCYC_chemo_rdkit_sanitized_pm.tsv ./
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/outputs/tables/3_curated/curated_tablesampled1000.tsv ./
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/outputs/tables/3_curated/curatedTable5000_shuffled_headed ./
rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/qiime2_cscs_explo_remote/pfabre/cscs_PCoA.qzv ./
rsync -rvz -e 'ssh' --progress allardp@10.25.88.39:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/data/interim/tables/1_translated/structure/unique.tsv ./

rsync -rvz -e 'ssh' --progress allardp@10.25.88.39:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/data/interim/tables_min/3_curated/smiles.gz ./

rsync -rvz -e 'ssh' --progress --include '*.txt' allardp@10.25.88.39:/home/EPGL.UNIGE.LOCAL/allardp/opennaturalproductsdb/data/interim/tables/3_curated/ ./

rsync -rvz -e 'ssh -p 80' --progress allardp@x2go.epgl-geneve.org:/home/EPGL.UNIGE.LOCAL/allardp/Desktop/FARMAnetwork/RECHERCHE/COMMON\ FASIE-FATHO/Workshop_Material/Data_annotation_Workshop_2019/190225_FullDNP_prot_deprot.csv ./


rsync -rvz -e 'ssh' --progress "allardp@x2go.epgl-geneve.org:/home/farma.unige.ch/allardp/Desktop/FARMAnetwork/RECHERCHE/COMMON\ FASIE-FATHO/PMA/Ubuntu_VM_img/ISDB_DNP/results/fbmn_lena_metabo_results_DNP_top50.out" ./ 


```


# baobab > local 

```bash
rsync -rvz -e 'ssh' --progress allardp@baobab2.unige.ch:/home/allardp/CFM_results/npatlas ./results
rsync -rvz -e 'ssh' --progress allardp@baobab2.unige.ch:/home/allardp/CFM_results/npatlas ./results
rsync -rvz -e 'ssh' --progress allardp@baobab2.unige.ch:/home/allardp/CFM_results/coconut ./ --apend
```


