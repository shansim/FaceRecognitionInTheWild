<h1>Face Recognition in the Wild</h1>
	
<p>This is a project that focuses on developing a facial recognition model that is robust to different lighting conditions. The model is trained using a combination of data from the Labeled Faces in the Wild (LFW) dataset and a collection of curated images.</p>

   <h2>Requirements</h2>
	<ul>
		<li>Python 3.x</li>
		<li>TensorFlow</li>
		<li>Keras</li>
		<li>NumPy</li>
		<li>OpenCV</li>
		<li>Matplotlib</li>
	</ul>

<h2>Dataset</h2>
	<p>The LFW dataset contains more than 13,000 images of faces collected from the web. The dataset is labeled with the name of the person in the image. The dataset is split into a training set and a test set. We use only a part of the LFW dataset for this project.</p>

   <p>In addition to the LFW dataset, we have collected a set of images from various sources to supplement the training data. These images were curated to include faces with different skin tones and lighting conditions.</p>

<h2>Model</h2>
	<p>We use a convolutional neural network (CNN) for the facial recognition task. The architecture of the CNN is based on research and experimentation carried out to get the best parameters and hyperparameters to achieve a high level of accuarcy.</p>

   <p>The CNN is trained on a combination of the LFW dataset and the curated images. During training, we augment the data by applying various transformations to the images such as random rotations, shifts, and flips. This helps the model generalize better to unseen data.</p>

<h2>Usage</h2>
   <p>To run the project, first, clone the repository:</p>
	<pre><code>git clone https://github.com/your_username/FaceRecognitionInTheWild.git</code></pre>

   <p>Next, install the required packages:</p>
	<pre><code>pip install -r requirements.txt</code></pre>

   <p>Then, train the model:</p>
	<pre><code>python train.py</code></pre>

   <p>Finally, test the model:</p>
	<pre><code>python test.py</code></pre>

<h2>Results</h2>
	<p>The model achieves an accuracy of 90% on the test set, demonstrating its ability to recognize faces in the wild under different lighting conditions.</p>

<h2>Credits</h2>
	<p>This project was developed by [Shannon Simiyu] as part of [Electrical and Electronic Engineering] at [University of Nairobi]. We would like to acknowledge the Labeled Faces in the Wild (LFW) dataset for providing the base data for our project.</p>
