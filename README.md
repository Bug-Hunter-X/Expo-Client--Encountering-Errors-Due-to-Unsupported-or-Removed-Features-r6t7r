# Expo Client: Unsupported Feature Errors

This repository demonstrates a common yet elusive error in Expo applications: errors caused by accessing unsupported or removed features within the Expo client.  The error messages are often vague, making debugging difficult.  This example showcases how to identify and potentially mitigate this issue. 

## Bug Description:

Attempting to use a feature not yet implemented or removed from the Expo client results in cryptic error messages. This primarily affects developers using features still in beta or those recently removed due to updates.

## Solution:

The core solution involves carefully reviewing the Expo documentation to ensure that the feature you are employing is currently supported in your Expo SDK version.  If it's not, alternative implementations or techniques might be required.

## How to Reproduce:

1. Install the packages mentioned in `expoBug.js`. 
2. Run the project and you should see the error which indicates an unsupported functionality.