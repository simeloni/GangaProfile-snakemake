# GangaProfile-snakemake
This profile configures Snakemake to submit jobs with Ganga

## Deploy profile 
mkdir -p ~/.config/snakemake
cd ~/.config/snakemake
cookiecutter https://github.com/simeloni/GangaProfile-snakemake

You will be asked for the name of the profile.

Then, you can run Snakemake with

snakemake --profile gangasnake ...

so that jobs are submitted to Ganga. 