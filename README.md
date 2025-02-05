<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Potato Leaf Disease Detection</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 40px;
            background-color: #f8f9fa;
        }
        h1, h2, h3 {
            color: #343a40;
        }
        code {
            background-color: #e9ecef;
            padding: 3px;
            border-radius: 4px;
        }
        pre {
            background: #e9ecef;
            padding: 10px;
            border-radius: 5px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <h1>Potato Leaf Disease Detection</h1>
    
    <h2>Overview</h2>
    <p>This project uses a Convolutional Neural Network (CNN) to detect diseases in potato leaves, specifically targeting early blight and late blight.</p>
    
    <h2>Project Structure</h2>
    <ul>
        <li><code>datasets/</code> - Contains training and testing images.</li>
        <li><code>Train_potato_disease.ipynb</code> - Jupyter Notebook for training the model.</li>
        <li><code>app.py</code> - Streamlit web application for disease detection.</li>
        <li><code>requirements.txt</code> - Required dependencies.</li>
        <li><code>trained_plant_disease_model.keras</code> - Trained CNN model.</li>
    </ul>
    
    <h2>Installation</h2>
    <p>Follow these steps to set up the project:</p>
    <pre><code>git clone https://github.com/VedantBende/potato-leaf-disease-detection.git
cd potato-leaf-disease-detection
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt</code></pre>
    
    <h2>Usage</h2>
    <p>To run the web application:</p>
    <pre><code>streamlit run app.py</code></pre>
    <p>Upload an image of a potato leaf to get a diagnosis.</p>
    
    <h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
