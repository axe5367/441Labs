# Prompt Engineering Process

### Attempt 1
#### Intention
>What is the improvement that you intend to make?

    This was the first attempt, which had a temperature of 2 and max tokens of 100. The system prompt tells the model that
    it has human-like emotions and to express them somehow. Also, I simply told it that it is a Dungeons and Dragons Dungeon Master, with no additional detail. I had the conversation initialize with a simple Hello message to the model.

### Attempt 2
#### Intention
>What is the improvement that you intend to make?

    For this second attempt, I gave the model much more specfic information about the world that it is putting the user in as a DM, as well as a particular way in which the user's character is intended to interact with the DM and their stats/inventory. This added detail is intended to put the model on a more particular world-building path and create a more unique experience. 
#### Action/Change
>Why do you think this action/change will improve the agent?

    As seen by the first attempt, no extra detail leads the model to create a more traditional D&D environment without any real uniqueness to it. Being more specific about the world I want the DM to describe will certainly create a better outcome than leaving it entirely up to the model. 
#### Result
>What was the result?

    As expected, the model told things from an AI's perspective in the cyberpunk world I asked it to describe. One main difference from the first attempt is that the model didn't go right into character creation for the user, instead asking what the user wants to do next based on the initial location/surroundings.
#### Reflection/Analysis of the result. 
>Why do you think it did or did not work?

    I would say the changes did work because the model directly followed all of the instructions given in the system prompt. Since I didn't tell it how to initiate the user's gameplay, such as by taking actions in the world first or creating a character, I am not really surprised that this difference is shown between these two attempts. Going forward, I plan on giving it much more extensive explanation in the system prompt for how to initiate the gameplay and what kind of options it can give the user.