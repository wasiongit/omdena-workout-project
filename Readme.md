1. For making a mobile app with Pose classification and reps counter First we need to train the ML model on colab or local machine as in the notebook Modified_Pose_classification_(extended).ipynb   
![lunges_count_gif_AdobeExpress](https://user-images.githubusercontent.com/84765303/221342911-9f1e3eb0-345e-43bc-8a72-3ad1cbdefcc9.gif)

original video :https://www.youtube.com/watch?v=3XDriUn0udo

2. To recognize poses we use the k-nearest neighbors algorithm (k-NN) because it's simple and easy to start with. The algorithm determines the object's class based on the closest samples in the training set.

3. Next We will train the model with the Lunges dataset https://drive.google.com/file/d/1iws4yh0dpNYzU-Q5b2SuT3SJqnUss_U9/view?usp=sharing and get the outputs fitness_poses_csvs_out(for testing in the notebook) and fitness_poses_csvs_out.csv (for mobile app)

4. Classification and counting accuracy can be checked by the predefined functions in the notebook with the help of fitness_poses_csvs_out

5. Then we will take the CSV file (fitness_poses_csvs_out.csv) and Build the app according to the official documentation https://developers.google.com/ml-kit/vision/pose-detection/classifying-poses#4_integrate_with_the_ml_kit_quickstart_app
