# COVID-19 Detection from Chest X-Ray Images Using Deep Learning

## Quick Links
1. COVID-19 Radiography Database: https://www.kaggle.com/tawsifurrahman/covid19-radiography-database

## Team Member
* Syachrul Qolbi Nur Septi
* Raihan B.
* Julio Fachrel

## Table of Contents
1. [Requirements](#requirements) to install on your system
2. How to [generate COVIDx dataset](docs/COVIDx.md) Steps for [training, evaluation and inference](docs/train_eval_inference.md) of COVIDNet
3. [Results](#results)
4. [Links to google colab](docs/models.md)

## Requirements

The main requirements are listed below:

* Tested with Tensorflow 2.5.0
* Python 3.6
* Numpy
* Matplotlib

Additional requirements to generate dataset:

* Shutil
* Pandas
* Patoolib

## Results
These are the final results for the models.

### Covid Model (Positive/Negative)
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Result</th>
  </tr>
  <tr>
    <td class="tg-7btt">Accuracy</td>
    <td class="tg-7btt">Val_Accuracy</td>
  </tr>
  <tr>
    <td class="tg-c3ow">99.02</td>
    <td class="tg-c3ow">94.18</td>
  </tr>
</table></div>

### Covid Model (Normal/Pneumonia/COVID)
<div class="tg-wrap"><table class="tg">
  <tr>
    <th class="tg-7btt" colspan="3">Result</th>
  </tr>
  <tr>
    <td class="tg-7btt">Accuracy</td>
    <td class="tg-7btt">Val_Accuracy</td>
  </tr>
  <tr>
    <td class="tg-c3ow">-</td>
    <td class="tg-c3ow">-</td>
  </tr>
</table></div>