# Forensic DNA Bayesian Inference

## Project Overview
This project implements a forensic DNA profile comparison system using Bayesian inference to calculate the probability of DNA matching between evidence and suspects. It applies likelihood ratios and Bayesian probability formulas to provide rigorous statistical evaluation of DNA evidence. The system supports multiple forensic scenarios including partial profiles and mixed DNA samples.

## Features
- Bayesian inference for DNA match probability calculation
- Likelihood ratio computation for forensic evidence interpretation
- Python-based implementation with both GUI (Tkinter) and Command Line Interface (CLI)
- Interactive DNA profile input with multiple loci and allele handling
- Real-time probability calculation and visual output
- Support for partial profiles and mixed samples
- Scenario-based forensic analysis suitable for criminal investigations, paternity testing, and missing person identification

## Technologies Used
- Programming Language: Python 3
- Key Libraries: NumPy, Math, Tkinter
- Data Structures: Dictionaries and Lists to represent DNA loci and alleles
- Version Control: GitHub

## Installation
1. Clone the repository:
git clone https://github.com/DivyanshiSingh07-hub/FORENSIC-DNA-BAYESIAN-INFERENCE.git

text
2. Navigate to the project directory:
cd FORENSIC-DNA-BAYESIAN-INFERENCE

text
3. Install required Python libraries:
pip install numpy

text

## Usage
- Run the GUI version:
python gui_main.py

text
- Run the CLI version:
python cli_main.py

text
- Follow on-screen instructions to input DNA profiles and obtain forensic match probabilities.


## Testing
- Automated and manual testing have been completed.
- All core functions have been unit tested.
- Input validation and edge cases such as partial profiles were tested to ensure accuracy.
- Test results: All tests passed.

## Future Enhancements
- Batch processing for multiple suspects
- Support for additional DNA loci and population genetics models
- Integration with forensic DNA databases
- Enhanced report generation for legal documentation
