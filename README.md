Input Variables: The template requires two inputs: context and skills. The context refers to the current situation or environment the character is in, and skills are the abilities or actions the character can perform.

Action Generation: The AI is instructed to generate a list of different action options that the character should take next, considering the context and the skills available.

Action Scoring: Each action generated is then scored on a scale from -1.0 to 1.0, where -1.0 indicates a terrible action, 0 is neutral, and 1.0 is considered the best action possible.

JSON Format: The output is structured in JSON format. This structured format makes it easy to parse and use in a program. The JSON object contains an array of options, each with a chosen skill and associated parameters in JSON. It also has a corresponding scores array providing scores for each action option.

