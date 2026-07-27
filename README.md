<h2 align="center">S²DB-Net: Satellite-Street Dual-Branch Network for Urban Sidewalk Detection</h2>
<p align="center">
  <b>ISPRS Journal of Photogrammetry and Remote Sensing</b> | 2026
  <br>
  <a href="https://openreview.net/pdf?id=OtLC2JNGZf">[Paper]</a> |
  <a href="https://github.com/EdgedEnd/S2DB-Net">[Code]</a> |
  <a href="https://huggingface.co/EdgedEnd/S2DB-Net">[🤗 Model & Dataset]</a>
</p>

![Architecture](figs/S2DB-Net.png)

## 📣 News

- **[2026/7/22]** Our paper is now officially online in ISPRS Journal of Photogrammetry and Remote Sensing.

## 📝 Abstract

Urban sidewalks are essential infrastructure for pedestrian mobility, and accurate acquisition of sidewalk geographic data is crucial for sustainable urban development. However, existing sidewalk detection methods based on satellite images commonly suffer from occlusions caused by street trees, buildings, and other urban structures, leading to discontinuities and omissions in the detection results. To address this issue, we propose S²DB-Net, a satellite and street-view dual-branch network informed by cross-view imaging geometry and geospatial alignment mechanism for urban sidewalk detection. Considering the imaging geometry differences between street-view and satellite images, we introduce an Implicit Perspective Transformation (IPT) module that transforms features from the street-view perspective to a bird's eye view (BEV) perspective via feature sampling and aggregation, aiming to align the feature spatial distributions across different perspectives and enhance fusion performance. Furthermore, leveraging the inherent geographic range consistency between perspectives, we design an auxiliary loss supervision structure, which mitigates the model's over-reliance on a single branch during the training process.

## 🤝 Citation

If you find this work useful, please cite our paper:

```bibtex
@article{lin2026urban,
  title={Urban sidewalk detection via a cross-view joint segmentation method using satellite and street-view imagery},
  author={Lin, Yi and Li, Weijia and Yu, Jinhua and Ye, Junyan and He, Jun and Zhang, Xiang},
  journal={ISPRS Journal of Photogrammetry and Remote Sensing},
  volume={240},
  pages={16--30},
  year={2026},
  publisher={Elsevier}
}
```

## 📄 License

This project is released under the [MIT License](LICENSE).
