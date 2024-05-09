<h1>NeuroWhiz - Make It More Accurate...</h1>

![NeuroWhiz Logo](images/neurowhiz-high-resolution-logo-transparent-resized.png)

Welcome to NeuroWhiz, our Brain Tumor Segmentation and Edge Detection application!

Are you tired of manually diagnosing brain tumor subregions and boundaries through MRIs? Introducing NeuroWhiz, a state-of-the-art tool that automates brain tumor segmentation and edge detection. Our model not only identifies tumor subregions but also delineates the boundaries, providing radiologists and neurosurgeons with more confidence and accuracy in their diagnoses and decision-making.
NeuroWhiz leverages the latest explainability techniques to offer insights into the decision-making process of our AI model. The NeuroWhiz application processes 3D multimodal MRI images and segments brain tumors, including their subregions, while also detecting the tumor boundaries. Its user-friendly interface ensures ease of use, saving you time. Trust NeuroWhiz for faster, more precise brain tumor diagnoses.

Analyzing brain MRIs has never been easier. Our advanced framework takes multimodal MRI scans and segments brain tumors while detecting their edges with precision.
NeuroWhiz isn't just about convenience—it's about accuracy. Our deep learning model harnesses the power of self-supervised learning and employs a unique dual-decoder architecture that emphasizes edge identification and enhanced segmentation accuracy. By using a dual-decoder 3D-Unet model, we prioritize accuracy and fine-grained detail in tumor segmentation. Additionally, our model includes a tumor edge detection task, moving beyond traditional single-decoder methods. Below are some results from NeuroWhiz.

<h1>Unleash the Power of Precision: A User Guide for 3D Brain Tumor Segmentation and Edge Detection</h1>

Welcome! This comprehensive guide empowers you to harness the capabilities of our innovative web application for 3D brain tumor segmentation and edge detection. This tool plays a vital role in medical image analysis, aiding in the localization, characterization, and treatment planning of brain tumors.

<h2>Steps to Use the Tool:</h2>

1. **Navigate to the 'Tool' Page:** Within the web app, locate the designated section for tumor segmentation and edge detection.
2. **Prepare Your Input Data:**
    * Ensure you have four separate modalities of 3D MRI images in NIfTI (.nii) format (T1, T2, T1ce, and FLAIR).
    * **Create a Single Zip Archive:** Combine all four NIfTI images into a single compressed zip folder for efficient upload.
    * Make sure each of 4 .nii files ends with following strings: '_t1.nii', '_t2.nii', '_t1ce.nii', '_flair.nii'.
    * Sample zip folder inputs can be found [here](https://drive.google.com/drive/folders/1scIsgHcb5ykqyp9uK3XOyGNN-3O6aPW-?usp=drive_link)
3. **Upload Your Data:**
    * Locate the designated upload area on the tool page.
    * Click the "Browse Files" button or its equivalent.
    * Select your prepared zip folder containing the four MRI images.
    * Click "Upload" or a similar action button to initiate the process.
4. **Wait for the Results:** The tool will automatically analyze your uploaded data. Be patient, as processing complex medical images might take a few minutes.

5. **Visualize and Download Results:**
    * Once processing is complete, the tool will present you with the segmentation mask and edge mask visualizations.
    * In addition to that, as XAI is integrated, you can also visualize the saliency maps to understand the model's decision-making process. 
    * You'll be able to examine these visualizations directly within the web app to gain insights into the tumor's location and boundaries.
    * Download options might also be available to save the masks for further analysis on your local machine.

<h2>Additional Tips and Considerations:</h2>

* **Data Quality:** For optimal results, ensure the uploaded MRI images are high quality and free from artifacts (distortions or errors).
* **Interpretation:** While the tool provides segmentation and edge detection results, consulting with a qualified medical professional for diagnosis and treatment planning remains crucial.
* **Ongoing Development:** Stay tuned! We're constantly striving to enhance our tool's capabilities and address user feedback.
               



