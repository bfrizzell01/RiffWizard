## RiffWizard – A Customizable Song Recommender for Music Enthusiasts

The modern music streaming ecosystem is filled with recommendation systems —suggested artists, daily playlists, AI-generated mixes— but very few allow users to directly control what is recommended. This can be frustrating for music aficionados who know exactly what they want to listen to and crave hyper-personalized recommendations. For example, someone (like me!) might want **ONLY** Swedish Blackened Death Metal released between 1985 and 1990.

RiffWizard takes a different approach. Instead of making assumptions, it asks for your explicit input first. Using this input, it populates a dataset of songs tailored to your preferences. From there, it recommends tracks and actively incorporates your feedback to continuously refine its suggestions to match your unique taste.

**Disclaimer:** This project is intended as a personal learning exercise in Reinforcement Learning (RL) algorithms, API operations, Music Information Retrieval (MIR), and front-end application development. It is not actively maintained for production use.

RiffWizard is still in the early stages of development, so stay tuned for future updates!


## Setting Up the Environment

This project uses Conda to manage dependencies. To set up the environment, follow these steps:

1. Ensure Conda is installed
   If you don’t have Conda installed, download and install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/).

2. Open a terminal in the project root
   Make sure your terminal’s working directory is the root of this project (where environment.yml is located).

3. Create the environment from `environment.yml`

```bash
   conda env create -f environment.yml
```

   This will create a Conda environment with all the dependencies specified in the YAML file.

4. Activate the environment

```bash
   conda activate riffwizard
```

5. Verify installation

```bash
   conda list
```

   You should see all the packages listed in the environment.

6. Optional: Update the environment
   If the `environment.yml` file is updated in the future:

```bash
   conda env update -f environment.yml --prune
```

   The `--prune` flag removes packages no longer required.
