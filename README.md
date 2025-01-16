# Preprocessing-Handwritten-Digit-Images-and-Converting-to-CSV-File-Using-Numpy

**Description:**
The goal of this exercise is to familiarize students with the steps of preprocessing images and converting them into data usable for machine learning models. You will process an image containing handwritten digits from 0 to 9 and save the final output in a CSV file. Each row of the CSV file represents one digit and consists of 784 columns (28 * 28 pixels).

**Steps:**

1. **Input Preparation**
   - Take a blank white sheet of paper and write the digits 0 to 9 in your own handwriting, ensuring they are of appropriate size. All digits should be written on a single sheet with sufficient spacing between them.
   - Use a camera or scanner to take a picture of the paper. Ensure the image is clear and free of additional noise.
   - Save the image in a common image format (e.g., JPEG or PNG).

2. **Image Processing**
   - Convert the image to grayscale.
   - For each digit, isolate a bounding box containing the digit and resize it to 28x28 pixels. If the digit's dimensions are smaller than 28x28 pixels, pad the surrounding area with white.

3. **Conversion to Numpy Array**
   - Convert each 28x28 pixel image into a one-dimensional array with 784 elements.
   - Combine the 10 one-dimensional arrays into a two-dimensional array with dimensions of 10 rows and 784 columns.

4. **Save to CSV File**
   - Save the two-dimensional array to a CSV file. Each row of the CSV file represents one digit and contains 784 columns (the pixel values of the image).

**Translation:**

**Preprocessing Handwritten Digit Images and Converting to CSV File Using Numpy**

**Description:**
The goal of this exercise is to familiarize students with the steps of preprocessing images and converting them into data usable for machine learning models. You will process an image containing handwritten digits from 0 to 9 and save the final output in a CSV file. Each row of the CSV file represents one digit and consists of 784 columns (28 * 28 pixels).

**Steps:**

1. **Input Preparation**
   - Take a blank white sheet of paper and write the digits 0 to 9 in your own handwriting, ensuring they are of appropriate size. All digits should be written on a single sheet with sufficient spacing between them.
   - Use a camera or scanner to take a picture of the paper. Ensure the image is clear and free of additional noise.
   - Save the image in a common image format (e.g., JPEG or PNG).

2. **Image Processing**
   - Convert the image to grayscale.
   - For each digit, isolate a bounding box containing the digit and resize it to 28x28 pixels. If the digit's dimensions are smaller than 28x28 pixels, pad the surrounding area with white.

3. **Conversion to Numpy Array**
   - Convert each 28x28 pixel image into a one-dimensional array with 784 elements.
   - Combine the 10 one-dimensional arrays into a two-dimensional array with dimensions of 10 rows and 784 columns.

4. **Save to CSV File**
   - Save the two-dimensional array to a CSV file. Each row of the CSV file represents one digit and contains 784 columns (the pixel values of the image).
