# Automatic Number Plate Recognition under Foggy Conditions

**Problem description**

Domain of interest: Security / Transport

Automatic Number Plate Recognition (ANPR) identifies vehicle number plates using images or video. This technology is used by authorities
to find stolen cars or bikes, monitor suspicious vehicles, and spot traffic violations. ANPR is also used by the government or businesses to
automate parking facilities and tolls, which enhances efficiency and reduces congestion.

A limitation of ANPR is due to the environmental factor of poor weather conditions. Reduced visibility makes it hard to detect number plates
and recognise the characters on them. One type of condition that greatly reduces visibility is fog, which is significantly relevant in the UK. It is
difficult for human operators to read the plates manually in these conditions; enhancing the images is time-consuming, and human judgment
may be inconsistent. This means there is a need for artificial intelligence (AI), particularly computer vision techniques, to challenge this problem.

There is active research in this area. Varma P . et al. (2020) used OpenCV and machine learning techniques on Indian vehicle number plates
under different challenging conditions, such as varied light intensity, blurriness, angled positions, and worn-out number plates. Tote et al.
(2023) achieved 85% accuracy using TensorFlow in detecting Indian license plates with different light intensities and varying distances and
angles. Our group is motivated to work on this project to build on existing efforts by developing an AI-based solution to improve ANPR
performance in foggy conditions.

**Aims and Objectives**

The aim of this project is to deploy intelligent systems to accurately detect number plates and recognise its characters under foggy
conditions.

The following measurable objectives have been identified:

1. Collect credible datasets from the internet
2. Preprocess data: applying image enhancements
3. Model training: plate detection, character segmentation, character recognition
4. Model selection: choose a suitable model for the task
5. Evaluation: make predictions to be compared to validation set
