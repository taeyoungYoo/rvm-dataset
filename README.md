# Dataset for Waste Classification

This is a dataset for waste classification in reverse vending machine, consisting of 3,084 images. We constructed and publish this dataset to serve as a baseline dataset of studies for `reverse vending machine`, and `waste classification`.

The figure below is the samples of this dataset.

## Composition of dataset
- The images are divided into the top view and the front view primary.
- The top view and the front view are further divided into aluminum cans, PET, non-target objects
- Non-target objects are inappropriate object(IAO) and intentional fraud objects.

### train dataset
- 850 Aluminum can
- 810 PET
- 636 Non-target(Inappropriate objects)

### test dataset
- 264 Aluminum can
- 264 PET
- 140 Non-target objects(fraud objects)
- 120 Non-target objects(Inappropriate objects)

## Intentional fraud objects

The fraud objects represent the intentionally made look-alike objects to fool the classification system. They are printed PET beverage containers, printed aluminum cans, and objects made with only the label of the PET beverage container. The printed look-alike frauds are printed in color or grayscale.

The figure below is the samples of intentional frauds.

## Download

If you are using our dataset, please give a citation of this repository. <br>
You can download the dataset [here](https://drive.google.com/drive/folders/1a2QQL3Nd8GYCUrMPWDopDkoM6xpf-HFj?usp=sharing).
