
<h1>QR Code Generator</h1>
<p>This script generates QR codes from the input data provided by the user. It utilizes the qrcode library to create QR codes and the PIL (Python Imaging Library) to save them as images. Users can input data spanning multiple lines, and the script terminates upon entering "exit".</p>

<h2>Features</h2>
<ul>
    <li>Multi-line Input: Users can input data spanning multiple lines.</li>
    <li>QR Code Generation: Generates QR codes based on the entered data.</li>
    <li>Customization: Allows customization of QR code version, error correction level, box size, and border.</li>
    <li>Image Saving: Saves the generated QR code as an image file.</li>
</ul>

<h2>How to Use</h2>
<h3>Running the Script:</h3>
<ol>
    <li>Execute the script in a Python environment.</li>
    <li>You'll be prompted to enter data to be encoded.</li>
    <li>Input each line of data, pressing Enter after each line.</li>
    <li>To finish inputting data, type "exit" (case-insensitive) and press Enter.</li>
</ol>
<h3>QR Code Generation:</h3>
<ul>
    <li>Once the input is complete, the script generates a QR code based on the entered data.</li>
    <li>The generated QR code is saved as "QR.png" in the same directory as the script.</li>
</ul>

<h2>Requirement</h2>
<ul>
    <li>Python 3.x: Ensure you have Python installed on your system.</li>
    <li>qrcode: Install the qrcode library using pip install qrcode.</li>
    <li>PIL: Install the Python Imaging Library using pip install Pillow.</li>
</ul>
<h2>Note</h2>
<ul>
<li>Ensure that the necessary dependencies are installed before running the script.</li>
</ul>
