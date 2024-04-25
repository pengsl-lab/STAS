

<div align="center">
  <a href="(https://github.com/panliangrui/STAS/blob/main/STAS%20prediction.png)">
    <img src="https://github.com/panliangrui/STAS/blob/main/STAS%20prediction.png" width="600" height="200" />
  </a>

  <h1>STAS(micropapillary, solid nests, single cells)</h1>

  <p>
  Liangrui Pan et al. is a developer helper.
  </p>

  <p>
    <a href="https://github.com/misitebao/yakia/blob/main/LICENSE">
      <img alt="GitHub" src="https://img.shields.io/github/license/misitebao/yakia"/>
    </a>
  </p>

  <!-- <p>
    <a href="#">Installation</a> | 
    <a href="#">Documentation</a> | 
    <a href="#">Twitter</a> | 
    <a href="https://discord.gg/zRC5BfDhEu">Discord</a>
  </p> -->

  <div>
  <strong>
  <samp>

[English](README.md) · [简体中文](README.zh-Hans.md)

  </samp>
  </strong>
  </div>
</div>

# Siamese graph encoder-based image analysis to predict STAS from histopathology images in lung cancer

## Table of Contents

<details>
  <summary>Click me to Open/Close the directory listing</summary>

- [Table of Contents](#table-of-contents)
- [Feature Preprocessing](#Feature-Preprocessing)
  - [Feature Extraction](#Feature-Extraction)
  - [Graph Construction](#Graph-Construction)
- [Train Models](#Train-models)
- [Test Models](#Test-Models)
- [Datastes](#Datastes)
- [Website](#Website)
- [License](#license)

</details>

## Feature Preprocessing

Use the pre-trained model for feature preprocessing and build the spatial topology of WSI.

### Feature Preprocessing

Features extracted based on KimiaNet and CTransPath.
```markdown
python new_cut7.py
```
```markdown
python new_cut7-1.py
```

### Graph Construction

Use KNN (K=9) to construct the spatial topology map.
```markdown
python construct_graph1.py
```

## Train Models
```markdown
train_feature1.py
```
## Test Models

- Best model for five-fold cross validation
  ```markdown
  链接：https://pan.baidu.com/s/11dxmND9ZhEA-o-Hnql6_rg?pwd=l6gh 提取码：l6gh
  ```
- Best model finally tested
  ```markdown
  链接：https://pan.baidu.com/s/1lT8x_ovemj3FXvfjTRjxmA?pwd=516i 提取码：516i 
  ```
- Test the model to obtain predictions.
  ```markdown
  python test_stas.py
  ```

## Datastes

As the data has a privacy protection agreement, only relevant data characteristics are provided.
```markdown
  链接：https://pan.baidu.com/s/1lT8x_ovemj3FXvfjTRjxmA?pwd=516i 提取码：516i 
```

## Website

We welcome you to visit our STAS test platform at http://plr.20210706.xyz:5000/.

## License

If your README conforms to the yakia, you can add a badge to link back to this
specification to help others adopt this readme.
