<h1>Secure Data Hiding in Image Using Steganography</h1>
<h2>Overview</h2>
<p>
  This project applies a technique for safely concealing data in an image via steganography methods. Steganography is the process of embedding messages within other non-secret information, like images, in a manner that is not easily perceptible to the naked eye.
</p>

<ul>
<h2>Features</h2>
<li>Hide data in images securely through LSB (Least Significant Bit) steganography</li>
  <li>Supports multiple image types (e.g., PNG, BMP, JPEG).</li>
  <li>Basic command-line interface for simplicity.</li>
  <li>Encryption of the concealed data for added protection.</li>
</ul>

<ul>
  <h2>Table of Contents</h2>
  <li>Installation</li>
  <li>Usage</li>
  <li>Contributing</li>
  <li>License</li> 
</ul>

<h2>Installation</h2>
<h3>Clone the repository</h3>
<p> git clone https://github.com/benimadhav188/Aicte_Project.git
cd Aicte_Project</p>
<h3>Install necessary dependencies</h3>
<h4>Ensure you have Python installed, then install the required libraries:</h4>
<p>pip install -r requirements.txt</p>

<h2>Usage</h2>
<h3>Hiding Data</h3>
<p>python hide_data.py -i input_image.png -d secret_data.txt -o output_image.png</p>
<ul>
  <li>Input image file path</li>
  <li>Data file containing the secret message</li>
  <li>Output image file path where the data will be hidden</li>
</ul>
<h2>Extracting Data</h2>
<h4>To extract the hidden data from an image use</h4>
<p>python extract_data.py -i output_image.png -o extracted_data.txt</p>
<h4>This will extract the hidden data from my_image_with_data.png and save it to extracted_secret.txt.</h4>
<h2>Contributing</h2>
<p>Contributions are appreciated! If you'd like to contribute, please fork the repository and send a pull request with your changes.</p>
<h2>License</h2>
<p>This project is licensed under the MIT License</p>

<h2>Acknowledgements</h2>
<ul>
  <li>Steganography Techniquies</li>
  <li>Phython Imaging Library(PIL)</li>
  <li>Cryptography Library</li>
</ul>
<h2>Feedback</h2>
<p>If you have any feedback, suggestions, or questions regarding the project, please create an issue in the repository or contact me at:</p>
<a href= "benimadhav31@gmail.com">benimadhav@gmail.com</a>
