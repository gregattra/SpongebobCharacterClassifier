<h1>Spongebob Character Classifier</h1>
<h3>Overview</h3>
<p>This machine learning system will classify your favorite Spongebob Squarepants characters&mdash;assuming your favorite characters
are among the following:</p>
<ul>
    <li>Spongebob Squarepants</li>
    <li>Plankton</li>
    <li>Gary</li>
    <li>Patrick Star</li>
    <li>Sandy Cheeks</li>
    <li>Mr. Krabs</li>
    <li>Squidward</li>
</ul>

<h3>Details</h3>

<p>This project implements a three layer standard neural network. The overall architecture is as follows:</p>
<ul>
    <li>Input Layer --> 98 flattened image examples, each of original shape 100 x 100 x 3 (RGB)</li>
    <li>Hidden Layer --> A fully connected layer of input units 30000 and output units 10</li>
    <li>Activation --> ReLU activation layer</li>
    <li>Output Layer --> A fully connected layer of input units 10 and output units 7 (the number of classes)</li>
    <li>Output Activation --> Softmax activation layer</li>
</ul>


<h3>Instructions:</h3>
<p>To test the tool:</p>
<ol>
    <li>Download or clone this repository.
    <li>Find a quality image of your favorite Spongebob Character</li>
    <li>Save the image to the directory: <em>SpongebobCharacterClassifier/datasets/user_images</em></li>
    <li>Run <em>main.py</em></li>
</ol>

<p>Once the process finishes, you should see a plot of your chosen character image, labeled with the correct character name :)</p>