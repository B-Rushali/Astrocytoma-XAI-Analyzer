🧠 Astrocytoma XAI Analyzer
A deep learning-based tool for segmenting brain tumors (astrocytomas) in MRI scans using a U-Net architecture, with explainability powered by LIME.

🔍 Features
🧬 MRI Image Segmentation using U-Net.
⚡ Lightweight SqueezeNet Encoder (optional hybrid).
🧠 Explainable AI with LIME visualizations.
🎛️ Easy-to-use GUI built with Gradio.
📁 Project Structure
Major_Code.ipynb # Main Jupyter Notebook README.md # Project Overview app.py # Gradio interface (optional) brain-mri-unet.pth # Trained U-Net model

🛠️ How to Run
Clone this repo
git clone https://github.com/Deekshitharachakatla/Astrocytoma-XAI-Analyzer.git`
Install dependencies
pip install -r requirements.txt`
Launch Gradio app
bash python app.py
Upload MRI → Get segmented output with LIME explanation.
🧪 Dataset
Used publicly available glioma MRI dataset. Images are resized to 128x128 RGB format.

💡 Technologies
Python, PyTorch
U-Net, SqueezeNet
Gradio, LIME
OpenCV, NumPy
📸 Sample Output
Tumor segmented with mask LIME overlay highlights the influential pixels

🙋‍♀️ Author
Bunedu Rushali B.Tech | CSE | BVIT Hyderabad College of Engineering for Women
