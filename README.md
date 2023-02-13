# Audio Classification using Image Classification Techniques
## Introduction
The goal of this project is to classify audio signals into different categories using image classification techniques. This can be achieved by converting audio signals into spectrograms, which are visual representations of audio frequencies, and then applying image classification algorithms to the spectrograms.

## Methodology
### Preprocessing:

The first step in this project is to preprocess the audio signals. This includes converting the audio signals into spectrograms, which are two-dimensional visual representations of audio frequencies over time.
The spectrograms can be generated using the Short-Time Fourier Transform (STFT).

![J01Z8](https://user-images.githubusercontent.com/75095471/218457737-9db09f82-4d0c-4758-bb48-86abe1eecceb.jpg)

## Image Classification:

After preprocessing the audio signals, the next step is to apply image classification algorithms to the spectrograms.
Several image classification algorithms, such as Convolutional Neural Networks (CNNs), can be used to classify the spectrograms into different categories.
The model should be trained on a large dataset of audio signals and spectrograms, and then evaluated on a separate test dataset.
## Results:
<table>
  <tr>
    <th>nameOfDevice</th>
    <th>precision</th>
    <th>recall</th>
    <th>accuracy</th>
  </tr>
  <tr>
    <td>-6_dB_fan/id_00'</td>
    <td>93</td>
    <td>96</td>
    <td>92</td>
  </tr>
  <tr>
    <td>-6_dB_fan/id_02'</td>
    <td>97</td>
    <td>100</td>
    <td>97</td>
  </tr>
  <tr>
    <td>-6_dB_fan/id_04'</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>-6_dB_fan/id_06'</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>-6_dB_pump/id_00'</td>
    <td>98</td>
    <td>98</td>
    <td>96</td>
  </tr>
  <tr>
    <td>-6_dB_pump/id_02'</td>
    <td>97</td>
    <td>100</td>
    <td>97</td>
  </tr>
  <tr>
    <td>-6_dB_pump/id_04'</td>
    <td>99</td>
    <td>94</td>
    <td>94</td>
  </tr>
  <tr>
    <td>-6_dB_pump/id_06'</td>
    <td>99</td>
    <td>94</td>
    <td>94</td>
  </tr>
  <tr>
    <td>-6_dB_slider/id_00'</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>-6_dB_slider/id_02'</td>
    <td>99</td>
    <td>100</td>
    <td>99</td>
  </tr>
  <tr>
    <td>-6_dB_slider/id_04'</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>-6_dB_slider/id_06'</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  <tr>
    <td>-6_dB_valve/id_00</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
   <tr>
    <td>-6_dB_valve/id_02</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
   <tr>
    <td>-6_dB_valve/id_04</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
   <tr>
    <td>-6_dB_valve/id_06</td>
    <td>100</td>
    <td>100</td>
    <td>100</td>
  </tr>
  </table>

## Conclusion
In conclusion, audio classification using image classification techniques has proven to be a successful method for classifying audio signals into different categories. By converting audio signals into spectrograms and then applying image classification algorithms, we can achieve high accuracy in audio classification. This method can be applied in various fields such as speech recognition, music classification, and sound event detection.
