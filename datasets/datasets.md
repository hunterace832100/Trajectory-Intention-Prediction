<a name=top></a>
---
<a href=../README.md#top><l style="font-size:30px">Home</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../papers/papers.md#top><l style="font-size:30px">Papers</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<l style="font-size:35px">Datasets</l>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;<a href=../metrics.md#top><l style="font-size:30px">Metrics</l></a>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
---
<h2>数据集格式</h2> 
以下是调研过程中相关的数据集。

每个数据集都有对应提出的文章链接，**点击数据集名称**，会有更为详细的信息，包括以下信息：

* **Summary** 数据集的基本情况介绍，包括大小和类别信息等等
* **Applications** 数据的应用任务
* **Data type and annotations** 数据集的数据类型和标注
* **Task**  在何种情况下的数据集集。（例如：监控、驾驶）
* **Bibtext** 数据集引用

</ul></details>
</ul><a name=datasets_Trajectory></a>
<h2>Trajectory</h2> 
<ul><a name=ucy></a>
<details close>
<summary><l style="font-size:20px"><strong>UCY</strong></l> <a href=https://graphics.cs.ucy.ac.cy/research/downloads/crowd-data.html>link</a> <a href=https://onlinelibrary.wiley.com/doi/abs/10.1111/j.1467-8659.2007.01089.x>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance videos capturing 900+ pedestrian trajectories in outdoor environments containing 4 videos
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory, gaze</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Lerner_2007_CGF,
    author = "Lerner, Alon and Chrysanthou, Yiorgos and Lischinski, Dani",
    title = "Crowds By Example",
    journal = "Computer graphics forum",
    volume = "26",
    number = "3",
    pages = "655--664",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=eth></a>
<details close>
<summary><l style="font-size:20px"><strong>ETH</strong></l> <a href=https://icu.ee.ethz.ch/research/datsets.html>link</a> <a href=https://www.google.com.hk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjixdLTurPtAhWMGaYKHZNcDEwQFjAAegQIAhAC&url=http%3A%2F%2Fvision.cse.psu.edu%2Fcourses%2FTracking%2Fvlpr12%2FPellegriniNeverWalkAlone.pdf&usg=AOvVaw37l3BEnJz_dAfzeX6aNQyC>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrian trajectory with 650 tracks in 25+ minutes of video footage
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Pellegrini_2009_ICCV,
    author = "Pellegrini, Stefano and Ess, Andreas and Schindler, Konrad and Van Gool, Luc",
    title = "You'Ll Never Walk Alone: Modeling Social Behavior For Multi-Target Tracking",
    booktitle = "ICCV",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=nuscenes></a>
<details close>
<summary><l style="font-size:20px"><strong>nuScenes</strong></l> <a href=https://www.nuscenes.org/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1903.11027.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 1K driving sequences and 1M+ 3D bounding boxes annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em> </li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Caesar_2020_CVPR,
    author = "Caesar, Holger and Bankiti, Varun and Lang, Alex H. and Vora, Sourabh and Liong, Venice Erin and Xu, Qiang and Krishnan, Anush and Pan, Yu and Baldan, Giancarlo and Beijbom, Oscar",
    title = "nuScenes: A Multimodal Dataset for Autonomous Driving",
    booktitle = "Proceedings of the CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=kitti></a>
<details close>
<summary><l style="font-size:20px"><strong>KITTI</strong></l> <a href=http://www.cvlibs.net/datasets/kitti/>link</a> <a href=https://ieeexplore.ieee.org/document/6248074>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A large-scale driving dataset recorded with different modalities including stereo, LIDAR, GPS, etc. recorded at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> Video prediction, Trajectory prediction, Other prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, bounding box, optical flow, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Geiger_2012_CVPR,
    author = "Geiger, Andreas and Lenz, Philip and Urtasun, Raquel",
    title = "Are We Ready For Autonomous Driving? The Kitti Vision Benchmark Suite",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=ngsim></a>
<details close>
<summary><l style="font-size:20px"><strong>Next Generation simulationulation (NGSIM)</strong></l> <a href=https://catalog.data.gov/dataset/next-generation-simulation-ngsim-vehicle-trajectories>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 10K+ frames of recording
</li>
<li>
<em><strong>Applications:</strong></em>Action prediction, Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{NGSIM_2007,
    author = "of Transporation, U.S. Department",
    Title = "Next Generation Simulation (Ngsim)",
    HowPublished = "Online",
    accessed = "2019-11-29",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=sd></a>
<details close>
<summary><l style="font-size:20px"><strong>Stanford Drone (SD)</strong></l> <a href=http://cvgl.stanford.edu/projects/uav_data/>link</a> <a href=https://link.springer.com/chapter/10.1007/978-3-319-46484-8_33>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians and cyclists movements recorded using an aerial drone with 3K+ tracks
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Robicquet_2016_ECCV,
    author = "Robicquet, Alexandre and Sadeghian, Amir and Alahi, Alexandre and Savarese, Silvio",
    title = "Learning Social Etiquette: Human Trajectory Understanding In Crowded Scenes",
    booktitle = "ECCV",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=cityscapes></a>
<details close>
<summary><l style="font-size:20px"><strong>Cityscapes</strong></l> <a href=https://www.cityscapes-dataset.com/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2016/papers/Cordts_The_Cityscapes_Dataset_CVPR_2016_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1604.01685.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of street images with annotations for 30 traffic objects in 5k frames and weak annotations in 20k frames
</li>
<li>
<em><strong>Applications:</strong></em>Video prediction, Trajectory prediction, Other prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Cordts_2016_CVPR,
    author = "Cordts, Marius and Omran, Mohamed and Ramos, Sebastian and Rehfeld, Timo and Enzweiler, Markus and Benenson, Rodrigo and Franke, Uwe and Roth, Stefan and Schiele, Bernt",
    title = "The Cityscapes Dataset For Semantic Urban Scene Understanding",
    booktitle = "CVPR",
    year = "2016"
}
</pre>
</details>

</ul></details>
<a name=jaad></a>
<details close>
<summary><l style="font-size:20px"><strong>Joint Attention in Autonomous Driving (JAAD)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/JAAD_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017_workshops/papers/w3/Rasouli_Are_They_Going_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of pedestrians with 346 video sequences showing pedestrians at the time of crossing in different geographical locations and under different weather conditions
</li>
<li>
<em><strong>Applications:</strong></em> Video prediction, Action prediction, Trajectory prediction, Other prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, temporal segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rasouli_2017_ICCVW,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Tsotsos, John K.",
    title = "Are They Going To Cross? A Benchmark Dataset And Baseline For Pedestrian Crosswalk Behavior",
    booktitle = "ICCVW",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=argoverse></a>
<details close>
<summary><l style="font-size:20px"><strong>Argoverse</strong></l> <a href=https://www.argoverse.org/data.html>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1911.02620.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with 100+ driving segments and 10K+ 3D bounding boxes for tracking and 300K+ segments for forecasting annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D bounding box, Map</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chang_2019_CVPR,
    author = "Chang, Ming-Fang and Lambert, John and Sangkloy, Patsorn and Singh, Jagjeet and Bak, Slawomir and Hartnett, Andrew and Wang, De and Carr, Peter and Lucey, Simon and Ramanan, Deva and Hays, James",
    title = "Argoverse: 3D Tracking And Forecasting With Rich Maps",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=gc></a>
<details close>
<summary><l style="font-size:20px"><strong>New York Grand Central (GC)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/grandcentral.html>link</a> <a href=https://ieeexplore.ieee.org/document/6248013>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A trajectory dataset of pedestrians walking in the train station with 50K+ samples annotated at 25fps
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Zhou_2012_CVPR,
    author = "Zhou, Bolei and Wang, Xiaogang and Tang, Xiaoou",
    title = "Understanding Collective Crowd Behaviors: Learning A Mixture Model Of Dynamic Pedestrian-Agents",
    booktitle = "CVPR",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=wod></a>
<details close>
<summary><l style="font-size:20px"><strong>Waymo Open Dataset (WOD)</strong></l> <a href=https://waymo.com/open/>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Sun_Scalability_in_Perception_for_Autonomous_Driving_Waymo_Open_Dataset_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.04838.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with approx. 2K driving segments and 20M+ 2D/3D bounding boxes annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, Bounding Box, 3D Bounding Box, Object Class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Sun_2020_CVPR_3,
    author = "Sun, Pei and Kretzschmar, Henrik and Dotiwalla, Xerxes and Chouard, Aurelien and Patnaik, Vijaysai and Tsui, Paul and Guo, James and Zhou, Yin and Chai, Yuning and Caine, Benjamin and Vasudevan, Vijay and Han, Wei and Ngiam, Jiquan and Zhao, Hang and Timofeev, Aleksei and Ettinger, Scott and Krivokon, Maxim and Gao, Amy and Joshi, Aditya and Zhang, Yu and Shlens, Jonathon and Chen, Zhifeng and Anguelov, Dragomir",
    title = "Scalability in Perception for Autonomous Driving: Waymo Open Dataset",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=virat/actev></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT/ActEV</strong></l> <a href=https://actev.nist.gov/trecvid19>link</a> <a href=https://www-nlpir.nist.gov/projects/tvpubs/tv18.papers/tv18overview.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiview surveillance sequences for trajectory  prediction and activity detection of 38 outdoor common activities
</li>
<li>
<em><strong>Applications:</strong></em>Action prediction, Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Awad_2018_Trecvid,
    author = "Awad, George and Butt, Asad and Curtis, Keith and Lee, Yooyoung and Fiscus, Jonathan and Godil, Afzad and Joy, David and Delgado, Andrew and Smeaton, Alan and Graham, Yvette and others",
    title = "Benchmarking Video Activity Detection, Video Captioning And Matching, Video Storytelling Linking And Video Search",
    booktitle = "TRECVID",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=town_center></a>
<details close>
<summary><l style="font-size:20px"><strong>Town Center</strong></l> <a href=http://www.robots.ox.ac.uk/ActiveVision/Research/Projects/2009bbenfold_headpose/project.html#datasets>link</a> <a href=https://ieeexplore.ieee.org/document/5995667>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance recording of 2.2K pedestrians walking at the Oxford Town Center
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Benfold_2011_CVPR,
    author = "Benfold, Ben and Reid, Ian",
    title = "Stable Multi-Target Tracking In Real-Time Surveillance Video",
    booktitle = "CVPR",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=forking_paths></a>
<details close>
<summary><l style="font-size:20px"><strong>Forking Paths</strong></l> <a href=https://github.com/JunweiLiang/Multiverse>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Liang_The_Garden_of_Forking_Paths_Towards_Multi-Future_Trajectory_Prediction_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1912.06445.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 3K simulated videos of pedestrian trajectory samples from 4 different camera views. Each sample comes with multiple human-annotated possible trajectories.
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance (simulation)</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Liang_2020_CVPR_2,
    author = "Liang, Junwei and Jiang, Lu and Murphy, Kevin and Yu, Ting and Hauptmann, Alexander",
    title = "The Garden of Forking Paths: Towards Multi-Future Trajectory Prediction",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=pie></a>
<details close>
<summary><l style="font-size:20px"><strong>Pedestrian Intention Estimation (PIE)</strong></l> <a href=http://data.nvision2.eecs.yorku.ca/PIE_dataset/>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Rasouli_PIE_A_Large-Scale_Dataset_and_Models_for_Pedestrian_Intention_Estimation_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of driving sequences with more than 6 hours of footage with 1.8K+ pedestrian tracks and 2.3M+ relevant traffic object bounding boxes annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em> Action prediction, Trajectory prediction
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, attribute, temporal segment, vehicle sensors, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Rasouli_2019_ICCV,
    author = "Rasouli, Amir and Kotseruba, Iuliia and Kunic, Toni and Tsotsos, John K.",
    title = "Pie: A Large-Scale Dataset And Models For Pedestrian Intention Estimation And Trajectory Prediction",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=hev-i></a>
<details close>
<summary><l style="font-size:20px"><strong>Honda Egocentric View-Intersection (HEV-I)</strong></l> <a href=https://usa.honda-ri.com/hevi0>link</a> <a href=https://ieeexplore.ieee.org/document/8794474>paper</a> <a href=https://arxiv.org/pdf/1809.07408.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 230 video clips of driving at different intersections in San Francisco annotated at 10Hz
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Object Class, Bounding Box, Tracking ID, activity label, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yao_2019_ICRA,
    author = "Yao, Y. and Xu, M. and Choi, C. and Crandall, D. J. and Atkins, E. M. and Dariush, B.",
    booktitle = "ICRA",
    title = "Egocentric Vision-based Future Vehicle Localization for Intelligent Driving Assistance Systems",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=highd></a>
<details close>
<summary><l style="font-size:20px"><strong>HighD</strong></l> <a href=https://www.highd-dataset.com/>link</a> <a href=https://arxiv.org/pdf/1810.05642.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 147 hours of 110K+ cars driving on German highways recorded from top-down view using a drone
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Trajectory, Vehicle Type, Vehicle Size</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Krajewski_2018_ITSC,
    author = "Krajewski, Robert and Bock, Julian and Kloeker, Laurent and Eckstein, Lutz",
    title = "The highD Dataset: A Drone Dataset of Naturalistic Vehicle Trajectories on German Highways for Validation of Highly Automated Driving Systems",
    booktitle = "ITSC",
    year = "2018"
}
</pre>
</details>

</ul></details>
<a name=orc></a>
<details close>
<summary><l style="font-size:20px"><strong>Oxford Robot Car (ORC)</strong></l> <a href=https://robotcar-dataset.robots.ox.ac.uk/>link</a> <a href=https://journals.sagepub.com/doi/abs/10.1177/0278364916679498>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset containing 100 repetitions of a consistent route through Oxford driving by a vehicle under different weather and traffic conditions
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, vehicle sensors</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Maddern_2017_IJRR,
    Author = "Maddern, Will and Pascoe, Geoff and Linegar, Chris and Newman, Paul",
    Title = "1 Year, 1000Km: The Oxford Robotcar Dataset",
    Journal = "IJRR",
    Volume = "36",
    Number = "1",
    Pages = "3-15",
    Year = "2017"
}
</pre>
</details>

</ul></details>
<a name=chuk_avenue></a>
<details close>
<summary><l style="font-size:20px"><strong>CHUK Avenue</strong></l> <a href=http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html>link</a> <a href=https://openaccess.thecvf.com/content_iccv_2013/papers/Lu_Abnormal_Event_Detection_2013_ICCV_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 37 video clips with 30K+ frames showing abnormal events
</li>
<li>
<em><strong>Applications:</strong></em> Video prediction, Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, anomaly, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Lu_2013_ICCV,
    author = "Lu, Cewu and Shi, Jianping and Jia, Jiaya",
    title = "Abnormal Event Detection At 150 Fps In Matlab",
    booktitle = "ICCV",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=virat></a>
<details close>
<summary><l style="font-size:20px"><strong>VIRAT</strong></l> <a href=http://viratdata.org/>link</a> <a href=https://ieeexplore.ieee.org/document/5995586>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A multiview dataset of 12 events, such as a person loading an object to a vehicle, a person opening a vehicle trunk, recorded in 11 scenes for a total of approx. 8.5 hours of video footage
</li>
<li>
<em><strong>Applications:</strong></em> Action prediction, Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Surveillance, Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Oh_2011_CVPR,
    author = "Oh, Sangmin and Hoogs, Anthony and Perera, Amitha and Cuntoor, Naresh and Chen, Chia-Chih and Lee, Jong Taek and Mukherjee, Saurajit and Aggarwal, JK and Lee, Hyungtae and Davis, Larry and others",
    title = "A Large-Scale Benchmark Dataset For Event Recognition In Surveillance Video",
    booktitle = "CVPR",
    year = "2011"
}
</pre>
</details>

</ul></details>
<a name=ca></a>
<details close>
<summary><l style="font-size:20px"><strong>Collective Activity (CA)</strong></l> <a href=http://www-personal.umich.edu/~wgchoi/eccv12/wongun_eccv12.html>link</a> <a href=https://ieeexplore.ieee.org/document/5457461>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40+ video clips showing collective activities including  crossing, waiting, queueing, walking and talking
</li>
<li>
<em><strong>Applications:</strong></em> Action prediction, Trajectory prediction, Motion prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, activity label, temporal segment, pose</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Choi_2009_ICCVW,
    author = "Choi, Wongun and Shahid, Khuram and Savarese, Silvio",
    title = "What Are They Doing? : Collective Activity Classification Using Spatio-Temporal Relationship Among People",
    booktitle = "ICCVW",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=eifp></a>
<details close>
<summary><l style="font-size:20px"><strong>Edinburgh Informatics Forum Pedestrian (EIFP)</strong></l> <a href=http://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/>link</a> <a href=https://homepages.inf.ed.ac.uk/rbf/FORUMTRACKING/IM090734.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 92K+ trajectories recorded with a top-down view camera capturing people walking inside a campus area for a period of several month
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, Tracking ID</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@mastersthesis{Majecka_2009,
    author = "Majecka, Barbara",
    title = "Statistical Models Of Pedestrian Behaviour In The Forum",
    school = "School of Informatics, University of Edinburgh",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=mot></a>
<details close>
<summary><l style="font-size:20px"><strong>MOT</strong></l> <a href=https://motchallenge.net/>link</a> <a href=https://arxiv.org/pdf/1504.01942.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A collection of videos from existing datasets for the purpose of object tracking
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Leal_2015_arxiv,
    author = "Leal-Taix\'e, Laura and Milan, Anton and Reid, Ian and Roth, Stefan and Schindler, Konrad",
    title = "Motchallenge 2015: Towards A Benchmark For Multi-Target Tracking",
    journal = "arXiv:1504.01942",
    year = "2015"
}
</pre>
</details>

</ul></details>
<a name=traf></a>
<details close>
<summary><l style="font-size:20px"><strong>TRAF</strong></l> <a href=https://drive.google.com/drive/folders/1LqzJuRkx5yhOcjWFORO5WZ97v6jg8RHN>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2019/papers/Chandra_TraPHic_Trajectory_Prediction_in_Dense_and_Heterogeneous_Traffic_Using_Weighted_CVPR_2019_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1812.04767.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 50 driving sequences with mix front and top-down view clips annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, object class, time-of-day, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Chandra_2019_CVPR,
    author = "Chandra, Rohan and Bhattacharya, Uttaran and Bera, Aniket and Manocha, Dinesh",
    title = "Traphic: Trajectory Prediction In Dense And Heterogeneous Traffic Using Weighted Interactions",
    booktitle = "CVPR",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=fit></a>
<details close>
<summary><l style="font-size:20px"><strong>Freiburg Imra Testing (FIT)</strong></l> <a href=https://lmb.informatik.uni-freiburg.de/resources/software.php>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Makansi_Multimodal_Future_Localization_and_Emergence_Prediction_for_Objects_in_Egocentric_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2006.04700.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A small-scale driving dataset with automatically generated bounding box track annotations
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Object Class, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Makansi_2020_CVPR,
    author = "Makansi, Osama and Cicek, Ozgun and Buchicchio, Kevin and Brox, Thomas",
    title = "Multimodal Future Localization and Emergence Prediction for Objects in Egocentric View With a Reachability Prior",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=citywalks></a>
<details close>
<summary><l style="font-size:20px"><strong>Citywalks</strong></l> <a href=https://github.com/olly-styles/Multiple-Object-Forecasting>link</a> <a href=https://openaccess.thecvf.com/content_WACV_2020/papers/Styles_Multiple_Object_Forecasting_Predicting_Future_Object_Locations_in_Diverse_Environments_WACV_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1909.11944.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 500+ front-view sequences of pedestrian trajectories annotated at 30fps
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, Tracking ID</li>
<li><em><strong>Task:</strong></em> Walking</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Styles_2020_WACV,
    author = "Styles, Oliver and Sanchez, Victor and Guha, Tanaya",
    title = "Multiple Object Forecasting: Predicting Future Object Locations in Diverse Environments",
    booktitle = "WACV",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=lankershim_boulevard></a>
<details close>
<summary><l style="font-size:20px"><strong>Lankershim Boulevard</strong></l> <a href=https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of vehicle trajectories containing 30 minutes of data recorded at Lankershim Boulevard
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{US_2007_Lankershim,
    author = "of Transportation, U.S. Department",
    title = "Lankershim Boulevard Dataset",
    url = "https://www.fhwa.dot.gov/publications/research/operations/07029/index.cfm",
    year = "2007"
}
</pre>
</details>

</ul></details>
<a name=titan></a>
<details close>
<summary><l style="font-size:20px"><strong>TITAN</strong></l> <a href=https://usa.honda-ri.com/titan>link</a> <a href=https://openaccess.thecvf.com/content_CVPR_2020/papers/Malla_TITAN_Future_Forecast_Using_Action_Priors_CVPR_2020_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/2003.13886.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 700 front-view video clips of driving for pedestrian action and trajectory prediction annotated at 10hz
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Attribute, Object Class, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Malla_2020_CVPR,
    author = "Malla, Srikanth and Dariush, Behzad and Choi, Chiho",
    title = "TITAN: Future Forecast Using Action Priors",
    booktitle = "CVPR",
    year = "2020"
}
</pre>
</details>

</ul></details>
<a name=mitt></a>
<details close>
<summary><l style="font-size:20px"><strong>MIT Trajectory (MITT)</strong></l> <a href=http://www.ee.cuhk.edu.hk/~xgwang/MITtrajsingle.html>link</a> <a href=https://ieeexplore.ieee.org/document/4587718>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 40K+ trajectories recorded from a parking lot for five days
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Grimson_2008_CVPR,
    author = "Grimson, Eric and Wang, Xiaogang and Ng, Gee-Wah and Ma, Keng Teck",
    title = "Trajectory Analysis And Semantic Region Modeling Using A Nonparametric Bayesian Model",
    booktitle = "CVPR",
    year = "2008"
}
</pre>
</details>

</ul></details>
<a name=pems-sf></a>
<details close>
<summary><l style="font-size:20px"><strong>PEMS-SF</strong></l> <a href=https://archive.ics.uci.edu/ml/datasets/PEMS-SF#:~:text=UCI%20Machine%20Learning%20Repository%3A%20PEMS%2DSF%20Data%20Set&text=Abstract%3A%2015%20months%20worth%20of,bay%20area%20freeways%20across%20time.>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset with over 15 months of lane occupancy rate (0 to 1) information for select freeways in California
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Lane Occupancy Rate</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Dua_2019,
    author = "Dua, Dheeru and Graff, Casey",
    year = "2017",
    title = "UCI Machine Learning Repository",
    url = "http://archive.ics.uci.edu/ml",
    institution = "University of California, Irvine, School of Information and Computer Sciences"
}
</pre>
</details>

</ul></details>
<a name=tum_kitchen></a>
<details close>
<summary><l style="font-size:20px"><strong>TUM Kitchen</strong></l> <a href=https://ias.in.tum.de/dokuwiki/software/kitchen-activity-data>link</a> <a href=https://ieeexplore.ieee.org/document/5457583>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of multiview video and multimodal sensor recordings of common activities in a kitchen environment containing 20 sequences
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, RFID, 3D pose, activity label, temporal segment</li>
<li><em><strong>Task:</strong></em> Activity</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Tenorth_2009_ICCVW,
    author = "Tenorth, Moritz and Bandouch, Jan and Beetz, Michael",
    title = "The Tum Kitchen Data Set Of Everyday Manipulation Activities For Motion Tracking And Action Recognition",
    booktitle = "ICCVW",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=fm></a>
<details close>
<summary><l style="font-size:20px"><strong>Future Motion (FM)</strong></l> <a href=https://mcl.korea.ac.kr/~krkim/iccv2019/index.html>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2019/papers/Kim_Instance-Level_Future_Motion_Estimation_in_a_Single_Image_Based_on_ICCV_2019_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of instance-level motions in still images containing 11K+ pedestrian instances along with quantized motion directions and auto-generated bounding boxes
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB (image), bounding box, activity label, motion direction, speed</li>
<li><em><strong>Task:</strong></em> Mix</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Kim_2019_ICCV,
    author = "Kim, Kyung-Rae and Choi, Whan and Koh, Yeong Jun and Jeong, Seong-Gyun and Kim, Chang-Su",
    title = "Instance-Level Future Motion Estimation In A Single Image Based On Ordinal Regression",
    booktitle = "ICCV",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=interaction></a>
<details close>
<summary><l style="font-size:20px"><strong>INTERACTION</strong></l> <a href=https://interaction-dataset.com>link</a> <a href=https://arxiv.org/pdf/1910.03088.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A naturalistic dataset of motions of various traffic road users in a variety of interactive driving scenarios for behavior modeling and prediction
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Map, trajectory</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Zhan_2019_arxiv,
    author = "Zhan, Wei and Sun, Liting and Wang, Di and Shi, Haojie and Clausse, Aubrey and Naumann, Maximilian and Kummerle, Julius and Konigshof, Hendrik and Stiller, Christoph and de La Fortelle, Arnaud and others",
    title = "Interaction Dataset: An International, Adversarial And Cooperative Motion Dataset In Interactive Driving Scenarios With Semantic Maps",
    journal = "arXiv:1910.03088",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=qmul></a>
<details close>
<summary><l style="font-size:20px"><strong>QMUL</strong></l> <a href=http://personal.ie.cuhk.edu.hk/~ccloy/downloads_qmul_junction.html>link</a> <a href=http://www.bmva.org/bmvc/2009/Papers/Paper077/Paper077.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of surveillance footage of road traffic  with 90K+ frames recorded at 25hz
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory</li>
<li><em><strong>Task:</strong></em> Driving, Anomaly</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Loy_2009_BMVC,
    author = "Loy, Chen Change and Xiang, Tao and Gong, Shaogang",
    title = "Modelling Multi-Object Activity By Gaussian Processes",
    booktitle = "BMVC",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=a3d></a>
<details close>
<summary><l style="font-size:20px"><strong>AnAn Accident Detection (A3D)</strong></l> <a href=https://github.com/MoonBlvd/tad-IROS2019>link</a> <a href=https://ieeexplore.ieee.org/document/8967556>paper</a> <a href=https://arxiv.org/pdf/1903.00618.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 1500 video clips of traffic accidents with start and end annotations of events
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, temporal segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yao_2019_IROS,
    author = "Yao, Y. and Xu, M. and Wang, Y. and Crandall, D. J. and Atkins, E. M.",
    booktitle = "IROS",
    title = "Unsupervised Traffic Accident Detection in First-Person Videos",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=pets2009></a>
<details close>
<summary><l style="font-size:20px"><strong>PETS2009</strong></l> <a href=http://www.cvg.reading.ac.uk/PETS2009/a.html>link</a> <a href=https://ieeexplore.ieee.org/document/5399556>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of crowd activities, e.g. walking, running, evacuation (rapid dispersion), local dispersion, recorded from multiple views (up to 8) with different crows densities
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Ferryman_2009_PETS,
    author = "Ferryman, J. and Shahrokni, A.",
    booktitle = "PETS",
    title = "Pets2009: Dataset And Challenge",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=atc></a>
<details close>
<summary><l style="font-size:20px"><strong>ATC</strong></l> <a href=https://irc.atr.jp/crest2010_HRI/ATC_dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/6636027>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of human tracks recorded in a shopping mall for a period of 92 days using 3D range sensors
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, trajectory, attribute, depth</li>
<li><em><strong>Task:</strong></em> Surveillance</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Brvsvcic_2013_HMS,
    author = "Br\vs\vci\'c, Dra{\v{z}}en and Kanda, Takayuki and Ikeda, Tetsushi and Miyashita, Takahiro",
    title = "Person Tracking In Large Public Spaces Using 3-D Range Sensors",
    journal = "Transactions on Human-Machine Systems",
    volume = "43",
    number = "6",
    pages = "522--534",
    year = "2013"
}
</pre>
</details>

</ul></details>
<a name=osu></a>
<details close>
<summary><l style="font-size:20px"><strong>OSU</strong></l> <a href=http://eecs.oregonstate.edu/football/tracking/dataset>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/5206801>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 20 videos, each with approx. 400 frames, of different football matches
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, bounding box, attribute, Tracking ID</li>
<li><em><strong>Task:</strong></em> Sport</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Hess_2009_CVPR,
    author = "Hess, Rob and Fern, Alan",
    title = "Discriminatively Trained Particle Filters For Complex Multi-Object Tracking",
    booktitle = "CVPR",
    year = "2009"
}
</pre>
</details>

</ul></details>
<a name=apolloscape></a>
<details close>
<summary><l style="font-size:20px"><strong>ApolloScape</strong></l> <a href=http://apolloscape.auto/>link</a> <a href=https://ieeexplore.ieee.org/abstract/document/8753527>paper</a> <a href=https://arxiv.org/pdf/1803.06184.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset of 5K vehicle instances, 110K lane segments and 100 mins of sequences for trajectory prediction and tracking annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, LIDAR, 3D Bounding Box, Object Class, Semantic Segment, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>

<summary><strong>Bibtex</strong></summary>
<pre>
@article{Wang_2019_PAMI,
    author = "Wang, Peng and Huang, Xinyu and Cheng, Xinjing and Zhou, Dingfu and Geng, Qichuan and Yang, Ruigang",
    title = "The Apolloscape Open Dataset for Autonomous Driving and its Application",
    journal = "PAMI",
    year = "2019"
}
</pre>
</details>

</ul></details>
<a name=mapillary_vistas></a>
<details close>
<summary><l style="font-size:20px"><strong>Mapillary Vistas</strong></l> <a href=https://www.mapillary.com/dataset/vistas?lat=-12.95419285181812&lng=-39.89899730092117&z=0.6853800234619407&pKey=H1P0sKnFsYu1MkfcjGUZTg>link</a> <a href=https://openaccess.thecvf.com/content_ICCV_2017/papers/Neuhold_The_Mapillary_Vistas_ICCV_2017_paper.pdf>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of street-level images with the corresponding instance and semantic segmentation
</li>
<li>
<em><strong>Applications:</strong></em> Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, Bounding Box, Semantic Segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Neuhold_2017_ICCV,
    author = "Neuhold, Gerhard and Ollmann, Tobias and Rota Bulo, Samuel and Kontschieder, Peter",
    title = "The Mapillary Vistas Dataset for Semantic Understanding of Street Scenes",
    booktitle = "ICCV",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=cityperson></a>
<details close>
<summary><l style="font-size:20px"><strong>CityPersons</strong></l> <a href=https://bitbucket.org/shanshanzhang/citypersons/src/default/>link</a> <a href=https://openaccess.thecvf.com/content_cvpr_2017/papers/Zhang_CityPersons_A_Diverse_CVPR_2017_paper.pdf>paper</a> <a href=https://arxiv.org/pdf/1702.05693.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A subset of Cityscapes dataset with fine-grained annotations for pedestrians and vehicles in additional 20K images with a total of 35K+ bounding boxes for pedestrians
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> Stereo RGB, bounding box, semantic segment</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Shanshan_2017_CVPR,
    Author = "Zhang, Shanshan and Benenson, Rodrigo and Schiele, Bernt",
    Title = "Citypersons: A Diverse Dataset For Pedestrian Detection",
    Booktitle = "CVPR",
    Year = "2017"
}
</pre>
</details>

</ul></details>
<a name=l-cas></a>
<details close>
<summary><l style="font-size:20px"><strong>L-CAS</strong></l> <a href=https://lcas.lincoln.ac.uk/wp/research/data-sets-software/l-cas-3d-point-cloud-people-dataset/>link</a> <a href=https://ieeexplore.ieee.org/document/8202247>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 28K indoor LIDAR scans showing the surroundings of a mobile robot in stationary or moving states
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> LIDAR, 3D bounding box, attribute</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{Yan_2017_IROS,
    author = "Yan, Zhi and Duckett, Tom and Bellotto, Nicola",
    title = "Online Learning For Human Classification In 3D Lidar-Based Tracking",
    booktitle = "IROS",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=sbuki></a>
<details close>
<summary><l style="font-size:20px"><strong>SBU Kinetic Interction (SBUKI)</strong></l> <a href=https://www3.cs.stonybrook.edu/~kyun/research/kinect_interaction/index.html>link</a> <a href=https://ieeexplore.ieee.org/document/6239234>paper</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A dataset of 8 dyadic human interactions, e.g. approaching, departing, pushing, kicking, recorded from 7 participants using a Kinect sensor comprising a total of approx. 300 interactions
</li>
<li>
<em><strong>Applications:</strong></em>Action prediction, Trajectory prediction, Motion prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D pose, activity label</li>
<li><em><strong>Task:</strong></em> Interaction</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@InProceedings{kiwon_2012_CVPR,
    author = "Yun, Kiwon and Honorio, Jean and Chattopadhyay, Debaleena and Berg, Tamara L. and Samaras, Dimitris",
    title = "Two-Person Interaction Detection Using Body-Pose Features And Multiple Instance Learning",
    booktitle = "CVPRW",
    year = "2012"
}
</pre>
</details>

</ul></details>
<a name=strands></a>
<details close>
<summary><l style="font-size:20px"><strong>STRANDS</strong></l> <a href=https://strands.readthedocs.io/en/latest/datasets/>link</a> <a href=https://ieeexplore.ieee.org/document/7948740>paper</a> <a href=https://arxiv.org/pdf/1604.04384.pdf>arxiv</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
An RGBD dataset of objects with corresponding 3D bounding boxes collected using a mobile robot
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGBD, 3D bounding box</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Article{Hawes_2017_RAM,
    author = "Hawes, Nick and Burbridge, Christopher and Jovan, Ferdian and Kunze, Lars and Lacerda, Bruno and Mudrova, Lenka and Young, Jay and Wyatt, Jeremy and Hebesberger, Denise and Kortner, Tobias and others",
    title = "The Strands Project: Long-Term Autonomy In Everyday Environments",
    journal = "IEEE Robotics \\\& Automation Magazine",
    volume = "24",
    number = "3",
    pages = "146--156",
    year = "2017"
}
</pre>
</details>

</ul></details>
<a name=lyft></a>
<details close>
<summary><l style="font-size:20px"><strong>Lyft</strong></l> <a href=https://self-driving.lyft.com/level5/data/>link</a></summary> 
<ul><li>
<em><strong>Summary:</strong></em> 
A driving dataset with 1M+ 3D annotations for perception and 1K+ driving sequences for prediction annotated at 2hz
</li>
<li>
<em><strong>Applications:</strong></em>Trajectory prediction</li>
<li><em><strong>Data type and annotations:</strong></em> RGB, LIDAR, 3D Bounding Box, Object Class, Attribute, Map, Tracking ID</li>
<li><em><strong>Task:</strong></em> Driving</li>
</ul><ul style="margin-left:-15px"><details close>
<summary><strong>Bibtex</strong></summary>
<pre>
@Misc{Lyft_2020,
    author = "Lyft",
    title = "Lyft Level 5 AV Dataset",
    howpublished = "https://self-driving.lyft.com/level5/data/",
    year = "2020"
}
</pre>
</details>
<a href=#top>&uarr; top</a>