# Welcome to Jülich Data Challenges

## About Us

[Jülich Challenges](https://data-challenges.fz-juelich.de/) is a platform for scientific data challenges initiated by Forschungszentrum Jülich. We host data challenges on the edge of scientific discovery promoting Jülich's unique scientific data and according research problems.

Jülich Challenges target ML researchers, or traditional image analysts, looking for interesting data to work on, that allow quick results for fast publications. As benefits for FZJ we expect to attract ML and AI specialists to our unique data sets, scientific questions and therewith to provide solutions for Jülich-specific research questions. This comes with an increased visibility in the fields of ML and AI - across domains and within the ML communities.

## Schedule

The hackathon is scheduled for 4 days as a fully virtual event. The first day is dedicated to the introduction of the platform and available challenges as well as aforementioned introduction into Jülich's Supercomputers. You will form teams for collaborative coding, ideally mixed between different working groups or institutes, and pick a challenge you'd like to work on. Of course you can join as a team as well.  The remaining time will be used for working on the challenges. At the end of the week we will hopefully have models that solve our challenges up to a certain performance and therewith proof their feasibility but also its challenging character.

## How to host a challenge on Jülich Data Challenge platform
1. Setup challenge configuration <br />
    We have created a sample challenge configuration that we recommend you to use to get started.

2. Edit challenge configuration <br />
    Open `challenge_config.yml` from the repository that you cloned in step-1. This file defines all the different settings of your challenge such as start date, end date, number of phases, and submission limits etc. Edit this file based on your requirement.

    You can refer to [link](https://evalai.readthedocs.io/en/latest/configuration.html) to edit the file based on your requirement.

3. Edit evaluation script <br />
    Next step is to edit the challenge evaluation script that decides what metrics the submissions are going to be evaluated on for different phases.

    You can refer to [link](https://evalai.readthedocs.io/en/latest/evaluation_scripts.html) to edit the file based on your requirement.

4. Edit challenge HTML templates <br />
    Now, you just need to update the HTML templates in the templates/ directory of the bundle that you cloned.

5. Upload configuration on Jülich Data Challenge platform <br />
    Finally run the `./run.sh` script in the bundle. It will generate a challenge_config.zip file that contains all the details related to the challenge. Now, visit EvalAI - Host challenge page and select/create a challenge host team. Then upload the `challenge_config.zip`.

## How to participate in Jülich Data Challenge
1. Visit [Jülich Challenges](https://data-challenges.fz-juelich.de/)
![alt text](../images/6a.png)

2. Sign up or Log in
Sign Up and fill in your credentials or log in if you have already registered.
![alt text](../images/5a.png)

After signing up you would be on the dashboard page.
![alt text](../images/4a.png)

3. Choose challenge
Then, go to challenges section and choose an active challenge.
![alt text](../images/3a.png)

4. Challenge Page
After reading the challenge instructions on the challenge page, you can participate in the challenge.
![alt text](../images/2a.png)

5. Create Participant Team
Create a participant team if there isn’t any or you can select from the existing ones. Click on ‘Participate’ tab after selecting a team.
![alt text](../images/1a.png)



## How to submit to a Jülich Data Challenge
You can go to the [link](https://storage.data-challenges.fz-juelich.de/) to download the files associated with the challenge. Each Jülich Data challenge comes with a zip files containing the datasets and information about the challenge and a Jupyter Notebook.

    ### Challenge Layout

    data_public_leaderboard_phase.tar.gz    #
    notebook.ipynb    # The notebook file.

After generating the `submision.csv` file, you can simply upload the csv file to the challenge frontend. 
![alt text](../images/2b.png)
![alt text](../images/1b.png)
