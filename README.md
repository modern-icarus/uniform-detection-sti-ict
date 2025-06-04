🎓 Uniform Detection at STI College Balagtas
This project aims to detect whether students are wearing their uniforms using a custom-trained YOLO (You Only Look Once) model. It was developed as a Computer Vision task using real-life data collected from STI College Balagtas.

📸 Step 1: Dataset Collection
We started by collecting images of students from STI College Balagtas, both:

Wearing their uniforms

Not wearing their uniforms

We requested our friends and classmates to share their pictures to build a diverse and representative dataset.

🏷️ Step 2: Annotation
To prepare the dataset for training, we used:

makesense.ai — a free online tool for labeling images

Each image was annotated with bounding boxes and labels:

uniform

no_uniform

The annotations were saved in YOLO format to ensure compatibility with the YOLO model.

🧠 Step 3: Model Development
We used a YOLO-based object detection approach:

Prepared the dataset (images + labels)

Trained the model using a YOLO implementation

Monitored the training performance using training/validation metrics

The model was trained to distinguish between students wearing and not wearing uniforms.

📈 Step 4: Results
The model was able to:

Accurately detect uniforms in real-world scenarios

Perform well even with a relatively small dataset

Results are visualized through bounding boxes in test images, clearly indicating whether a uniform is present or not.

🛠️ Technologies Used
Python

Jupyter Notebook

YOLO (You Only Look Once)

makesense.ai

OpenCV / PyTorch
