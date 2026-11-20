# Violence Detection

## Data
This project uses the Real Life Violence Situations (RLVS) dataset from Kaggle.
The data is not stored in this repo.

To download it:
1. Create a Kaggle account and generate an API token (Kaggle > Settings > API).
2. Save the token as an environment variable or in ~/.kaggle/access_token.
3. Run:

    pip install --upgrade kaggle
    kaggle datasets download -d mohamedmustafa/real-life-violence-situations-dataset -p data --unzip

## Citation
Soliman et al., "Violence Recognition from Videos using Deep Learning Techniques", 2019.
