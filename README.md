# onnx-demo
An introduction to ONNX! Convert your ML models to an agnostic format and take advantage of speedier inference ⚡️.

## Demo
See:

[`onnx-demo.ipynb`](https://github.com/godatadriven/onnx-demo/blob/main/onnx-demo.ipynb)

✨

## Installation
```shell
pip install -r requirements.txt
```

## Demo

Serve the Notebook as slides using:

```shell
jupyter nbconvert onnx-demo.ipynb \
    --to slides \
    --post serve \
    --SlidesExporter.reveal_scroll=True \
    --TagRemovePreprocessor.remove_input_tags={\"remove-input\"}
```

## About
- The reference ONNX.js demo comes from: [dunnkers/neural-network-backdoors](https://github.com/dunnkers/neural-network-backdoors)
- Notebook partially from [sklearn-onnx](https://github.com/onnx/sklearn-onnx/blob/main/docs/tutorial/plot_bbegin_measure_time.py) repo.

Slides built by [Jeroen Overschie](https://jeroenoverschie.nl/).
