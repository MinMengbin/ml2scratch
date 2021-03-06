# ML2Scratch(Scratch2ML)

ML2Scratch connects Machine Learning(TensorFlow.js) to ScratchX.

*Read this in other languages: [English](README.md), [日本語](README.ja.md).*

## Requirements

- Chrome browser
- macOS High Sierra(10.13.3) or Windows 10(1607 OS build 14393.576)

## Demo Movie

https://www.youtube.com/watch?v=DkH1hwc-Gb4

## Setup

1. Install Node.js from https://nodejs.org/ja/.

2. Download the source code of ML2Scratch from https://github.com/champierre/ml2scratch.

3. Unzip the ZIP file.

	```
	% unzip ml2scratch-master.zip
	```

4. Install required packages.

	```
	% mv ml2scratch-master ml2scratch
	% cd ml2scratch/helper
	% npm install
	```

## Setup on Windows 10

- Please use Windows PowerShell.

![PowerShell](https://user-images.githubusercontent.com/10215/38457066-c3aae2aa-3ac6-11e8-8e08-800a08926a01.PNG)

## How to use

1. Start ML2Scratch Helper.

	```
	% node ml2scratch_helper.js
	```

2. Open [MLScratch](https://champierre.github.io/ml2scratch/) page.

3. Open [ScratchX](http://scratchx.org/?url=https://champierre.github.io/ml2scratch/ml2scratch.js) page with the extension loaded. If you cannot open ScratchX with the extension loaded, open [ScratchX](http://scratchx.org/) page, click "Open Extension URL" and paste the following URL, then click "Open".

	```
	https://champierre.github.io/ml2scratch/ml2scratch.js
	```

4. On Warning dialog of ScratchX, click "I understand, continue".

## Reference

- https://js.tensorflow.org/
- https://github.com/googlecreativelab/teachable-machine-boilerplate
