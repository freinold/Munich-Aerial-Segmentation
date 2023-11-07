# Munich-Aerial-Segmentation

## Data Sources

Regions: Stadt München & Landkreis Fürstenfeldbruck

- [Digitales Orthophoto 40cm (DOP40)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dop40)
- [Digitales Geländemodell 1m (DGM1)](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=dgm1)
- [Laserdaten](https://geodaten.bayern.de/opengeodata/OpenDataDetail.html?pn=laserdaten)
- [OpenData Portal München](https://geoportal.muenchen.de/portal/opendata/)
- [OSM Anfrage-Engine Overpass Turbo](https://overpass-turbo.eu/)

## Ideas

1. Segment whole image with [Segment Anything Model](https://segment-anything.com/), then label parts with CLIP-like model (https://github.com/facebookresearch/MetaCLIP) trained on categories of aerial images
    - inspired by Grounded SAM (https://github.com/IDEA-Research/Grounded-Segment-Anything), example demo: https://huggingface.co/spaces/SkalskiP/SAM_and_MetaCLIP
2. Combine image channels with ground model data and lidar data -> RGB + ground height + lidar height to direct segmentation with ViT, CNN or RNN (needs labeling!)

## Datasets

- [UAE Semantic segmentation of aerial imagery](https://www.kaggle.com/datasets/humansintheloop/semantic-segmentation-of-aerial-imagery/data)
- [STPLS3D](https://paperswithcode.com/dataset/stpls3d)
- [Urban Modelling and Semantic Labelling Benchmark 	Urban Modelling and Semantic Labelling Benchmark](https://www.isprs.org/education/benchmarks/UrbanSemLab/default.aspx)
- [DALES (DALES: A Large-scale Aerial LiDAR Data Set for Semantic Segmentation) ](https://paperswithcode.com/dataset/dales)
- [ AeroScapes aerial semantic segmentation](https://github.com/ishann/aeroscapes)

## Methods

- [Segment-before-Detect: Vehicle Detection and Classification through Semantic Segmentation of Aerial Images](https://www.mdpi.com/2072-4292/9/4/368#)
- [https://github.com/Junjue-Wang/LoveDA](https://github.com/Junjue-Wang/LoveDA)
