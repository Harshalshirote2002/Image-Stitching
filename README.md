# Image Stitching

The `panorama.py` file comprises the code for stitching two images. 

This is achieved by leveraging the SIFT algorithm to accurately detect and match keypoints, resulting in a panoramic composition.

# Instructions to use
run the driver.py file using a command as such:

`python ./driver.py -f path_to_image1 -s path_to_image2`

# Demo

Input `Image1`:

![image](https://github.com/Harshalshirote2002/Image-Stitch/assets/75237728/0b558a48-8d4b-4c48-9c85-dc9035b6edbf)

Input `Image2`:

![image](https://github.com/Harshalshirote2002/Image-Stitch/assets/75237728/1d7b39fd-93bb-4738-b112-5e89997d8261)

Obtained keypoint matches:

![image](https://github.com/Harshalshirote2002/Image-Stitch/assets/75237728/0de2441e-3e1a-489c-8b90-7e7a34c3979e)

Note that the images are in order: ImageB, ImageA.

Final "stitched" Panorama:

![image](https://github.com/Harshalshirote2002/Image-Stitch/assets/75237728/b8756b2f-5984-46d4-825e-5803e88cd965)

### Note
For optimal results, it's crucial to provide the input in the specified order; otherwise, the output may not yield the desired outcome.


