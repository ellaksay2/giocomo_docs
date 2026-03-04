# Headfixed Training Protocol

(for Ella’s reference)

## Before Training

- Citric acid restriction
    - 2.5% citric acid
    - use scale + graduated cylinder + water from animal facility
    - 90mL/3 bottles 22.5g citric acid (1 bottle ~7.5g citric acid)
    - use special water card from animal facility
- Water restriction
    - Feed 0.8mL water each day
    - Use water restriction card from animal facility
    - weigh mice + record on card each day
- Sucrose water
    - 60mL bottle filled with water from animal facility or DI water from room
    - 5% sucrose ~3g sucrose in 60mL water
    - add directly from scale using weigh boat and shake to dissolve

## Handling (1-2 days)

- 1-2 days handling animal post-surgery
- Weigh animal
- Feed 0.8mL water while holding animal
- Let smell the wheel + put water on lickport to habituate to the rig

## Headfixed habituation (1-2 days)

- Headfix animal to the rig
- Feed water while animal is headfixed

## Cleaning lickport

- Open Unity “Clean” scene
- Check make sure valve is turned ‘open’ towards the reservoir
- Press start
- Use reservoir pump to push water through + catch water out of lickport with beaker

## Lickport training (2-3 days)

- Weigh animal
- Make sure 2mL of water in the vertical syringe (use reservoir to refill if not)
    - adjust height of water to control output flow
- Open Unity “lickport training” scene
    - First couple days set “Auto-reward” to On
    - Change mouse ID name
    - Max rewards = 200
- Headfix animal to rig
- Put lickport near head (**careful of turning the correct knobs to prevent breakage**)
- Press start in Unity
- Use secondary mouse (of the computer variety) to click screen a couple times and deliver reward
- Click “G” for Go!
- Leave animal on rig until stops licking or gets max rewards
- Record number of rewards
- Water animal with remaining water up until 0.8mL

## Running training (??? days)

- Weigh animal
- Make sure 2mL of water in the vertical syringe (use reservoir to refill if not)
    - adjust height of water to control output flow
- Open Unity “run training” scene
    - add name
    - MRD = 50 cm, MaxTrainingDist = 300 cm
    - 150 mL is max rew on Thorlabs rig, 200 mL on NLW
- Headfix animal to rig
- Put lickport near head
- Press start in Unity
- Use secondary mouse (of the computer variety) to click screen a couple times and deliver reward
- Click “G” for Go!
- Troubleshooting:
    - if mouse is not running, can help by moving wheel
    - if mouse is not licking, deliver manual rewards? (is this right IDK)
- Record number of laps + number of rewards

post-running training: cue-less environment

- Trouble Shooting
    - Water not properly calibrated (dispense too much/too little)
        - raise the syringe for more water flow, lower for less
        - Using running training and manually click 50 rewards, check for 0.2mL of water dispensed
        - Adjust accordingly
    -