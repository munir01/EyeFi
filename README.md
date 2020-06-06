# EyeFi: Fast Human Identification Through Vision and WiFi-based Trajectory Matching

This is the official repository for the EyeFi research project. It provides the dataset for the following reseach paper:

```
@inproceedings{eyefi2020,
  title={EyeFi: Fast Human Identification Through Vision and WiFi-based Trajectory Matching},
  author={Fang, Shiwei and Islam, Tamzeed and Munir, Sirajum and Nirjon, Shahriar},
  booktitle={IEEE International Conference on Distributed Computing in Sensor Systems (DCOSS)},
  year={2020},
  organization={IEEE}
}
```

### Abstract
Human sensing, motion trajectory estimation, and identification are central to a wide range of applications in many domains such as retail stores, surveillance, public safety, public address, smart homes and cities, and access control. Existing solutions either require facial recognition or installation and maintenance of multiple units, or they lack long-term re-identification capability. In this paper, we propose a novel system -- called EyeFi -- that combines WiFi and camera on a standalone device to overcome these limitations. EyeFi integrates a WiFi chipset to an overhead camera and fuses motion trajectories obtained from both vision and RF modalities to identify individuals. In order to do that, EyeFi uses a student-teacher model to train a neural network to estimate the Angle of Arrival (AoA) of WiFi packets from the CSI values. Based on extensive evaluation using real-world data, we observe that EyeFi improves WiFi CSI based AoA estimation accuracy by more than 30% and offers 3,800 times computational speed over the state-of-the-art solution. In a real-world environment, EyeFi's accuracy of person identification averages  75%  when the number of people varies from 2 to 10.    


Please read the research paper to know more about the project.

# Dataset download
The dataset can be downloaded from here: https://zenodo.org/record/3882104. 
