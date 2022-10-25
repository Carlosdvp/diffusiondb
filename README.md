#DiffusionDB
## Summary

DiffusionDB is a large-scale image generation prompt dataset. Each image in DiffusionDB is generated using the deep learning, text-to-image model known as Stable Diffusion, which was released by StabilityAI in 2022. The dataset maps the textual prompt inputs to the images generated by the Stable Diffusion model. The goal of this dataset is to enable researchers to explore how people write prompts and help design better tooling for prompt engineering. DiffusionDB contains xxx text-to-image mappings which were mined from the Stable Diffusion discord server (https://discord.gg/stablediffusion).

## Supported Tasks and Leaderboards

Enable researchers to explore how people write prompts, design better tooling for prompt engineering
Check section 4 in the paper

## Languages

The class labels in the dataset are in English.

# Dataset Structure

Recommend using `tree` command to get an output

## Data Instances

[TODO]

## Data Fields

[TODO]

## Data Splits

[TODO]

# Dataset Creation

## Curation Rationale

[TODO]
Public discord server
Many images there

## Source Data

### Initial Data Collection and Normalization

Initial data for PromptDB image generation prompt dataset consists of images collected from the Stable Diffusion public discord server. The textual prompts which were input into the Stable Diffusion model to generate the images are retrieved from the image file metadata and mapped to the associated image that was generated. These images were filtered for quality control by human annotators.

### Who are the source language producers?

The images and prompts are retrieved from the Stable Diffusion public discord server.

## Annotations

### Annotation process

The annotation process of collecting PromptDB images and prompts is a three step process:

Mining images generated from the Stable Diffusion model from the Stable Diffusion discord server.
Collecting the candidate image prompt that was used to generate the image from the image file metadata.
Quality control on the candidate images and prompts by human annotators.

### Who are the annotators?

Images are mined from a Stable Diffusion discord server and filtered by human annotators.

## Personal and Sensitive Information

Potential personal information
We provide ways to let users remove prompt and image from our dataset

This dataset does not contain the images of people without their consent.

# Considerations for Using the Data

## Social Impact of Dataset

Check GPT3’s model card and write similar concerns
https://github.com/openai/gpt-3/blob/master/model-card.md
Probably dall-e is more useful
https://github.com/openai/dalle-2-preview/blob/main/system-card.md

## Discussion of Biases

See above

[TODO]

## Other Known Limitations

See above
Might include sensitive information

# Additional Information

## Authors

Evan Montoya, Jay Wang, David Munechika, Alex Yang, Ben Hoover, Polo Chau

## Licensing Information

In exchange for permission to use the PromptDB database (the "Database") at Georgia Institute of Technology, Researcher hereby agrees to the following terms and conditions:

Researcher shall use the Database only for non-commercial research and educational purposes.
Georgia Institute of Technology makes no representations or warranties regarding the Database, including but not limited to warranties of non-infringement or fitness for a particular purpose.
Researcher accepts full responsibility for his or her use of the Database and shall defend and indemnify the PromptDB team, Georgia Institute of Technology, including their employees, Trustees, officers and agents, against any and all claims arising from Researcher's use of the Database, including but not limited to Researcher's use of any copies of copyrighted images that he or she may create from the Database.
Researcher may provide research associates and colleagues with access to the Database provided that they first agree to be bound by these terms and conditions.
Georgia Institute of Technology reserves the right to terminate Researcher's access to the Database at any time.
If Researcher is employed by a for-profit, commercial entity, Researcher's employer shall also be bound by these terms and conditions, and Researcher hereby represents that he or she is fully authorized to enter into this agreement on behalf of such employer.
The law of the State of Georgia shall apply to all disputes under this agreement.

## Citation Information

[TODO]

## Contributions

Thanks to [@github-username](https://github.com/<github-username>) for adding this dataset.
