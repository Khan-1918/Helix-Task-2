# Helix-Task-2
Image Enhancement and Quality Segregation Documentation

Objective
To process and improve image quality by:

Validating Image Readability: Identify unreadable or bad images.
Enhancing Images: Resize, denoise, sharpen, and adjust brightness and contrast to improve quality.
Classifying Enhanced Images: Segregate good images based on defined criteria (dimensions and brightness).
Saving Results: Organize enhanced and good images into dedicated directories for further use.

Mount Google Drive:

Access images stored in Google Drive.
Ensure necessary directories exist for input and output.

Step 1: Validate and Read Images:

Iterate through images to check format (.jpg, .jpeg, .png) and readability.
Log file type counts and flag unreadable or bad images.

Step 2: Enhance Images:

Resize large images for consistency.
Denoise images to reduce artifacts.
Sharpen details using kernel filters.
Adjust brightness and contrast for better visibility.
Save enhanced images to a separate directory.

Step 3: Classify Enhanced Images:

Good Images (Gray Conversion):
Convert enhanced images to grayscale.
Check dimensions and mean brightness.
Save grayscale good images in a dedicated folder.

Good Images (RGB):
Evaluate dimensions and average brightness across RGB channels.
Save high-quality RGB images in a separate directory.

Output:

Log the count of images processed, enhanced, and classified as good or bad.
Organize good and enhanced images into respective folders.

Criteria for Image Classification
Good Images:

Minimum Dimensions: Height or width ≥ 1000 pixels.

Brightness Threshold:
Gray Conversion: Mean pixel intensity ≥ 50.
RGB: Average brightness across channels ≥ 50.

Enhanced Images:

Successfully processed images after resizing, denoising, sharpening, and brightness adjustments.

Deliverables
Processed Image Counts:

Total number of valid images.
Count of images enhanced and saved.
Classification results (good vs. bad images).
Output Directories:

Enhanced Images: /Enhanced 3_Images
Good Gray Images: /Good_Images
Good RGB Images: /Good GBR_Images
Insights:

Proportion of enhanced images that meet "good" criteria.
Summary of failed or unreadable images.

Conclusion

This workflow ensures systematic enhancement and classification of images, resulting in a well-organized dataset with high-quality outputs. The structured directories make it easy to utilize good images for further analysis or processing.
