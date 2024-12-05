# Dockerfile Bug: Missing Application Code

This repository demonstrates a common error in Dockerfiles: forgetting to copy the necessary application code into the image.  The provided `Dockerfile` installs Python dependencies but omits the crucial step of copying the application's Python script.

The solution demonstrates the correct way to copy the application code and run it within the Docker container.