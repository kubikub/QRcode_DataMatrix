<!DOCTYPE html>
<html>
<body>
    <h1>Real Time QR CODE Data Matrix Reader</h1>
    <h2>Description</h2>
    <p>This project use OpenCV and <a href=https://github.com/zxing-cpp/zxing-cpp>Zxing-cpp library</a> and internal or usb camera on Linux or Windows PC.</p>
    <p>When Datamatrix or any compatible with Zxing-cpp QR Code is detected a bouding box is created on the camera picture frame and a thread is writing informations in a CSV File.</p>
    <h2>Installation</h2>
    <p>This project requires Python 3.11. After cloning the repository, install the necessary dependencies with the following command:</p>
    <pre><code>pip install -r requirements.txt</code></pre>
    <h2>Run</h2>
    <p>In a Python Env simply run : </p>
    <pre><code>python3 Data_Matrix_Reader_2_CSV.py<code></pre>
</body>
</html>
