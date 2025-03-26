# guess-the-doodle

Im using this publicly available dataset: https://github.com/googlecreativelab/quickdraw-dataset?tab=readme-ov-file
My goal is to test different ways for an AI player to guess the players drawing in my RS project: https://gitlab.com/matf-bg-ac-rs/course-rs/projects-2024-2025/SketchIt.

What im going to be trying:
 - Using a pretrained model to guess the image
 - Using a pretrained model to make an image embedding and store it to a vector database. Guess the drawing by embedding similarity.
 - Making my own CNN
 - Using a multimodal LLM to guess the image