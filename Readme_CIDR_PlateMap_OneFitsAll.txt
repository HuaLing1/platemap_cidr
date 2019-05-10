##########
# Python Style
##########

# Adebamowo: non-family study. no cross study dup
CIDR_PlateMap_OneFitsAll_pythonStyle.R \
	-p testAdebamowo \
	-i /mnt/research/active/Adebamowo_CervicalCa_H3Africa_033117_1/Project_Management/Plate_Maps/Files_for_Genetic_Analysts \
	-a P2112_Adebamowo_REARRAYSENT_2019-02-21-13_47_15.916.csv \
	-d DUPS_Aliquot_Report_022619_7742_modified_by_PM_for_GA.csv \
	-f Adebamowo_CervicalCa_H3Africa_033117_1_SIF_Aliquot_022619_81243_modified_by_PM_for_GA.csv \
	-n 11567 \
	-s 'MTA' \
	-b 'Population' \
	-r 365 \
	2>&1 | tee > log.proj.txt

# Shaffer: Family study with cross-study dup
CIDR_PlateMap_OneFitsAll_pythonStyle.R \
	-p testShaffer \
	-i /mnt/research/active/Shaffer_DentalCaries_MultiEthnicGlobal_033117_2/Project_Management/Plate_Map_Design/ForMakePlateMap \
	-a P2104_Shaffer_REARRAYSENT_2018-05-16-08_46_45.109.csv \
	-d DUPS_Aliquot_Report_040219_25534.csv \
	-f Shaffer_DentalCaries_MultiEthnicGlobal_033117_2_SIF_Aliquot_040219_2523.csv \
	-n 3233 \
	-s 'NA' \
	-b 'Population Sex' \
	-r 365 \
	2>&1 | tee > log.proj.txt

# Catalona (ProCa). non-family study. no cross study dup
CIDR_PlateMap_OneFitsAll_pythonStyle.R \
	-p testCatalona \
	-i /mnt/research/active/Catalona_ProstateCa_MultiEthnicGlobalPlusCustom_120916_1/Project_Management/Plate_Map_Files_Needed_by_GA \
	-a P2075_Catalona_REARRAYSENT_2019-01-15-16_21_55.045.csv \
	-d DUPS_Aliquot_Report_010919_14939_CIDR.csv \
	-f Catalona_ProstateCa_MultiEthnicGlobalPlusCustom_120916_1_SIF_Aliquot_011119_84325.csv \
	-n 6613 \
	-s 'Population' \
	-b 'DNA.Source DNA.Extraction.Method MTA IRB' \
	-r 419 \
	2>&1 | tee > log.proj.txt




