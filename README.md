# **Face Features Comparison and Verification Program**

This program performs face feature comparisons and checks identity verification based on user input. The comparisons are made by analyzing physical features such as eye, nose, lip, and face proportions, as well as the color values of the skin. It uses weighted values and functions to determine how similar the input features are to predefined "registered" values. If the calculated difference is within an acceptable range, identity verification is successful.

## **Features:**

- Input fields for various facial features (eye, nose, lips, and face size).
- RGB color model inputs for facial color comparison.
- Weighted values for registered face proportions and features.
- A series of functions to process and compare the entered values to predefined registered face feature values.
- Identity validation based on the differences between input values and registered ones.

## **How It Works:**

1. **Input Fields:**
   - Users are prompted to enter their face feature measurements: eye width/height, nose width/height, lip width/height, and face width/height.
   - RGB color values for facial skin tones are also requested.

2. **Processing Functions:**
   - A series of comparison functions calculate weighted values and feature differences.
   - Predefined feature values are used to compare against the user's inputs (e.g., `kayitliGozAgirlikliOrani`, `kayitliYuzAgirlikliOrani`, etc.).

3. **Feature Comparison:**
   - The program uses different thresholds and mathematical functions to process the entered feature values, calculate differences, and assign weights to the feature ratios.
   - If the differences are below a certain threshold, identity verification is confirmed. Otherwise, the user is asked to try again.

## **Inputs:**

- Eye Width (Göz Eni)
- Eye Height (Göz Boyu)
- Face Width (Yüz Eni)
- Face Height (Yüz Boyu)
- Nose Width (Burun Eni)
- Nose Height (Burun Boyu)
- Lip Width (Dudak Eni)
- Lip Height (Dudak Boyu)
- RGB Color Values for Skin (Red, Green, Blue)

## **Outputs:**

- Calculated proportions for each facial feature.
- Displayed numerical value for skin tone RGB analysis.
- Validation message: Whether the input matches registered values or not.

## **Example:**

The program prompts the user to input their facial measurements and RGB values:

