# High-Frequency Cybersickness Prediction Using Deep Learning Techniques With Eye-Related Indices

This repository contains the LaTeX source files for the paper "High-Frequency Cybersickness Prediction Using Deep Learning Techniques With Eye-Related Indices" published in IEEE Access. The full paper can be accessed [here](https://ieeexplore.ieee.org/document/10239343).

## Co-Authors
- **Peerawat Pannattee** - Graduate School of Systems Design, Tokyo Metropolitan University, Tokyo 191-0065, Japan.
- **Yasushi Ikei** - Graduate School of Information Science and Technology, The University of Tokyo, Tokyo 113-8656, Japan.
- **Nobuyuki Nishiuchi** - Graduate School of Systems Design, Tokyo Metropolitan University, Tokyo 191-0065, Japan.
- **Vibol Yem** - Graduate School of Science and Technology, Degree Program in Systems and Information Engineering, University of Tsukuba, Ibaraki 305-8573, Japan.

## Abstract
Cybersickness is a growing concern in the field of virtual reality (VR). It is characterized by symptoms, such as headache, sweating, disorientation, and nausea. These symptoms can considerably hinder the users’ immersive experience in VR environments, leading to a pressing need for effective solutions to combat cybersickness. In this study, we aim to tackle cybersickness by presenting a novel high-frequency approach for detecting the timing at which users experience cybersickness. Our approach uses 1-, 5-, or 10-s time-series eye-related indices processed by deep learning algorithms to predict cybersickness severity. In five-fold cross-validation, we achieved 71.09% accuracy in classifying four classes of cybersickness severity when individuals were not distinguished. Furthermore, with individualized cross-validation, we achieved an accuracy of up to approximately 80%. Our approach outperforms other cybersickness prediction studies as it provides the highest frequency in predicting cybersickness. It is anticipated that our approach will be valuable not only for immediate evaluation by researchers investigating cybersickness mitigation but also for early detection and notification of users experiencing cybersickness symptoms. By predicting cybersickness, our approach has the potential to promote the future advancement of VR technology.

## Repository Contents
- `final_manuscript.tex`: The main LaTeX file containing the structure of the paper.
- `final_manuscript.pdf`: The compiled PDF version of the paper.
- `reference_shimada.bib`: The bibliography file with all the references used.
- `IEEEtran.cls`: The IEEE LaTeX class file used for formatting.

## How to Compile
To compile the LaTeX source files into a PDF, it is recommended to use Overleaf with the `pdflatex` compiler. Follow these steps:

1. Clone the repository:
    If you haven't already, clone the repository to your local machine.
    ```sh
    git clone git@github.com:shwg8986/Cybersickness-Prediction.git
    cd Cybersickness-Prediction
    ```

2. Compress the Repository Contents:
    Use a terminal command or a file compression tool to zip the contents.

    In a terminal, you can use the zip command as follows:
    ```sh
    zip -r Cybersickness-Prediction.zip .
    ```
    This command will create a file named Cybersickness-Prediction.zip containing all the files and folders in the current directory.

3. Upload to Overleaf (or any LaTeX editor of your choice):
    - Go to Overleaf.
    - Create a new project or open an existing one.
    - Click on the "Upload" button in the top menu.
    - Select "Upload a .zip file".
    - Choose the Cybersickness-Prediction.zip file you just created and upload it.

4. Compile the `final_manuscript.tex` file using `pdflatex`.
    The output PDF will be generated in the root directory of the repository.

