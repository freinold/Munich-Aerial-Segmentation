# Munich-Aerial-Segmentation

## Data Sources

Regions: Stadt München & Landkreis Fürstenfeldbruck

- [Digitales Orthophoto 40cm (DOP40)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dop40)
- [Digitales Geländemodell 1m (DGM1)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dgm1)
- [Laserdaten](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)

## Ideas

1. Segment whole image with Segment Anything Model, then label parts with CLIP-like model trained on categories of aerial images
2. Combine image segmentation with ground model data and lidar data to directly segment (needs labeling!)

## Datasets

- [UAE Semantic segmentation of aerial imagery](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery/data)
- [STPLS3D](https://paperswithcode.com/dataset/stpls3d)
- [Urban Modelling and Semantic Labelling Benchmark 	Urban Modelling and Semantic Labelling Benchmark](https://www.isprs.org/education/benchmarks/UrbanSemLab/default.aspx)
- [DALES (DALES: A Large-scale Aerial LiDAR Data Set for Semantic Segmentation) ](https://paperswithcode.com/dataset/dales)
- [ AeroScapes aerial semantic segmentation](https://github.com/ishann/aeroscapes)

## Methods

- [Segment-before-Detect: Vehicle Detection and Classification through Semantic Segmentation of Aerial Images](https://www.mdpi.com/2072-4292/9/4/368#)
- [https://github.com/Junjue-Wang/LoveDA](https://github.com/Junjue-Wang/LoveDA)
