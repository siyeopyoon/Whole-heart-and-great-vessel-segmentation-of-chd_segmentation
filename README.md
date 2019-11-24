# Whole-heart-and-great-vessel-segmentation-of-chd_segmentation
A dataset of whole heart and great vessel segmentation of chd_segmentation is published.

Our dataset includes 68 CT images with labels. The label includes left ventricle (label: 1), right ventricle (label: 2), left atrium (label: 3), right atrium (label: 4), myocardium (label: 5), aorta (label: 6), and pulmonary artery (label: 7).
You notice other labels such 14 etc., you can just ignore them as they are labels corresponding to airways etc.

Our dataset is available at https://notredame.box.com/v/chdsegmentationdataset, and please send emails to Prof. Yiyu Shi yshi4@nd.edu for the password. 

If you used our dataset, please consider to cite our paper in MICCAI 2019, Xiaowei Xu, Tianchen Wang, Yiyu Shi, Haiyun Yuan, Qianjun Jia, Meiping Huang, and Jian Zhuang, "Whole-Heart and Great Vessel Segmentation in Congenital Heart Disease using Deep Neural Networks and Graph Matching," in Proc. of Medical Image Computing and Computer Assisted Interventions (MICCAI), Shenzhen, China, 2019.

The diagnosis of the dataset is as follows: (suggest to copy and paste it in the excel, and parse it with rows)
Index	ASD	AVSD	VSD	AD	ToF	PAS	PDA	CA	CAT	PS	AAA	TGA	SV	PuA	Normal

1001	0	1	0	0	0	0	0	0	0	0	0	0	0	0	0

1002	0	0	1	0	0	0	0	0	0	0	0	0	0	0	0

1004	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0

1007	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
1008	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1010	0	0	0	0	1	0	0	0	0	0	0	0	0	0	0
1012	0	0	0	0	1	0	0	0	0	0	0	0	0	0	0
1016	1	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1021	0	0	1	1	0	0	0	0	0	0	0	0	0	0	0
1022	1	0	0	0	0	1	0	0	0	0	0	0	0	0	0
1024	0	0	1	1	0	0	1	1	0	0	0	0	0	0	0
1026	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1027	0	0	1	0	1	0	0	0	0	0	0	0	0	0	0
1028	0	0	0	0	1	0	0	0	0	0	0	0	0	0	0
1029	0	0	1	0	0	0	0	0	0	0	0	0	0	0	0
1030	0	0	0	0	0	0	0	0	1	0	0	0	0	0	0
1032	0	0	0	0	0	0	0	0	0	1	0	0	0	0	0
1033	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
1035	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
1036	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
1037	0	0	0	0	1	0	0	0	0	0	0	0	0	0	0
1039	0	0	0	0	0	0	0	0	0	0	1	0	0	0	0
1040	0	0	0	0	0	0	0	0	0	0	0	0	0	0	1
1041	0	0	1	0	0	0	0	0	0	0	0	0	0	0	0
1042	0	0	1	1	0	0	0	0	0	0	0	0	0	0	0
1043	1	0	1	1	0	0	0	0	0	0	0	1	0	0	0
1044	1	0	1	1	0	0	0	0	0	0	0	0	0	0	0
1046	0	0	0	0	1	0	0	0	0	0	0	0	0	0	0
1048	1	0	0	0	0	0	0	0	0	0	1	0	0	0	0
1053	1	0	0	0	0	0	0	0	0	0	1	0	0	0	0
1056	0	0	1	1	0	0	0	0	0	0	0	0	0	0	0
1059	0	0	0	0	0	0	0	0	1	0	0	0	0	0	0
1060	1	0	1	0	0	0	1	0	0	0	0	1	1	0	0
1061	0	0	0	0	0	1	1	0	0	0	0	0	0	0	0
1062	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1066	0	1	0	0	0	0	0	0	0	0	0	0	0	0	0
1070	1	0	0	0	0	0	0	0	0	0	0	0	0	0	0
1072	0	0	0	0	0	0	0	0	0	0	0	0	0	0	1
1074	0	0	1	0	1	0	0	0	0	0	0	0	0	0	0
1077	1	0	1	0	0	0	0	0	0	0	1	0	0	0	0
1079	0	1	0	0	0	0	0	0	0	0	0	0	0	0	0
1080	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1081	1	0	1	0	0	0	1	0	0	0	1	0	0	0	0
1083	0	0	0	0	0	0	0	0	0	0	0	1	0	0	0
1085	0	1	0	0	0	0	0	0	0	0	0	1	0	0	0
1088	0	0	0	0	0	0	0	1	0	0	0	0	0	0	0
1089	0	0	0	1	0	0	0	0	0	0	0	0	0	0	0
1090	0	0	0	1	0	0	0	1	0	1	0	0	0	0	0
1091	0	0	1	0	0	0	1	0	1	0	1	0	0	0	0
1092	0	0	1	1	0	0	0	0	0	0	0	0	0	1	0
1098	0	0	0	0	0	0	0	0	1	0	0	0	0	0	0
1099	0	0	1	1	0	0	0	0	0	0	0	0	0	1	0
1101	0	0	0	0	0	0	0	0	0	0	0	0	0	0	1
1102	1	0	1	1	0	0	1	0	0	0	0	0	0	1	0
1103	0	0	1	0	0	0	0	0	0	0	0	0	0	0	0
1106	1	0	0	1	0	0	0	0	0	0	1	0	0	0	0
1109	0	0	0	1	0	0	1	0	0	0	0	0	0	0	0
1111	0	0	0	0	0	0	0	0	0	1	0	0	0	0	0
1113	0	0	1	1	0	0	0	0	0	0	0	0	0	1	0
1114	0	0	0	0	0	1	0	0	0	0	0	0	0	0	0
1116	0	0	0	0	0	0	0	0	0	0	0	0	1	0	0
1117	0	0	1	0	0	0	0	0	0	0	0	0	0	1	0
1122	0	0	1	0	0	0	0	0	0	0	0	0	0	1	0
1124	1	0	1	0	0	0	0	0	0	0	1	0	0	0	0
1125	0	0	1	0	0	0	0	0	0	0	0	0	0	1	0
1126	0	0	0	0	0	0	0	1	0	0	0	0	0	0	0
1127	0	0	1	0	0	0	0	0	0	1	0	0	0	0	0
1128	0	0	1	0	0	0	0	0	0	0	0	0	0	0	0
