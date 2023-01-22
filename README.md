# Overview
Gym app that gives the gym the following features:
  - accounts for users
  - scheduling for massage, trainers etc
  - training programs on demand
  - trainer interactions
  - leaderboards etc

## User
  - can be a member of gym and get bennies from app
  - used to sign in to gym
  - comunicates to trainer with app ( better looking, more understandable )
  - can select free list of programs based on goals (powerlifting, weight loss etc)
    -  gives daily program to user for workouts
  - record and send video to trainer with app (out of scope but may eventually be a feature)
  - Good for new gym goes with free basic programs, along with long time veterans
  - personalize programs cost money for user.
  - can schedule massages etc
  - get ticket purchases for events ( arnold classic )


## Gym
  - can hire less trainers
  - can be re skinned to personalize app to gym
  - doesnt pay for IT
  - can have 'high score'/leaderboard for users
  - they get more traffic in app, meaning more engagement more likely to spend


## Trainers
  - can work remote
  - easily create new programs for people
  - can cover more users / hr


## needs
  - trainer to create programs
    - Need a trainer who can do many programs and different styles 
  - analyst for creating possible ML models to create programs for users
     - This could be another paid sub 
     - good metric analysis and dashboard for progress
     
## Technolgies
- db 
  - Postgres
- app lang
  - python
-infra
  - aws
  - terraform
    - will allow us to easily spin up infra for new gyms, with minimal effort
  - kubernetes
