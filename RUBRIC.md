# Rubric
Use this project rubric to understand and assess the project criteria.

## Segment the subject

### Criteria	
Demonstrate proficiency in loading and using the Segment Anything Model (SAM) to segment objects

### Submission Requirements
The students has completed the SAM section of the notebook by filling in all the "# YOUR CODE HERE" sections of the code. The output of the last cell on the section looks like the example provided just above that cell: the car area is white and the background area is green

## Inpainting

### Criteria
The student demonstrate proficiency in loading a pretrained AutoPipelineForInpainting from the diffusers library

### Submission Requirements
The student has completed all the "# YOUR CODE HERE" sections of the starter in the Inpainting section. The last code of the section should show an image with 3 panels: the original image, the mask of the car, and a new image where the background has been substituted with a Mars landscape

## Interactive App

### Criteria
The students use the app, showing they understand how to run SAM to segment the subject and substitute the background or the subject with text prompts

### Submission Requirements
The student has run the app, clicked on the public URL link, and tested the functionality with a few images. The student provides the results either by taking screenshots or by downloading the resulting image and uploading it as part of the submission

# Suggestions to Make Your Project Stand Out
## Study how parameters affect the result
Try the same prompt with different values for the Classifier-Free Guidance Scale and record the results.

## Prompt engineering
Imagine a not-so-simple scene you want to obtain starting from a picture you have. Keeping the random seed fixed, experiment with prompt engineering by iteratively adding or removing elements to the text prompt and record the effects until you get close enough to your original idea

## Iterative changes
Experiment with modifying an image by passing it through the app multiple times. For example, select the subject, substitute the background, then download the results and upload it again as the input image. Then substitute the subject.