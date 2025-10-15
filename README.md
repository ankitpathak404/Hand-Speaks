<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center">SIGN-LANGUAGE-RECOGNITION</h1></p>
<p align="center">
	<em><code>❯ uses android smartwatch to detect hand motion using built in accelerometer and gyro and perform sign language detection </code></em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/license/ankitpathak2004/Sign-language-recognition?style=default&logo=opensourceinitiative&logoColor=white&color=0080ff" alt="license">
	<img src="https://img.shields.io/github/last-commit/ankitpathak2004/Sign-language-recognition?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/ankitpathak2004/Sign-language-recognition?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/ankitpathak2004/Sign-language-recognition?style=default&color=0080ff" alt="repo-language-count">
</p>
<p align="center"><!-- default option, no dependency badges. -->
</p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>❯ uses RNN model to detect sign lanuage through an android smartwatch(tested with samsung galaxy watch 7) </code>

---

##  Features

<code>❯ realtime detection </code>
<code>❯ dataset creation </code>
<code>❯ doublepoint touch-sdk integration to take sensor data from watch over bluetooth </code>


---

##  Project Structure

```sh
└── Sign-language-recognition/
    ├── compile_model.py
    ├── dataset_creator.py
    ├── gesture_recognition_model.pkl
    ├── model.h5
    ├── output_predictions.csv
    ├── realtime_test.py
    ├── sensor.csv
    ├── static_test.py
    ├── test.csv
    ├── test1.csv
    └── training.csv
```


###  Project Index
<details open>
	<summary><b><code>SIGN-LANGUAGE-RECOGNITION/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/dharshan17sn/Hand-Speaks/blob/master/compile_model.py'>compile_model.py</a></b></td>
				<td><code>❯ train the model </code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/dharshan17sn/Hand-Speaks/blob/master/dataset_creator.py'>dataset_creator.py</a></b></td>
				<td><code>❯ create dataset </code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/dharshan17sn/Hand-Speaks/blob/master/realtime_test.py'>realtime_test.py</a></b></td>
				<td><code>❯ test model on realtime data </code></td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/dharshan17sn/Hand-Speaks/blob/master/static_test.py'>static_test.py</a></b></td>
				<td><code>❯ test model on static data </code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with Sign-language-recognition, ensure your runtime environment meets the following requirements:

- **Programming Language:** Python
- **SDK:**Double point touch-sdk
- **Libraries:** tensorflow, numpy,pandas, scikit-learn, scipy, keras


###  Installation

Install Sign-language-recognition using one of the following methods:

**Build from source:**

1. Clone the Sign-language-recognition repository:
```sh
git clone https://github.com/ankitpathak404/Hand-Speaks
```

2. Navigate to the project directory:
```sh
cd Sign-language-recognition
```

3. Install the project dependencies:

```sh
pip install tensorflow numpy pandas scikit-learn scipy 
```


###Screenshots
(screenshots\1.png)
(screenshots\2.png)
(screenshots\3.png)
(screenshots\4.png)
(screenshots\5.png)
(screenshots\6.png)
(screenshots\7.png)
(screenshots\8.png)