# A Data-driven Approach to Training & Tuning AWS DeepRacer Reinforcement Learning Models
*How I used Log Analysis to drive experiments to win the F1 DeepRacer ProAm Race*

## What is AWS DeepRacer?
AWS DeepRacer is the world’s first global autonomous racing league, driven by Reinforcement Learning. It is also a fun and easy way for everyone to get started with Machine Learning, regardless of their background. As part of our digital transformation journey at DBS Bank, we are using AWS DeepRacer as a learning platform to equip more than 3000 of our employees with skills in AI/ML by the end of 2020. Thanks to DeepRacer's virtual simulation and training environment, our employees are able to upgrade their skills and pick up new knowledge, even when they are not physically in the office. The ability to run private races also allows us to create our own racing league, where our employees can pit their newfound skills against each other competitively.

## Winning the F1 ProAm Race in May 2020
In May 2020, racers from around the world were given a unique opportunity to test their Machine Learning skills against F1 professionals in the AWS DeepRacer League F1 ProAm Event. We got to train our models on a replica of the F1 Spanish Grand Prix track, and the top 10 racers from the month-long Head-to-Head qualifying race would then face off against F1 professional drivers Daniel Ricciardo and Tatiana Calderon in a Grand Prix-style race.

After a gruelling month of racing, I emerged as the Champion in the F1 ProAm Race, beating fellow racer JJ and the pro F1 drivers to the checkered flag! I attribute my win to having performed more experiments than my fellow competitors throughout that month of racing. Those experiments allowed me to continuously tweak and improve my model leading up to the final race at the end of the month. Behind those experiments, are ideas that arose from data-driven insights through Log Analysis.

## What is Log Analysis?

## Amazon SageMaker Notebook Instances

## Using Amazon SageMaker Notebook Instance for Log Analysis
### Downloading Logs from the AWS DeepRacer Console
### Extracting the Required Log Files
### Creating a Notebook Instance
### Uploading the Log Files for Analysis

## Visualising the Performance Envelope of the Model

## Identifying Potential Model Checkpoints for Race Submission

## Identifying Convergence and Gauging Consistency

## Identifying Inefficiencies in Driving Behaviour

## Identifying Track Sections to Tweak Actions & Rewards
