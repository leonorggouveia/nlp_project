[README.md](https://github.com/user-attachments/files/24652225/README.md)
Truth, Lies and Reasoning Machines - Natural Language Processing
================
Leonor Gonçalves Gouveia
2026-01-15

## Dataset

This project utilizes the **HotpotQA** dataset
(<https://github.com/hotpotqa/hotpot>), specifically the dev set in the
distractor setting.

The code is designed to fetch the dataset automatically via the
following URL:
<http://curtis.ml.cmu.edu/datasets/hotpot/hotpot_dev_distractor_v1.json>

## How to run

1.  Go to [colab.research.google.com](colab.research.google.com).

2.  Ensure the runtime is set to **T4 GPU** (Runtime \> Change runtime
    type \> T4 GPU).

3.  Use the file upload icon to upload the `nlp_project.ipynb`.

4.  Run the following command in a cell to install the required
    dependencies:

        !pip install torch transformers pandas matplotlib seaborn requests

5.  Run the script.
