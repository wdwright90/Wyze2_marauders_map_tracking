# Deep SORT with Pytorch

## Demo
1. Clone this repository: `git clone https://github.com/wdwright90/Wyze2_marauders_map.git`
2. Install detectron2: `cd /content/Wyze2_marauders_map/Detection_mode` then `pip install detectron2 -f https://dl.fbaipublicfiles.com/detectron2/wheels/cu101/torch1.7/index.html`
3. Install deepsort requirements: `cd /content/Wyze2_marauders_map/deep_sort` then `pip install -r requirement.txt`
4. Run the demo: `python detectron2_deepsort.py VIDEO_PATH('Wyze2_marauders_map/data/cam0_seq0.mp4')`. If you want to add more videos and integrate them in one windows use `_next`.

## Citing DeepSORT

If you find this repo useful in your research, please consider citing the following papers:

    @inproceedings{Wojke2017simple,
      title={Simple Online and Realtime Tracking with a Deep Association Metric},
      author={Wojke, Nicolai and Bewley, Alex and Paulus, Dietrich},
      booktitle={2017 IEEE International Conference on Image Processing (ICIP)},
      year={2017},
      pages={3645--3649},
      organization={IEEE},
      doi={10.1109/ICIP.2017.8296962}
    }

    @inproceedings{Wojke2018deep,
      title={Deep Cosine Metric Learning for Person Re-identification},
      author={Wojke, Nicolai and Bewley, Alex},
      booktitle={2018 IEEE Winter Conference on Applications of Computer Vision (WACV)},
      year={2018},
      pages={748--756},
      organization={IEEE},
      doi={10.1109/WACV.2018.00087}
    }
